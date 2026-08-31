# Daily Scan — 2026-08-31

## Top Matches (up to 10)

No new qualifying roles found in today's scan. All searches returned URLs already present in
`data/scan-history.tsv`. The pipeline was already updated by an earlier run this morning
that added 3 entries (lines 1148–1150 of scan-history.tsv): Wiz VP Sales EMEA, Pebl Expand
Sales Director EMEA/APAC, and NMI CSM Cape Town Hybrid (below walk-away threshold).

Of those 3, 2 score ≥ 3.5 and are already in the pipeline for evaluation:

| Rank | Score | Company | Role | Source | URL |
|------|-------|---------|------|--------|-----|
| 1 | 4.25 | Wiz | Vice President, Sales EMEA | Remotive | https://remotive.com/remote/jobs/sales/vice-president-sales-emea-5689708 |
| 2 | 3.80 | Pebl | Expand Sales Director, EMEA/APAC | Remotive | https://remotive.com/remote/jobs/sales/expand-sales-director-5605598 |

> ⚠️ **Domain caveats:** Wiz is cloud security (not fintech/FX). Pebl is interactive content SaaS.
> Both were scored generously on seniority and remote-fit. Recommend verifying domain
> transferability and comp vs. ZAR 1.8M walk-away before prioritising.

---

## Stats
- Queries run: 11 (3 × HiringCafe, 2 × WeWorkRemotely, 1 × Remotive, 3 × Greenhouse search, 1 × CryptoJobsList, 1 × web3.career)
- Greenhouse API endpoints attempted: 10 (all blocked by network egress proxy — API unavailable in this environment)
- Raw results: ~55 URLs evaluated
- After positive title filter: ~8 pass
- After dedup with scan-history.tsv: 5 not previously seen
- After location / score filter: 0 new entries qualify (≥ 3.5 + remote-eligible from SA)
- Added to pipeline today (this run): 0
- Added to pipeline (earlier morning run, 2026-08-31): 2 scored entries above

---

## New URLs logged to scan-history.tsv today

| URL | Company | Title | Status |
|-----|---------|-------|--------|
| https://web3.career/director-of-sales-rarible/89753 | Rarible | Director of Sales ($350k–$400k) | skipped_location (NY/SF US-only) |
| https://weworkremotely.com/remote-jobs/credit-wellness-llc-inside-sales-account-executive | Credit Wellness LLC | Inside Sales - Account Executive | skipped_title |
| https://weworkremotely.com/remote-jobs/cockroach-labs-account-executive-singapore | Cockroach Labs | Account Executive, Singapore | skipped_location |
| https://remotive.com/remote-jobs/sales/high-ticket-financial-sales-specialist-team-lead-track-2090949 | FSE LLC | High-Ticket Financial Sales Specialist | skipped_title |
| https://weworkremotely.com/remote-jobs/your-resource-group-llc-remote-inside-sales-1 | Your Resource Group LLC | Remote Inside Sales | skipped_title |

---

## Skipped (title mismatch / location samples)
- Rarible | Director of Sales — NY/SF required (not remote globally)
- Cockroach Labs | Account Executive, Singapore — APAC-specific
- Eltropy | Customer Success Manager, Tier 1 (West) — Tier 1 support role
- Surge Staffing | Sales Director — IT professional services, not fintech institutional
- Coinbase | Senior Institutional Sales Associate, Remote – Singapore — APAC territory
- Twilio | Director EMEA Strategic Sales North — comms SaaS, not fintech
- BVNK | Sales Director (EU board) — duplicate of existing entries
- Experian | Sales Account Executive — consumer/retail credit, not institutional

---

## Notes on Greenhouse API Block
The network egress proxy blocks direct access to `boards-api.greenhouse.io` and
`job-boards.greenhouse.io` in this environment. The 10 target companies
(Fireblocks, Chainalysis, Airwallex, Coinbase, Circle, Wise, Nium, Tipalti, Luno, Gemini)
were not scanned via API this run. Web search was used as fallback — most of their
recent listings are already captured in the pipeline from prior scans (last full Greenhouse
scan: 2026-08-28). **Recommend:** manual Playwright verification of the Greenhouse board
for any of these companies if listings are time-sensitive.

---

## Pipeline Health
The pipeline is well-populated with **200+ pending evaluations**. Priority queue includes:
- Keyrock Director Institutional Derivative Sales (★★ 5.0/5, Added 2026-06-01)
- Xapo Bank Regional Head EMEA (★★ 5.0/5, Added 2026-05-13)
- Xapo Bank Head of Customer Success (★★ 5.0/5, Added 2026-05-13)
- Visa Business Development Director, Johannesburg (4.83/5, Added 2026-08-16)
- Kraken Sales Director Distribution EMEA (4.80/5, Added 2026-08-01)
- Chorus One Head of EMEA (4.75/5, Added 2026-07-19)
- Backbase Sales Director North/West Africa (4.70/5, Added 2026-08-01)
- Fireblocks VP Customer Success (4.90/5, Added 2026-07-10)

Run `/career-ops evaluate` on any URL or paste a JD to begin evaluating.
