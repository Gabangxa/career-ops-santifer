# Daily Scan — 2026-07-28

## Top Matches (4 qualify at ≥ 3.5)

| Rank | Score | Company | Role | Source | URL |
|------|-------|---------|------|--------|-----|
| 1 | 4.35 | Mesh | Director of Sales (Europe Remote) | Greenhouse | https://job-boards.greenhouse.io/mesh/jobs/5370177008 |
| 2 | 4.20 | Ebury | Key Account Director (Düsseldorf) ⚠️ office | Greenhouse EU | https://job-boards.eu.greenhouse.io/ebury/jobs/4555918101 |
| 3 | 3.75 | AlphaSense | Senior Director, Account Management, Consulting | Greenhouse | https://job-boards.greenhouse.io/alphasense/jobs/8605590002 |
| 4 | 3.65 | Convera | Business Development Manager, FX Sales (est.) ⚠️ London | Greenhouse EU | https://job-boards.eu.greenhouse.io/convera/jobs/4691579101 |

### Scoring notes

**Mesh — Director of Sales (Europe Remote) — 4.35**
- Archetype #1/#2 (Sales Director): 5 × 0.35 = 1.75
- Domain (crypto/fintech payment connectivity, serves exchanges/wallets/banks): 4 × 0.25 = 1.00
- Seniority (Director): 5 × 0.20 = 1.00
- Remote ("Europe Remote" — SA eligibility unconfirmed): 3 × 0.20 = 0.60
- New listing; distinct from prior Mesh Director of Sales IDs (5030671008, 5030665008, etc.) in pipeline.
- ⚠️ "Europe Remote" may restrict to EU candidates — confirm SA-based hiring before applying.

**Ebury — Key Account Director, Düsseldorf — 4.20**
- Archetype #1/#2 (Account Director, sales leadership): 5 × 0.35 = 1.75
- Domain (FX / cross-border payments — PERFECT match to Bloomberg/SGX FX background): 5 × 0.25 = 1.25
- Seniority (Director): 5 × 0.20 = 1.00
- Remote (Düsseldorf office-based, Germany): 1 × 0.20 = 0.20
- ⚠️ Office-based role in Germany. Strong domain signal for Ebury — watch for any remote or EMEA-remote Ebury listings.

**AlphaSense — Senior Director, Account Management, Consulting — 3.75**
- Archetype #1 (Account Management Director): 4 × 0.35 = 1.40
- Domain (market intelligence — Consulting vertical, not Financial Services): 3 × 0.25 = 0.75
- Seniority (Senior Director): 5 × 0.20 = 1.00
- Remote (London-preferred EMEA, SA unconfirmed): 3 × 0.20 = 0.60
- ⚠️ Consulting segment differs from AlphaSense's Financial Services vertical already in pipeline (which scores higher).

**Convera — Business Development Manager, FX Sales — 3.65 (est.)**
- Archetype #4 (Business Development): 4 × 0.35 = 1.40
- Domain (largest non-bank B2B cross-border FX/payments company — PERFECT): 5 × 0.25 = 1.25
- Seniority (Manager): 4 × 0.20 = 0.80
- Remote (London office-based): 1 × 0.20 = 0.20
- ⚠️ Title estimated from web search; office-based in London. Convera also has multiple unverified EU Greenhouse listings (4742268101, 4766005101, 4751927101, 4802453101) — titles and remote status TBC via Playwright.

---

## Scan Notes

**Greenhouse API access:** All 10 Greenhouse API endpoints returned HTTP 403 (blocked in this environment). Fell back to web search discovery for Greenhouse listings.

**Key discovery: Convera** — not previously in portals.yml. Largest non-bank B2B cross-border FX payments company (formerly Western Union Business Solutions). Active EMEA hiring with multiple EU Greenhouse listings. Consider adding to portals.yml for future scans. Most current roles appear London/EU-office based.

**Key discovery: Ebury** — FX, trade finance, and international payments for SMEs. Already in scan history (several listings), but the Düsseldorf Key Account Director is a new find. Ebury is one of the strongest domain matches for Sokhana's profile — monitor for remote/EMEA-remote variants.

---

## Stats
- Queries run: 19 web searches + 10 Greenhouse API attempts (all 403)
- Raw URLs identified: ~55
- After dedup (not in scan-history.tsv): 11 new URLs
- After title filter: 9 pass
- After score threshold (≥ 3.5): 4 qualify
- Added to pipeline: 9 (4 scored + 5 Convera/Ebury unverified titles needing Playwright check)

## Skipped (title mismatch / below threshold / already seen)

| Company | Title | Reason |
|---------|-------|--------|
| BVNK | Sales Director - Banking | skipped_dup (in history 2026-07-13, skipped_location) |
| BVNK | Sales Director - APAC | skipped_dup (in history 2026-07-06, skipped_location) |
| BVNK | [EU listing] | skipped_dup (in history 2026-06-16, skipped_title) |
| Fireblocks | Senior Sales Executive | skipped_dup (in history 2026-07-01, skipped_title) |
| Unlimit | BDM Crypto EMEA | skipped_dup (in history 2026-06-07, skipped_score) |
| Ebury | (EU listing 4383829101) | skipped_dup (in history 2026-07-27, skipped_title) |
| AlphaSense | Customer Success Manager, Corporate | skipped_score (2.95 < 3.5) |
| AlphaSense | Account Manager, Corporate | skipped_score (2.95 < 3.5) |
| BTIG | Various new IDs | skipped_title (internship/tech/IB analyst roles) |
| Twilio (WWR) | New Business Account Executive | skipped_title (not in positive list context) |
| Jumio (WWR) | Account Executive - LATAM | skipped_location |
| Visier | Account Executive | skipped_title (people analytics, not fintech) |
| Fireblocks | Sales Engineer, EMEA | skipped_title ("Sales Engineer" not in positive filter) |
