# Daily Scan — 2026-11-04

> **Network note:** `boards-api.greenhouse.io`, `boards.greenhouse.io`, `job-boards.greenhouse.io`, `remotive.com`, and `weworkremotely.com` are blocked for direct WebFetch in this cloud session. All Greenhouse API pulls failed. Roles were identified via WebSearch snippets and Google index data — titles and remote policies are inferred from search results, not live page reads. Mark each for Playwright verification before applying.

## Top Matches (up to 10)

| Rank | Score | Company | Role | Source | URL |
|------|-------|---------|------|--------|-----|
| 1 | 4.15 | Zero Hash | Director of Enterprise Sales, Payments | Breezy HR | https://zero-hash.breezy.hr/p/e9d6291c8998-director-enterprise-sales-payments |

### Scoring detail

**1. Zero Hash — Director of Enterprise Sales, Payments (4.15)**
Zero Hash is a B2B crypto payments and stablecoin infrastructure company serving banks, fintechs, and exchanges. The Director of Enterprise Sales role targets enterprise payments clients; up to 40% travel; US-focused team. **⚠️ US-focused** — verify if SA global remote is eligible. Posted ~Oct 5, 2026 on BuiltIn/Breezy HR.
- Archetype fit (×0.35): 5 — Sales Director / Enterprise Sales, target #1/#2
- Domain relevance (×0.25): 4 — crypto payments infrastructure / stablecoin B2B (adjacent to FX/capital markets)
- Seniority match (×0.20): 5 — Director
- Remote-friendly (×0.20): 2 — US-primary team, SA remote unconfirmed

---

## Stats
- Queries run: 12 WebSearch (site: filters partially bypassed by Google) + 10 Greenhouse API calls (all blocked by network policy)
- Raw results: ~36 unique URLs extracted from search result snippets
- After title filter: ~18 passed positive title filter (no negatives matched)
- After dedup: 1 new (not already in scan-history.tsv or pipeline.md)
- Added to pipeline: 1

## Blocked infrastructure (⚠️ action needed)
The following domains are outside the cloud session's allowed network and must be added to network settings for full scan coverage:
- `boards-api.greenhouse.io` — Greenhouse API (10 company feeds failed)
- `boards.greenhouse.io` — Greenhouse job pages
- `job-boards.greenhouse.io` — Greenhouse job pages
- `remotive.com` — direct page verification
- `weworkremotely.com` — direct page verification

## Closed/inactive (found in search, removed from consideration)
- Notabene — Enterprise Account Executive, EMEA — confirmed closed (Castle Island Ventures: "no longer accepting applications" since April 2026)
- Fireblocks — Sales Director, Africa (ID 4643558006) — Dubai-based, archived/no longer accepting applications

## Skipped (title mismatch / score < 3.5 / dup / location)
| Status | Company | Title |
|--------|---------|-------|
| skipped_location (Istanbul on-site) | Sanction Scanner | Global Sales Director |
| skipped_title (energy/commodities, score 2.5) | Zema Global | Sales/Account Executive |
| skipped_title (AWS cloud consulting, not fintech) | AllCloud | Account Executive |
| skipped_location (London hybrid) | Papaya Global | EMEA Enterprise Sales Director |
| skipped_title (closed/archived) | Notabene | Enterprise Account Executive, EMEA |
| skipped_location (Dubai-based, archived) | Fireblocks | Sales Director, Africa (4643558006) |
