# Daily Scan — 2026-07-25

**Candidate:** Sokhana Caza  
**Scan date:** 2026-07-25  
**Portals queried:** HiringCafe, WeWorkRemotely, Remotive, Greenhouse boards (BitGo, Fireblocks, Chainalysis, Airwallex, Coinbase, Circle, Wise, Nium, Tipalti, Luno, Gemini), CryptoJobsList, Web3.career, CryptocurrencyJobs  
**Dedup baseline:** 894 URLs in scan-history.tsv (through 2026-07-22)

---

## Infrastructure Notes

Greenhouse API (`boards-api.greenhouse.io/v1/boards/*/jobs`) returned **403 Forbidden** for all 10 tracked companies. Greenhouse board pages, WeWorkRemotely listings, web3.career, and cryptojobslist.com also blocked at the proxy level. All discovery performed via WebSearch (snippet-level data). Coverage is reduced — structured job feeds unavailable this run.

---

## Stats

| Metric | Count |
|--------|-------|
| Search queries run | 21 |
| URLs evaluated | ~40 |
| Already in history (skipped_dup) | ~37 |
| New URLs found | 3 |
| Passed title filter & score ≥ 3.5 | 1 |
| Added to pipeline | 1 |

---

## Qualifying Roles (score ≥ 3.5)

### 1. BitGo — Senior Customer Success Manager, Fintech
**Score: 4.03/5**  
**URL:** https://job-boards.greenhouse.io/bitgo/jobs/8555322002  
**Portal:** Greenhouse — BitGo  
**Dimensions:**
- Archetype fit (35%): 4.0 — Senior CSM is a named archetype; strategic account ownership at institutional crypto custodian
- Domain relevance (25%): 4.5 — BitGo serves institutional trading firms, hedge funds, exchanges; strong overlap with Bloomberg/SGX institutional background
- Seniority match (20%): 4.0 — Senior-level role appropriate for Director-track candidate
- Remote-friendly (20%): 3.5 — BitGo is crypto-native distributed team; unverified for SA specifically

**Notes:** BitGo is the largest independent digital asset custodian, serving 1,500+ institutional clients. CSM role likely owns post-sales relationship with fintech clients — strong domain fit. Verify SA remote eligibility and compensation band before full evaluation.

---

## Skipped — Below Score Threshold

| URL | Company | Title | Score | Reason |
|-----|---------|-------|-------|--------|
| https://weworkremotely.com/remote-jobs/twilio-new-business-account-executive-1 | Twilio | New Business Account Executive | 3.45/5 | Communications/CPaaS — not fintech domain; below 3.5 threshold |
| https://remotive.com/remote/jobs/sales/commercial-account-executive-5287801 | Archera | Commercial Account Executive | 3.15/5 | FinOps/cloud cost — domain not relevant; below threshold |

---

## Already in Pipeline / History

All other search results matched URLs already present in scan-history.tsv (through 2026-07-22), including:
- Bloomberg ETS eFX roles (IDs 20315, 16768, 13802, 16372) — already in pipeline
- Fireblocks EMEA roles (IDs 4690576006, 4599435006, 4558518006) — already in pipeline
- Partnerverse Sales Director Web3 AI — already in pipeline
- Fordefi Sales Executive EMEA — already in pipeline
- Cryptio Account Executive — already in pipeline
- Jumio Account Executive EMEA — already in pipeline
- Chainalysis, Luno, Gemini — no new roles surfaced in search results
- Ripple, Coinbase, Circle — previously scanned roles only

---

## Pipeline Addition

```
- [ ] https://job-boards.greenhouse.io/bitgo/jobs/8555322002 | BitGo | Senior Customer Success Manager, Fintech [4.03/5 — institutional crypto custodian; Senior CSM archetype match; strong domain fit with FX/institutional background; ⚠️ verify SA remote eligibility and title via Playwright — Greenhouse API blocked this run]
```
