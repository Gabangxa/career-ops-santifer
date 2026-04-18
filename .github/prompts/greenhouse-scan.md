You are running a weekly Greenhouse API job scan for Sokhana Caza (Sales Director, SGX FX, Johannesburg, South Africa). Scan only — no git operations, no Discord notifications (the workflow handles those).

## Step 1 — Read config
Read `portals.yml`. Extract only companies in `tracked_companies` where:
- `enabled: true`
- The company has an `api:` field (Greenhouse API URL)

Also read `title_filter` and `location_filter`.

## Step 2 — Read dedup sources
Read `data/scan-history.tsv` and `data/pipeline.md`.

## Step 3 — Fetch Greenhouse APIs
For each company with an `api:` field, use WebFetch to GET the API URL.
Parse the JSON — each job has `title`, `absolute_url`, `location.name`.
Apply title_filter: at least 1 positive keyword in title, 0 negative keywords.
Apply location_filter: skip US-only roles; flag ambiguous as [⚠️ verify SA eligibility].

## Step 4 — Deduplicate
Skip any URL already in scan-history.tsv or pipeline.md.

## Step 5 — Update files
- Append new offers to `data/pipeline.md` under Pending: `- [ ] {url} | {company} | {title}`
- Append ALL seen URLs to `data/scan-history.tsv`: url, today's date (YYYY-MM-DD), portal (company + ' Greenhouse API'), title, company, status (added/skipped_title/skipped_dup/skipped_location)

## Step 6 — Print summary
Output a markdown table: Company | Title | URL | Location | SA status

Candidate target roles: Institutional Sales, Electronic Trading Sales, Customer Success, Account Management, Business Development, Sales Director, Head of Sales.
Remote only — SA-eligible positions only.
