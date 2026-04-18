You are running a weekly WebSearch job scan for Sokhana Caza (Sales Director, SGX FX, Johannesburg, South Africa). Scan only — no git operations, no Discord notifications (the workflow handles those).

## Step 1 — Read config
Read `portals.yml`. Extract:
- All entries in `search_queries` where `enabled: true`
- All companies in `tracked_companies` where `scan_method: websearch` AND `enabled: true` — use their `scan_query` as additional queries
- Skip any company with an `api:` field (those run in the Greenhouse scan)

Also read `title_filter` and `location_filter`.

## Step 2 — Read dedup sources
Read `data/scan-history.tsv` and `data/pipeline.md`.

## Step 3 — Run WebSearch queries
For each query from Step 1, run WebSearch.
Extract: title, URL, company from each result.
Apply title_filter: at least 1 positive keyword in title, 0 negative keywords.
Apply location_filter: skip US-only roles (e.g. "US only", "must be located in the US"); flag ambiguous as [⚠️ verify SA eligibility].

## Step 4 — Deduplicate
Skip any URL already in scan-history.tsv or pipeline.md (exact URL or normalised company+role match).

## Step 5 — Update files
- Append new offers to `data/pipeline.md` under Pending: `- [ ] {url} | {company} | {title}`
- Append ALL seen URLs to `data/scan-history.tsv`: url, today's date (YYYY-MM-DD), portal (query name), title, company, status (added/skipped_title/skipped_dup/skipped_location)

## Step 6 — Print summary
Output a markdown table: Company | Title | URL | SA status

Candidate target roles: Institutional Sales, Electronic Trading Sales, Customer Success, Account Management, Business Development, Sales Director, Head of Sales.
Remote only — SA-eligible positions only.
