You are running a weekly ATS API job scan for Sokhana Caza (Sales Director, SGX FX, Johannesburg, South Africa). Scan only — no git operations, no Discord notifications (the workflow handles those).

Companies in `portals.yml` live on different ATS platforms (Greenhouse, Lever, Ashby, SmartRecruiters). Each exposes a JSON API but with a **different schema** — you must parse each according to its `ats:` field.

## Step 1 — Read config
Read `portals.yml`. Extract only companies in `tracked_companies` where:
- `enabled: true`
- The company has an `api:` field

Each such company has an `ats:` field — one of `greenhouse`, `lever`, `ashby`, `smartrecruiters`. Use it to choose the parser in Step 3.

Also read `title_filter` and `location_filter`.

## Step 2 — Read dedup sources
Read `data/scan-history.tsv` and `data/pipeline.md`.

## Step 3 — Fetch each API and parse by ATS type
For each company, use WebFetch to GET the `api:` URL, then map fields per its `ats:`:

| ATS | Job list path | Title | Job URL | Location | Notes |
|-----|---------------|-------|---------|----------|-------|
| `greenhouse` | `jobs[]` | `title` | `absolute_url` | `location.name` | — |
| `lever` | top-level array `[]` | `text` | `hostedUrl` | `categories.location` (+ `workplaceType`) | — |
| `ashby` | `jobs[]` | `title` | `jobUrl` | `location` (+ `isRemote`, `secondaryLocations`) | Only include jobs where `isListed` is true |
| `smartrecruiters` | `content[]` | `name` | `https://jobs.smartrecruiters.com/{token}/{id}` (build from posting `id`; `{token}` is the company slug in the api URL) | `location.fullLocation` or `location.city`+`location.country` (+ `location.remote`) | **Paginated, 100/page.** If `totalFound` > returned count, fetch more pages with `?offset=100`, `?offset=200`, … until all are read |

Apply title_filter: at least 1 positive keyword in title, 0 negative keywords.
Apply location_filter: skip US-only roles; flag ambiguous as [⚠️ verify SA eligibility]. If the ATS marks a role remote (`isRemote`/`location.remote`/`workplaceType: remote`), treat location as more flexible but still verify SA eligibility.

If an API returns a non-200 / non-JSON response, note it in the summary as a possible stale endpoint and continue — do not abort the scan.

## Step 4 — Deduplicate
Skip any URL already in scan-history.tsv or pipeline.md.

## Step 5 — Update files
- Append new offers to `data/pipeline.md` under Pending: `- [ ] {url} | {company} | {title}`
- Append ALL seen URLs to `data/scan-history.tsv`: url, today's date (YYYY-MM-DD), portal (company + ' ' + ats + ' API'), title, company, status (added/skipped_title/skipped_dup/skipped_location)

## Step 6 — Print summary
Output a markdown table: Company | Title | URL | Location | SA status. Note any endpoints that failed to return jobs.

Candidate target roles: Institutional Sales, Electronic Trading Sales, Customer Success, Account Management, Business Development, Sales Director, Head of Sales.
Remote only — SA-eligible positions only.
