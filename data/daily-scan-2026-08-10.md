# Daily Scan — 2026-08-10

## Top Matches (up to 10)

| Rank | Score | Company | Role | Source | URL |
|------|-------|---------|------|--------|-----|
| 1 | 4.50 | Customer.io | Senior Director, Sales EMEA | Remotive | https://remotive.com/remote/jobs/sales/senior-director-sales-5210703 |
| 2 | 4.35 | BVNK | Sales Director, Banking | Greenhouse | https://job-boards.greenhouse.io/bvnk/jobs/4924175101 |
| 3 | 3.55 | MindBridge Analytics | Customer Success Manager | Remotive | https://remotive.com/remote/jobs/customer-service/customer-success-manager-4680067 |

### Scoring notes

**Rank 1 — Customer.io, Senior Director, Sales EMEA (4.50)**
Archetype #1 Sales Director (5×0.35=1.75) + fully remote EMEA (5×0.20=1.00) + Senior Director seniority (5×0.20=1.00) + generic SaaS domain (3×0.25=0.75) = 4.50.
⚠️ Marketing automation SaaS — not fintech. $350k OTE is exceptional and remote EMEA is clean. Worth considering if open to SaaS beyond financial services. Note: previously seen 2026-07-27 as `skipped_title`; re-scored as match on Sales Director archetype.

**Rank 2 — BVNK, Sales Director, Banking (4.35)**
Archetype #1 Sales Director (5×0.35=1.75) + stablecoin/cross-border payments fintech (4×0.25=1.00) + Director seniority (5×0.20=1.00) + remote uncertain/3 (3×0.20=0.60) = 4.35.
BVNK builds stablecoin-native payment infrastructure for enterprise clients (Worldpay, Deel, Rapyd). Visa-backed. Director of Account Management PSP (4821225101) already in pipeline — this is a distinct Banking vertical role. ⚠️ Listed as "New York" on fintechcareers.com but also appears on Working Nomads as remote — verify SA eligibility before applying. Previously seen as `skipped_location` (2026-07-13, 2026-08-07); re-added pending SA remote verification with new Working Nomads signal.

**Rank 3 — MindBridge Analytics, Customer Success Manager (3.55)**
Archetype #3 CSM (4×0.35=1.40) + AI financial audit analytics (3×0.25=0.75) + Senior CSM (5+ yrs req) / Manager seniority 4 (4×0.20=0.80) + remote uncertain/3 (3×0.20=0.60) = 3.55.
MindBridge builds AI-powered audit and financial risk analytics for accounting/finance teams. CSM role requires 5+ years. ⚠️ Audit-analytics domain is adjacent but not direct FX/trading/institutional sales fit; verify SA remote eligibility and comp range. Genuinely new URL — first seen this scan.

### Deduplication corrections

The following appeared in initial search results but were found in scan-history and excluded from the pipeline:

| URL | Prior status | Reason |
|-----|-------------|--------|
| https://remotive.com/remote/jobs/customer-service/customer-success-manager-4822667 (AltScore) | `skipped_dup` (2026-07-01, 2026-07-31) | Same Remotive URL already processed twice |
| https://job-boards.greenhouse.io/btig27/jobs/7815467002 | `skipped_title` (2026-06-19) | US work auth required per prior evaluation |
| https://job-boards.greenhouse.io/btig27/jobs/8468553002 | `skipped_title` (2026-06-19) | US work auth required per prior evaluation |

---

## Stats

- Queries run: 15 (11 parallel WebSearch + 4 targeted follow-up)
- Greenhouse API: BLOCKED by egress proxy — all 10 API endpoints inaccessible this run
- Raw results: ~80 URLs surfaced across all queries
- After title filter: ~25 pass
- After dedup vs existing pipeline + scan history: ~14 new URLs
- Scored ≥ 3.5 (after full dedup): 3
- Deduplication corrections: 3 (AltScore Remotive dup ×2, BTIG US work auth ×2)
- Added to pipeline: 3

### Infrastructure note
Greenhouse API (`boards-api.greenhouse.io`) and direct job page fetches (`boards.greenhouse.io`, `job-boards.greenhouse.io`) were both blocked by the network egress proxy this session. As a result:
- 10 Greenhouse company APIs (Fireblocks, Chainalysis, Airwallex, Coinbase, Circle, Wise, Nium, Tipalti, Luno, Gemini) could not be fetched
- This is the main reason today's shortlist is shorter than typical — not a lack of new listings on those platforms

Scan-history partial read (lines 1–418 of 1030) in prior session context caused incomplete initial deduplication; corrected after full file check this session.

---

## Skipped (title mismatch / location / dedup samples)

| Company | Title | Reason |
|---------|-------|--------|
| sFOX | Sales Manager - Institutional | skipped_location (US/Remote only) |
| Priority Technology Holdings | Customer Success Manager | skipped_location (comp/location signals US-based) |
| BTIG | Franchise Sales, Healthcare — VP/Director | skipped_title (Healthcare domain) |
| Alpaca | Account Executive - US | skipped_location (US-focused per title) |
| Coconut Software | Customer Success Manager | skipped_title (below score threshold 3.0) |
| Customer.io | Customer Success Manager, EMEA (WWR) | skipped_dup (marketing SaaS, below threshold) |
| Esusu | Customer Success Manager | skipped_title (real estate/rent fintech, below threshold) |
| Revolut | Account Executive, Mid-Market | skipped_title (mid-market AE, below Director seniority) |
| Fidus Systems | Director of Business Development | skipped_title (embedded hardware, not fintech) |
| Visier Solutions | Account Executive | skipped_title (workforce analytics, not fintech) |
| iBase-t | VP of Sales | skipped_title (manufacturing ERP, not fintech) |
| Paysend | Head of Sales, B2B | skipped_title (startup.jobs blocked — unverified active) |
| Mangopay | Unknown role | skipped_title (title unverified, likely EU in-office payments platform) |
| AltScore | Customer Success Manager | skipped_dup (Remotive URL 4822667 already in scan history ×2) |
| BTIG | [title TBD] (job 7815467002) | skipped_dup (previously evaluated 2026-06-19, US work auth required) |
| BTIG | [title TBD] (job 8468553002) | skipped_dup (previously evaluated 2026-06-19, US work auth required) |
