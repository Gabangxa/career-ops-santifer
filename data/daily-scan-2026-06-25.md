# Daily Scan — 2026-06-25

**Candidate:** Sokhana Caza | Johannesburg, SA | Remote-only | ZAR 1.8M–2.3M target

---

## Summary

| Metric | Value |
|--------|-------|
| Queries run | 21 |
| Raw results surfaced | ~50 |
| Passed title filter | ~15 |
| Already in scan history (dedup) | 12 |
| New qualifying roles (≥ 3.5) | 3 |
| Added to pipeline.md | 3 |
| Greenhouse APIs attempted | 10 |
| Greenhouse APIs blocked (403) | 10 |
| WebFetch blocked (403) | all |

**Verification note:** Greenhouse API endpoints and direct job board WebFetch calls all returned HTTP 403 via the outbound proxy. Scores are estimated from search snippet descriptions and company knowledge rather than full JD text. Listings marked `unconfirmed (batch mode)`.

---

## Shortlist — New Roles Added to Pipeline

### Rank 1 | Score 4.40 | Kraken | Sr. Sales Manager EMEA — Kraken Institutional

- **URL:** https://web3.career/sr-sales-manager-emea-kraken-institutional-kraken/147845
- **Portal:** web3.career
- **Archetype fit (35%):** Institutional sales at a top-5 crypto exchange institutional desk — near-perfect match for Bloomberg LP background. Score: 4.5 → weighted 1.58
- **Domain relevance (25%):** Crypto/digital assets institutional trading — directly adjacent to SGX FX and fixed income. Score: 4.5 → weighted 1.13
- **Seniority match (20%):** Sr. Sales Manager = Director-adjacent; requires 7+ yrs institutional sales in trading/crypto. Score: 4.0 → weighted 0.80
- **Remote-friendly (20%):** Listed as remote EMEA; ⚠️ "located in Europe or UK" language — SA/Africa eligibility unconfirmed. Score: 4.0 → weighted 0.80 (conditional)
- **Comp:** $72k–$110k USD base (~ZAR 1.37M–2.09M); upper end approaches walk-away floor
- **Action:** Verify SA-Africa eligibility explicitly before applying. If remote EMEA includes Africa, this is a strong apply.

---

### Rank 2 | Score 4.20 | Banyan Software | VP of Sales

- **URL:** https://remotive.com/remote/jobs/sales/vice-president-of-sales-4728965
- **Portal:** Remotive
- **Archetype fit (35%):** VP-level sales leadership in vertical market SaaS; Banyan acquires fintech/banking/financial software companies — relevant to Sokhana's financial services background. Score: 4.0 → weighted 1.40
- **Domain relevance (25%):** Financial software vertical (banking tech, treasury, payments) — indirect but real overlap with institutional finance. Score: 4.0 → weighted 1.00
- **Seniority match (20%):** VP of Sales — appropriate seniority step from current Director role; requires 8+ yrs progressive sales leadership in SaaS/fintech/banking tech. Score: 5.0 → weighted 1.00
- **Remote-friendly (20%):** Listed as fully remote. Score: 4.5 → weighted 0.90 (conditional on SA eligibility)
- **Comp:** Not specified in listing
- **Action:** Verify SA remote eligibility. Financial software acquirer is niche but aligns with fintech institutional knowledge.

---

### Rank 3 | Score 3.60 | FIS Capital Markets | Account Manager II

- **URL:** https://weworkremotely.com/remote-jobs/fis-capital-markets-account-manager-ii
- **Portal:** WeWorkRemotely
- **Archetype fit (35%):** Enterprise account management for FIS capital markets platform suite — solid domain overlap with Bloomberg and SGX backgrounds. Score: 3.5 → weighted 1.23
- **Domain relevance (25%):** Capital markets technology (NYSE: FIS is a tier-1 fintech infrastructure provider). Score: 4.5 → weighted 1.13
- **Seniority match (20%):** "Account Manager II" is a step below current Head of Sales/Director level — seniority mismatch. Score: 2.5 → weighted 0.50
- **Remote-friendly (20%):** WWR listing; ⚠️ may be US-focused. Score: 3.7 → weighted 0.74 (conditional)
- **Comp:** Not specified
- **Action:** ⚠️ Borderline — seniority is below target level. Only pursue if a strategic move into a known capital markets platform name is desired. Verify SA eligibility and whether a senior variant exists.

---

## Skipped — Title Filter (samples)

| URL | Company | Title | Reason |
|-----|---------|-------|--------|
| https://remotive.com/remote/jobs/business-development/svp-national-financial-business-development-4964804 | Loomis Armored | SVP National Financial Business Development | Physical armored transport — not financial markets; domain mismatch |
| https://remotive.com/remote/jobs/sales/account-executive-4986482 | Sawdey Solution Services | Account Executive | Defense/government sector; not relevant domain |
| https://weworkremotely.com/remote-jobs/tourcc-vp-customer-success-account-management-saas | TourCC | VP - Customer Success & Account Management | Tourism SaaS; outside target domain |

## Skipped — Duplicate

| URL | Company | Title | Reason |
|-----|---------|-------|--------|
| https://remotive.com/remote/jobs/sales/account-executive-5000915 | Visier Solutions Inc. | Account Executive | Already in scan history |

---

## Blocked Sources

| Source | Status | Note |
|--------|--------|------|
| Greenhouse API (10 companies) | HTTP 403 | All Greenhouse board API endpoints blocked by outbound proxy |
| Fireblocks, Chainalysis, Airwallex, Coinbase, Circle, Wise, Nium, Tipalti, Luno, Gemini | 403 | WebSearch fallback used; results already in scan history |
| WeWorkRemotely (direct fetch) | HTTP 403 | Title/detail scraped from search snippets only |
| Remotive (direct fetch) | HTTP 403 | Title/detail scraped from search snippets only |
| web3.career (direct fetch) | HTTP 403 | Title/detail scraped from search snippets only |

---

## Next Actions

1. **Kraken Sr. Sales Manager EMEA** — highest priority; verify whether remote EMEA explicitly includes Africa/SA before proceeding
2. **Banyan Software VP of Sales** — verify SA remote eligibility; if confirmed, strong candidate
3. **FIS Capital Markets Account Manager II** — lower priority; evaluate whether seniority trade-off is acceptable

Run `/career-ops evaluate <URL>` on any role to generate a full evaluation report and tailored CV.

---

*Scan completed 2026-06-25 | career-ops-santifer automated routine*
