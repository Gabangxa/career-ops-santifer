# Daily Scan — 2026-11-01

> **Network note:** `boards-api.greenhouse.io`, `boards.greenhouse.io`, `job-boards.greenhouse.io`, `remotive.com`, and `weworkremotely.com` are blocked for direct WebFetch in this cloud session. All Greenhouse API pulls failed. Roles were identified via WebSearch snippets and Google index data — titles and remote policies are inferred from search results, not live page reads. Mark each for Playwright verification before applying.

## Top Matches (up to 10)

| Rank | Score | Company | Role | Source | URL |
|------|-------|---------|------|--------|-----|
| 1 | 4.40 | Pico | Sales Director | Greenhouse | https://job-boards.greenhouse.io/picoquantitativetrading/jobs/4410757006 |
| 2 | 4.25 | Customer.io | Senior Director, Sales | Remotive | https://remotive.com/remote/jobs/sales/senior-director-sales-5210703 |
| 3 | 4.20 | Alpaca | Customer Success Manager, Europe | Greenhouse | https://boards.greenhouse.io/alpaca/jobs/5505552004 |
| 4 | 4.15 | Episode Six | Sales Director | Greenhouse (LinkedIn board) | https://job-boards.greenhouse.io/episodesixlinkedin/jobs/5425812004 |
| 5 | 3.95 | Veriff | Senior Account Executive, EMEA | Remotive | https://remotive.com/remote/jobs/sales/senior-account-executive-6341367 |

### Scoring detail

**1. Pico — Sales Director (4.40)**
Pico provides capital markets data services and managed infrastructure to global banks and electronic trading firms. Role reports to Head of AMRS Sales; sells to banks and electronic trading firms. Salary $175k–$200k USD. **⚠️ NYC hybrid** — weekly in-office requirement; verify if SA remote is possible given Pico's Dublin remote-considered precedent. Strong archetype + domain match.
- Archetype fit (×0.35): 5 — Sales Director, target #1/#2
- Domain relevance (×0.25): 5 — capital markets / electronic trading
- Seniority match (×0.20): 5 — Director
- Remote-friendly (×0.20): 2 — NYC hybrid

**2. Customer.io — Senior Director, Sales (4.25)**
Fully remote, $350k OTE. Runs an EMEA sales team of AEs. **⚠️ Domain caveat:** Customer.io is marketing automation SaaS, not fintech. Strong seniority and comp, and distinct from the Director of Sales entry (`customerio/jobs/7904660`) already in pipeline.
- Archetype fit (×0.35): 5 — Senior Director of Sales
- Domain relevance (×0.25): 2 — marketing SaaS, not fintech
- Seniority match (×0.20): 5 — Senior Director
- Remote-friendly (×0.20): 5 — fully remote

**3. Alpaca — Customer Success Manager, Europe (4.20)**
Alpaca is a self-clearing brokerage infrastructure for stocks, ETFs, options, crypto, FX. Europe-specific CSM role, EMEA remote. **⚠️ Verify** not a duplicate of CSM-EMEA (5670974004) already in pipeline — new Greenhouse ID suggests different territory or territory split.
- Archetype fit (×0.35): 4 — CSM, archetype #3
- Domain relevance (×0.25): 4 — trading API fintech (FX + stocks + crypto)
- Seniority match (×0.20): 4 — Manager level
- Remote-friendly (×0.20): 5 — globally remote / EMEA

**4. Episode Six — Sales Director (4.15)**
Episode Six makes payments infrastructure sold to banks and card issuers. Sales Director for US team. **⚠️ US-focused** — verify if SA global remote is eligible. Distinct from Senior Business Analyst (5799337004) already in pipeline.
- Archetype fit (×0.35): 5 — Sales Director
- Domain relevance (×0.25): 4 — payments fintech / banking
- Seniority match (×0.20): 5 — Director
- Remote-friendly (×0.20): 2 — US-based team, remote unconfirmed for SA

**5. Veriff — Senior Account Executive, EMEA (3.95)**
Identity verification SaaS; clients include fintechs, banks, and crypto exchanges. Posted Oct 22, 2026 on Remotive. EMEA remote confirmed. Selling into financial services clients with 5+ yrs enterprise SaaS sales required.
- Archetype fit (×0.35): 4 — Senior AE / institutional sales archetype
- Domain relevance (×0.25): 3 — sells TO fintech/banking, not core fintech platform
- Seniority match (×0.20): 4 — Senior
- Remote-friendly (×0.20): 5 — EMEA remote confirmed

---

## Stats
- Queries run: 11 WebSearch (site: filters partially bypassed by Google) + 10 Greenhouse API calls (all blocked by network policy)
- Raw results: ~42 unique URLs extracted from search result snippets
- After title filter: ~22 passed positive title filter (no negatives matched)
- After dedup: 5 new (not already in scan-history.tsv or pipeline.md)
- Added to pipeline: 5

## Blocked infrastructure (⚠️ action needed)
The following domains are outside the cloud session's allowed network and must be added to network settings for full scan coverage:
- `boards-api.greenhouse.io` — Greenhouse API (10 company feeds failed)
- `boards.greenhouse.io` — Greenhouse job pages
- `job-boards.greenhouse.io` — Greenhouse job pages
- `remotive.com` — direct page verification
- `weworkremotely.com` — direct page verification

## Unverified new Greenhouse IDs (seen but title/remote unconfirmed)
These appeared in search results with new IDs not in pipeline — added to scan-history as seen, need Playwright verification once Greenhouse is unblocked:
- `https://job-boards.greenhouse.io/blockchain/jobs/8035556` — Blockchain.com
- `https://job-boards.greenhouse.io/blockchain/jobs/8046206` — Blockchain.com
- `https://job-boards.greenhouse.io/bitgo/jobs/8584877002` — BitGo
- `https://job-boards.greenhouse.io/bitgo/jobs/8350286002` — BitGo

## Skipped (title mismatch / score < 3.5 / dup)
| Status | Company | Title |
|--------|---------|-------|
| skipped_title (junior) | Figure Markets | Customer Success Associate |
| skipped_title (not fintech) | Gurobi Optimization | Account Director, EMEA |
| skipped_title (NYC on-site) | Numerix | Senior Customer Success Manager |
| skipped_title (not fintech) | Dropbox | Scaled Customer Success Manager |
| skipped_title (score 3.40) | CryptoTrader.Tax | Customer Success Specialist |
| skipped_title (score 3.25) | Alloy | Account Executive, Banking & Credit Unions |
| skipped_title (company unverified) | Fin | Senior Customer Success Manager |
| skipped_title (company unverified) | Fin | Principal Customer Success Manager |
| skipped_dup | Fireblocks | Customer Success Manager, Tres (alt ID 4648310006) |
| skipped_dup | Customer.io | Director of Sales (Remotive mirror of pipeline entry) |
| skipped_title (US-only) | Copyright 2026 / FS co. | Director of Sales |
