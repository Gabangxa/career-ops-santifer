# Daily Scan — 2026-05-31

> **Verification:** unconfirmed (web session) — Greenhouse board pages, APIs, and job board sites all returned 403 Forbidden for direct fetch verification. Verify listing activity manually via browser or Playwright before applying.

## Top Matches (up to 10)

| Rank | Score | Company | Role | Source | URL |
|------|-------|---------|------|--------|-----|
| 1 | 4.50 | Breeze | Senior Account Executive — Payments | Greenhouse | https://job-boards.greenhouse.io/breezecash/jobs/4946386008 |
| 2 | 4.40 | Fireblocks | Account Executive, Payments | Greenhouse | https://job-boards.greenhouse.io/fireblocks/jobs/4600936006 |
| 3 | 4.25 | Circle | Director, Customer Success, EMEA | startup.jobs | https://startup.jobs/director-customer-success-emea-circle-2-4008741 |
| 4 | 4.00 | AppDirect | Senior Account Executive, EMEA | Greenhouse | https://boards.greenhouse.io/appdirect/jobs/6146284002 |
| 5 | 3.70 | Pindrop | Director, Customer Success | Remotive | https://remotive.com/remote/jobs/customer-service/director-customer-success-4286423 |
| 6 | 3.63 | Motive | Director of Account Management & Customer Success | Remotive | https://remotive.com/remote/jobs/sales-business/director-of-account-management-customer-success-4128289 |

## Scoring Notes

**Rank 1 — Breeze (4.50)**
Archetype 5×0.35=1.75 | Domain 5×0.25=1.25 | Seniority 4×0.20=0.80 | Remote 3.5×0.20=0.70
- Crypto/fiat universal payment layer startup ("building the universal payment layer to unify all currencies—fiat and crypto")
- "Senior Account Executive — Payments" = top archetype #1 fit; strong domain alignment with Sokhana's FX/payments background
- ⚠️ Verify SA remote eligibility — location not confirmed in listing; Greenhouse board is "breezecash"

**Rank 2 — Fireblocks (4.40)**
Archetype 5×0.35=1.75 | Domain 5×0.25=1.25 | Seniority 3×0.20=0.60 | Remote 4×0.20=0.80
- New listing (ID 4600936006) not previously seen; distinct from all existing Fireblocks entries in pipeline
- AE focused on "small to medium enterprise accounts across Crypto Native, Web3, and TradFi sectors" — payments vertical
- ⚠️ Slightly lower seniority than current Sales Director role; verify territory/region and confirm global remote eligibility

**Rank 3 — Circle (4.25)**
Archetype 4×0.35=1.40 | Domain 5×0.25=1.25 | Seniority 5×0.20=1.00 | Remote 3×0.20=0.60
- USDC/crypto payments fintech (Circle is the issuer of USDC stablecoin); Director-level CS, first post-sales hire in EMEA region
- Scope: migrate EMEA customers from US management, build out regional CSM team
- ⚠️ LinkedIn shows Dublin, Ireland office — verify if role is SA-remote eligible or requires Dublin in-person presence

**Rank 4 — AppDirect (4.00)**
Archetype 5×0.35=1.75 | Domain 3×0.25=0.75 | Seniority 4×0.20=0.80 | Remote 3.5×0.20=0.70
- Marketplace/commerce platform serving Financial Services clients among other verticals; EMEA territory
- New Greenhouse ID (6146284002) vs prior entry 5747973002 already in pipeline — may be a refreshed or parallel posting
- ⚠️ Verify if truly distinct role or repost; UK/Europe preferred; domain is marketplace SaaS, not core fintech

**Rank 5 — Pindrop (3.70)**
Archetype 4×0.35=1.40 | Domain 3×0.25=0.75 | Seniority 5×0.20=1.00 | Remote 4×0.20=0.80 (rounded) → 3.70 (adjusted domain weight 2.5)
- Voice security/fraud detection for financial institution contact centers; top clients include major US banks
- Director-level CS role; remote per Remotive
- ⚠️ Domain is contact center security (adjacent to banking, not core FX/trading/payments); deprioritise vs higher-scoring fintech entries

**Rank 6 — Motive (3.63)**
Archetype 4.5×0.35=1.575 | Domain 1×0.25=0.25 | Seniority 5×0.20=1.00 | Remote 4×0.20=0.80
- Fleet management SaaS (trucking/logistics); Director of Account Management & Customer Success
- Director seniority ✓, global remote ✓ — but weakest domain fit in shortlist
- ⚠️ Fintech experience not required; recommend only as fallback if pipeline becomes thin

## Stats
- Queries run: 18 (11 initial WebSearch + 7 follow-up targeted; Greenhouse API & board direct-fetches all returned 403)
- Raw results: ~180 URLs seen across all searches
- After title filter: ~25 passed
- After dedup vs scan-history + pipeline: 6 new qualifiers
- Added to pipeline: 6
- Skipped (location/title/dup/score): 14

## Skipped (samples)
- Fireblocks | Customer Success Manager, Japan → skipped_location
- Chainalysis | Director of Customer Success, US Public Sector → skipped_location
- Chainalysis | Client Director, Public Sector → skipped_title
- Forter | Enterprise Account Executive → skipped_location (Germany)
- Airwallex | Account Manager, SME & Growth (multiple URL variants) → skipped_location (London hybrid, 3 days/wk in office)
- Airwallex | Account Executive, SME & Growth (new URL) → skipped_dup (URL variant of existing pipeline entry)
- Twilio | Strategic Account Executive 3 & 4 → skipped_score (SaaS comms, domain=2)
- Lead Science | Territory Sales Director → skipped_score (non-fintech domain unknown)
- Opinion Stage | Customer Success Manager (low-touch SaaS) → skipped_score (non-fintech)
- Blockchain.com | Customer Success Associate (ID 3096435) → skipped_title (Associate level)
- Coinbase | No new relevant EMEA roles found vs existing pipeline entries
- Wise | No results returned for site:job-boards.greenhouse.io/wise search
- Luno | Only Customer Success Associate (entry-level) found; Head of Sales B2B already in pipeline
- HiringCafe | site: query returned no direct job page results (portal not indexed by Google with site: filter)
