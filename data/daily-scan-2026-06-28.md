# Daily Scan — 2026-06-28

## Top Matches (up to 10)

| Rank | Score | Company | Role | Source | URL |
|------|-------|---------|------|--------|-----|
| 1 | 4.65 | NICE (Actimize) | Lead Customer Success Manager | Greenhouse | https://job-boards.greenhouse.io/nice/jobs/4875626101 |
| 2 | 4.05 | Horizen Labs | EMEA Business Development Manager | Greenhouse | https://boards.greenhouse.io/horizenlabs/jobs/5426324004 |
| 3 | 3.80 | AltScore | Customer Success Manager (Enterprise / EC) | Greenhouse | https://job-boards.greenhouse.io/altscore/jobs/5168737008 |
| 4 | 3.80 | Plooto | Customer Success Manager | Remotive | https://remotive.com/remote/jobs/customer-service/customer-success-manager-4387795 |

### Scoring rationale

**NICE (Actimize) — Lead Customer Success Manager | Score: 4.65**
- Archetype #3 (CSM): 4 × 0.35 = 1.40
- Domain (financial crime/AML compliance tech for banks & FIs): 5 × 0.25 = 1.25
- Seniority ("Lead" = senior IC, equiv. Director of CSM): 5 × 0.20 = 1.00
- Remote: explicitly listed "South Africa – Remote" = 5 × 0.20 = 1.00
- ★ Standout: Only new listing this scan explicitly listing South Africa as eligible remote location. NICE Actimize serves 1,000+ financial institutions with AML/fraud/compliance tech — directly overlaps with Sokhana's Bloomberg/SGX FX institutional client background. Prior NICE Actimize roles were skipped for US location; this one is SA-specific.

**Horizen Labs — EMEA Business Development Manager | Score: 4.05**
- Archetype #4 (BD): 4 × 0.35 = 1.40
- Domain (blockchain/ZK infrastructure, crypto): 5 × 0.25 = 1.25
- Seniority (Manager = senior BD): 4 × 0.20 = 0.80
- Remote: EMEA-listed, SA eligibility unconfirmed: 3 × 0.20 = 0.60
- ⚠️ Caveat: Horizen Labs (New York + Milan offices) typically recruits remote-Europe for EMEA BD. Verify whether "EMEA" encompasses sub-Saharan Africa before applying.

**AltScore — Customer Success Manager (Enterprise / EC) | Score: 3.80**
- Archetype #3 (CSM): 4 × 0.35 = 1.40
- Domain (fintech: credit infrastructure / embedded finance for FIs, LatAm + global): 4 × 0.25 = 1.00
- Seniority (Manager): 4 × 0.20 = 0.80
- Remote: global remote platform, SA eligibility unconfirmed: 3 × 0.20 = 0.60
- ⚠️ Caveat: AltScore is LatAm-origin fintech (lending/credit infra for banks). Check if EMEA/Africa candidates accepted. Distinct from prior AltScore listing 5078798008.

**Plooto — Customer Success Manager | Score: 3.80**
- Archetype #3 (CSM): 4 × 0.35 = 1.40
- Domain (B2B payments fintech, accounts payable/receivable automation): 4 × 0.25 = 1.00
- Seniority (Manager): 4 × 0.20 = 0.80
- Remote: EMEA candidates mentioned in role description, SA eligibility to verify: 3 × 0.20 = 0.60
- ⚠️ Caveat: Canadian fintech. Confirm whether EMEA hire can be based in South Africa (outside EU/UK).

---

## Stats

- Queries run: 22 (11 WebSearch + 10 Greenhouse API attempts + 1 additional)
- Greenhouse API status: All 10 endpoints returned HTTP 403 (blocked this session) — fallback via WebSearch
- Raw results surfaced: ~90 URLs across all queries
- Already in scan-history (dedup): ~74 URLs
- Genuinely new URLs: ~16
- After title filter: 9 passed
- After location/score filter (< 3.5): 5 skipped
- Added to pipeline: 4

---

## Skipped — New URLs (not qualifying)

| Company | Title | Reason |
|---------|-------|--------|
| Duetto Research | Senior Customer Success Manager, EMEA | skipped_score: hospitality/hotel tech domain (score ~3.1) |
| Bask Health | Senior Customer Success Manager | skipped_score: telehealth, off-domain (score ~2.6) |
| Salesmsg | Head of Sales (SaaS) | skipped_score: SMS/text messaging SaaS, off-domain (score ~2.8) |
| BitGo | Business Development Representative - Ecosystem | skipped_title: "Representative" = junior/entry level |
| Luno | OTC Desk Trader | skipped_title: trader role, not sales/CSM/BD |
| Human Interest | Account Executive, South (EST/CST) | skipped_location: US timezone requirement |
| Redis | Customer Success Manager | skipped_score: database infra, not fintech (score ~2.9) |
| Tide | Senior Partnerships Manager | skipped_title: "Partnerships Manager" not in positive filter |
| Interface AI | Sr Partner Sales Manager – Fintech | skipped_title: "Partner Sales Manager" not in positive filter |
| Anthropic | Manager, Customer Success | skipped_score: AI company, not fintech/capital markets |
| Remote.com | Manager, Sales Development (EMEA) | skipped_title: Sales Development Manager not in positive filter |

---

## Notes for This Scan

- **Thin results**: The pipeline already contains 400+ pending entries accumulated over 11 prior scan cycles (2026-04-11 through 2026-06-25). This scan produced only 4 new qualifying roles, which is expected as the market yield naturally decreases as the pipeline matures.
- **Greenhouse API blocked**: All 10 Greenhouse API endpoints (Fireblocks, Chainalysis, Airwallex, Coinbase, Circle, Wise, Nium, Tipalti, Luno, Gemini) returned HTTP 403. Compensated with site-specific WebSearch queries. Live API access would have yielded more granular results.
- **HiringCafe, WeWorkRemotely, Remotive**: Site-restricted searches returned mostly previously-seen listings. No new high-scoring results from these portals.
- **Priority recommendation**: With 400+ pending entries in pipeline.md, the bottleneck is evaluation — not discovery. Consider running `/career-ops pipeline` to work through the backlog before the next scan cycle.
