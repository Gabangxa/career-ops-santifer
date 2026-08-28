# Daily Scan Report — 2026-08-28

**Candidate:** Sokhana Caza | Sales Director | Johannesburg, SA | Remote-only  
**Scan run:** 2026-08-28 | **Previous scan:** 2026-08-25

---

## Summary

| Metric | Count |
|--------|-------|
| Sources queried | 7 (WeWorkRemotely, Remotive, HiringCafe, CryptoJobsList, web3.career, Greenhouse API x10) |
| Raw URLs checked | ~30 (web search results) + 12 Greenhouse (found via search) |
| Already in history | 3 (skipped_dup/skipped_location) |
| Egress-blocked (Greenhouse API) | 10 (boards-api.greenhouse.io blocked — fell back to web search) |
| Title filter: failed | 2 (Fireblocks — title unknown, egress blocked) |
| Score < 3.5 | 2 (Wise roles — location/seniority issues) |
| **New qualifying roles added** | **8** |

---

## Ranked Shortlist (score ≥ 3.5)

| # | Score | Company | Role | URL | Notes |
|---|-------|---------|------|-----|-------|
| 1 | 4.13/5 | Coinbase | International Exchange Sales Manager, Remote - Brazil | [link](https://boards.greenhouse.io/coinbase/jobs/7113176) | ⚠️ Brazil region tag — verify SA eligibility |
| 2 | 4.10/5 | Circle | Senior Director, Business Development, Americas | [link](https://boards.greenhouse.io/circle/jobs/7073975002) | ⚠️ Americas territory — verify SA remote |
| 3 | 4.00/5 | Coinbase | Senior Institutional Sales Associate, Remote - Singapore | [link](https://boards.greenhouse.io/coinbase/jobs/6821780) | ⚠️ APAC region + below Director level |
| 4 | 4.00/5 | Circle | Director, Business Development, Americas | [link](https://boards.greenhouse.io/circle/jobs/7066248002) | ⚠️ Americas territory |
| 5 | 4.00/5 | Circle | Business Development Director, Americas | [link](https://boards.greenhouse.io/circle/jobs/7500169002) | ⚠️ Americas territory; verify vs #4 |
| 6 | 3.93/5 | Circle | Senior Director, Capital Markets | [link](https://boards.greenhouse.io/circle/jobs/6284518002) | Senior Director level ✓; Americas-focused |
| 7 | 3.73/5 | Circle | Senior Manager, Business Development | [link](https://boards.greenhouse.io/circle/jobs/7517062002) | ⚠️ Manager level below Director |
| 8 | 3.53/5 | Circle | Business Development Manager, Americas | [link](https://boards.greenhouse.io/circle/jobs/6064633002) | ⚠️ Manager level; borderline fit |

---

## Scoring Breakdown

**Weights:** Archetype fit 35% | Domain relevance 25% | Seniority match 20% | Remote-friendly 20%

| Role | Archetype | Domain | Seniority | Remote | Total |
|------|-----------|--------|-----------|--------|-------|
| Coinbase — Intl Exchange Sales Mgr (Brazil) | 4.5 | 5.0 | 3.5 | 3.0 | **4.13** |
| Circle — Sr Dir, BD, Americas | 4.0 | 4.0 | 5.0 | 3.5 | **4.10** |
| Coinbase — Sr Institutional Sales Assoc (SG) | 5.0 | 5.0 | 2.0 | 3.0 | **4.00** |
| Circle — Director, BD, Americas | 4.0 | 4.0 | 4.5 | 3.5 | **4.00** |
| Circle — BD Director, Americas | 4.0 | 4.0 | 4.5 | 3.5 | **4.00** |
| Circle — Sr Director, Capital Markets | 3.5 | 4.0 | 5.0 | 3.5 | **3.93** |
| Circle — Sr Manager, BD | 3.5 | 4.0 | 3.5 | 4.0 | **3.73** |
| Circle — BD Manager, Americas | 3.5 | 4.0 | 3.0 | 3.5 | **3.53** |

---

## Skipped / Below Threshold

| URL | Company | Reason | Score |
|-----|---------|--------|-------|
| [transferwise/4710389](https://boards.greenhouse.io/transferwise/jobs/4710389) | Wise | NYC office-based; Senior AM not Director level | 2.93 |
| [transferwise/3823806](https://boards.greenhouse.io/transferwise/jobs/3823806) | Wise | Singapore-based; APAC BD not remote for SA | 3.40 |
| [fireblocks/4453473006](https://job-boards.greenhouse.io/fireblocks/jobs/4453473006) | Fireblocks | Title unknown — egress blocked | — |
| [fireblocks/4574080006](https://job-boards.greenhouse.io/fireblocks/jobs/4574080006) | Fireblocks | Title unknown — egress blocked | — |
| [chainalysis/6854572002](https://boards.greenhouse.io/chainalysis/jobs/6854572002) | Chainalysis | Already in history (2026-05-31, skipped_title) | — |
| [chainalysis/5292196002](https://boards.greenhouse.io/chainalysis/jobs/5292196002) | Chainalysis | Already in history (2026-06-10, skipped_location) | — |
| [coinbase/7235232](https://boards.greenhouse.io/coinbase/jobs/7235232) | Coinbase | Already in history (2026-06-10, skipped_location) | — |

---

## Infrastructure Notes

- **Greenhouse API (boards-api.greenhouse.io):** Egress-blocked by network proxy — all 10 company API fetches failed. Fell back to web search for job discovery.
- **job-boards.greenhouse.io:** Also egress-blocked — two Fireblocks job pages unverifiable.
- **Next scan:** Recommend retrying Fireblocks job IDs 4453473006 and 4574080006 from a non-restricted environment.
- **Scan history:** 1,140 URLs total after today's additions (+12 new entries).

---

## Action Items

1. **Priority evaluate:** Coinbase International Exchange Sales Manager (Brazil) — strongest domain + archetype fit; check if Brazil region requires geographic presence
2. **Evaluate batch:** 3× Circle Director-level BD roles (7073975002, 7066248002, 7500169002) — confirm which if any are open to SA remote
3. **Verify Fireblocks:** Job IDs 4453473006, 4574080006 — fetch titles when egress is available; likely high-value given Fireblocks' institutional sales focus
4. **Skip:** Wise roles (location-bound), Coinbase Singapore Senior Associate (seniority mismatch)
