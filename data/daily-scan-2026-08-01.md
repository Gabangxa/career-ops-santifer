# Daily Job Scan — 2026-08-01

## Summary

| Metric | Value |
|--------|-------|
| Scan date | 2026-08-01 |
| Portals covered | WeWorkRemotely, Remotive, Greenhouse (HTML fallback), Lever, Ashby, Workable, Web3.career, CryptoJobsList |
| Greenhouse API status | ⚠️ 403 Blocked by proxy for all 10 tracked companies — WebSearch fallback used |
| Total URLs evaluated | ~25 |
| Already in pipeline/history | ~16 |
| New qualified roles (≥3.5) | **9** |
| Pushed to pipeline | **9** |

---

## Ranked Shortlist

| # | Company | Role | Score | URL | Notes |
|---|---------|------|-------|-----|-------|
| 1 | Kraken | Sales Director, Distribution — EMEA | **4.80** | [Lever](https://jobs.lever.co/kraken123/a5438fe6-cc13-447b-a969-a3e69d86f8a7) | Top-5 crypto exchange; Sales Director exact match; Kraken remote-first 70+ countries; ⚠️ verify SA eligibility vs EMEA preference |
| 2 | Backbase | Sales Director, North/West Africa | **4.70** | [Greenhouse](https://boards.greenhouse.io/workatbackbase/jobs/6424316) | Digital banking platform; Africa territory perfectly aligns with Sokhana's Bloomberg/SGX FX Nigeria/Ghana/SA coverage; Director level ✓ |
| 3 | BVNK | Director of Account Management — PSP & Fintech | **4.63** | [Greenhouse EU](https://job-boards.eu.greenhouse.io/bvnk/jobs/4821225101) | Visa-backed stablecoin/cross-border payments infra; Director AM for PSP & Fintech clients; strong FX/payments domain match |
| 4 | RedotPay | Country Manager, Payment | **4.50** | [Remotive](https://remotive.com/remote/jobs/business-development/country-manager-payment-5116081) | Web3/crypto payment solutions; Country Manager = Director-level ownership; fully remote ✓ |
| 5 | The Tie | Director of Business Development, EMEA (Crypto) | **4.40** | [Workable](https://apply.workable.com/thetie/j/507ACA326B/) | Crypto data/analytics (Bloomberg equivalent for digital assets); Director BD EMEA; 500+ hedge fund/asset manager/bank client base aligns with Bloomberg background |
| 6 | Backbase | Senior Account Executive, Africa | **4.30** | [Greenhouse](https://job-boards.greenhouse.io/workatbackbase/jobs/7480593) | Same company/territory as #2 but AE level; Africa expansion pipeline role; ⚠️ seniority slightly below Director target |
| 7 | Morpho | Strategic Account Manager | **4.23** | [Remotive](https://remotive.com/remote/jobs/account-management/strategic-account-manager-4899010) | DeFi crypto lending protocol; SAM role managing CFO/CRO/Heads of Crypto; fully remote ✓; ⚠️ AM level below Director target |
| 8 | dLocal | VP, Operations — Africa | **4.08** | [Lever](https://jobs.lever.co/dlocal/d17adba1-1a13-49b3-a77e-1f471a8cf800) | EM payments (Africa, LatAm, SEA); VP level ✓; Africa territory ownership; ⚠️ Operations title — verify if commercial/partnerships scope matches Sokhana's skills; location: Cape Town/Lagos/Nairobi preferred |
| 9 | Ozow | Enterprise Solutions Lead | **3.80** | [Greenhouse](https://job-boards.greenhouse.io/ozow/jobs/7800988003) | SA fintech payment rails; Enterprise Solutions Lead (AE/BD hybrid); ⚠️ likely Johannesburg office — verify remote eligibility; 8+ yrs fintech required |

---

## Scoring Rubric

| Dimension | Weight | What it measures |
|-----------|--------|-----------------|
| Archetype fit | 35% | Sales Director / BD / AE / AM / CSM match |
| Domain relevance | 25% | Fintech / Crypto / Payments / FX / Digital Assets |
| Seniority match | 20% | Director / VP / Country Manager target |
| Remote-friendly | 20% | Explicitly remote or EMEA-remote eligible |

---

## Skipped / Deduped

| URL | Reason |
|-----|--------|
| `jobs.lever.co/zerotier/...` | Already in history (skipped_location 2026-07-27) |
| `job-boards.greenhouse.io/bitmex/...` | BitMEX Senior Sales CIS — Russian fluency required, wrong territory |
| `weworkremotely.com/...customer-io...` | Customer.io CSM — many Customer.io entries already in pipeline |
| `apply.workable.com/gomining/...` | GoMining BDM — too junior |
| `apply.workable.com/emerchantpay/...` | Amsterdam in-office |
| `jobs.ashbyhq.com/polygon-labs/...` | APAC focus, not EMEA |
| `jobs.ashbyhq.com/primer.io/...` | BDM Senior, not Director level |
| `jobs.lever.co/yuno/...` | China focus |
| `jobs.lever.co/valiantys/...` | Atlassian services, not fintech |
| `jobs.ashbyhq.com/iverify/...` | Cybersecurity, not fintech |

---

## Notes for Next Scan

- Greenhouse API (boards-api.greenhouse.io) returning 403 via proxy — all 10 tracked companies missed direct API access. Consider configuring proxy exception or using HTML board fallback via Playwright.
- Backbase has 2 Africa-focused roles open simultaneously — high-signal company to watch.
- BVNK is a new entrant to the scan; add to `tracked_companies` in portals.yml.
- The Tie Director BD EMEA is a step up from their Institutional Sales AE role already in pipeline (Added 2026-07-13) — different level, worth separate evaluation.
