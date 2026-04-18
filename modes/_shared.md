# Shared Context -- career-ops

<!-- ============================================================
     HOW TO CUSTOMIZE THIS FILE
     ============================================================
     This file contains the shared context for all career-ops modes.
     Before using career-ops, you MUST:
     1. Fill in config/profile.yml with your personal data
     2. Create your cv.md in the project root
     3. (Optional) Create article-digest.md with your proof points
     4. Customize the sections below marked with [CUSTOMIZE]
     ============================================================ -->

## Sources of Truth (ALWAYS read before evaluating)

| File | Path | When |
|------|------|------|
| cv.md | `cv.md` (project root) | ALWAYS |
| article-digest.md | `article-digest.md` (if exists) | ALWAYS (detailed proof points) |
| profile.yml | `config/profile.yml` | ALWAYS (candidate identity and targets) |

**RULE: NEVER hardcode metrics from proof points.** Read them from cv.md + article-digest.md at evaluation time.
**RULE: For article/project metrics, article-digest.md takes precedence over cv.md** (cv.md may have older numbers).

---

## North Star -- Target Roles

The skill applies with EQUAL rigor to ALL target roles. None is primary or secondary -- any is a success if comp and growth are right:

| Archetype | Thematic axes | What they buy |
|-----------|---------------|---------------|
| **Institutional Sales / Electronic Trading Sales** | FX, fixed income, equities, platform sales, pipeline ownership | Someone who closes enterprise deals in financial markets |
| **Sales Director / Head of Sales** | Team leadership, revenue ownership, strategic accounts | Someone who builds and runs a revenue function |
| **Customer Success / Account Management** | Retention, expansion, adoption, renewal | Someone who grows revenue from existing accounts |
| **Business Development** | New markets, partnerships, prospecting, outbound | Someone who opens new revenue streams |
| **Trading Support / Operations** | Platform support, onboarding, FIX/SWIFT, client enablement | Someone who keeps institutional clients running smoothly |
| **Project / Program Manager** | Implementation, delivery, cross-functional coordination | Someone who lands complex client projects on time |

### Adaptive Framing by Archetype

> **Concrete metrics: read from `cv.md` at evaluation time. NEVER hardcode numbers here.**

| If the role is... | Emphasize about the candidate... | Key proof points |
|-------------------|----------------------------------|-----------------|
| Institutional Sales / Electronic Trading | Full sales cycle ownership, FX/equities/fixed income expertise, African market coverage | 20% adoption increase, 32% trading revenue increase (Bloomberg) |
| Sales Director / Head of Sales | Revenue ownership, pipeline management, cross-functional collaboration | Current Sales Director at SGX FX; progression from support → sales director |
| Customer Success / Account Management | Retention, renewal, product adoption, escalation handling | 13% revenue increase at SGX FX; key account management at Bloomberg |
| Business Development | Prospecting, new account identification, onboarding | Full sales life cycle at SGX FX; Southern Africa, Nigeria, Ghana coverage |
| Trading Support / Operations | FXGO, EMSX, FIX/SWIFT, platform troubleshooting, client onboarding | Bloomberg Electronic Trading Support; FXGO FAQ authorship |
| Project / Program Manager | Client requirements scoping, implementation coordination, stakeholder management | Cross-functional delivery at SGX FX and Bloomberg |

### Exit Narrative (use in ALL framings)

Use the candidate's exit story from `config/profile.yml` to frame ALL content:
- **In PDF Summaries:** Bridge from past to future -- "Now bringing the same [skill] to [JD domain]."
- **In STAR stories:** Reference proof points from cv.md (13% revenue, 20% adoption, 32% trading revenue)
- **When the JD asks for "ownership", "hunter", "client-facing", "relationship-driven":** This is the #1 differentiator. Increase match weight.
- **African market coverage** (South Africa, Nigeria, Ghana) is a rare differentiator -- lead with it for any EMEA or Africa-focused roles.

### Cross-cutting Advantage

Frame profile as **"Rare combination of deep product knowledge and institutional sales execution"**:
- For Sales roles: "understands the technology well enough to demo it, close it, and retain the client"
- For CSM roles: "bridges client needs directly to product teams — former support background means she speaks both languages"
- For Trading Support: "has lived both sides — support desk and sales floor — understands what clients actually need"
- For BD roles: "knows the competitive landscape from Bloomberg and can identify gaps competitors leave"

The Bloomberg → SGX FX career arc is a credibility signal: she was trusted with progressively larger accounts and eventually full sales ownership.

### Portfolio as Proof Point (use in high-value applications)

<!-- [CUSTOMIZE] If you have a live demo, dashboard, or public project, configure it here.
     Example:
     dashboard:
       url: "https://yoursite.dev/demo"
       password: "demo-2026"
       when_to_share: "LLMOps, AI Platform, observability roles"
     Read from config/profile.yml → narrative.proof_points and narrative.dashboard -->

If the candidate has a live demo/dashboard (check profile.yml), offer access in applications for relevant roles.

### Comp Intelligence

**Candidate target:** ZAR 1,800,000 – 2,300,000 per annum (walk-away: ZAR 1,800,000)

**General guidance:**
- Use WebSearch for current market data (Glassdoor, LinkedIn Salary, PayScale, eFinancialCareers)
- For remote roles paying in USD/GBP/EUR: convert to ZAR at current rate and flag if materially above/below target
- Geographic arbitrage applies: a USD 80K remote role = ~ZAR 1.5M at current rates (flag as below target)
- USD 100K+ remote roles typically land above ZAR 1.8M — flag as strong comp match
- For SA-based roles, ZAR 1.8M–2.3M is Director/VP level at a major bank or large fintech
- Contractor rates are typically 30-50% higher than permanent base to account for benefits

### Negotiation Scripts

<!-- [CUSTOMIZE] Adapt these to your situation -->

**Salary expectations (general framework):**
> "Based on market data for this role, I'm targeting [RANGE from profile.yml]. I'm flexible on structure -- what matters is the total package and the opportunity."

**Geographic discount pushback:**
> "The roles I'm competitive for are output-based, not location-based. My track record doesn't change based on postal code."

**When offered below target:**
> "I'm comparing with opportunities in the [higher range]. I'm drawn to [company] because of [reason]. Can we explore [target]?"

### Location Policy

<!-- [CUSTOMIZE] Adapt to your situation. Read from config/profile.yml → location -->

**In forms:**
- Binary "can you be on-site?" questions: follow your actual availability from profile.yml
- In free-text fields: specify your timezone overlap and availability

**In evaluations (scoring):**
- Remote dimension for hybrid outside your country: score **3.0** (not 1.0)
- Only score 1.0 if JD explicitly says "must be on-site 4-5 days/week, no exceptions"

### Time-to-offer priority
- Working demo + metrics > perfection
- Apply sooner > learn more
- 80/20 approach, timebox everything

---

## Global Rules

### NEVER

1. Invent experience or metrics
2. Modify cv.md or portfolio files
3. Submit applications on behalf of the candidate
4. Share phone number in generated messages
5. Recommend comp below market rate
6. Generate a PDF without reading the JD first
7. Use corporate-speak
8. Ignore the tracker (every evaluated offer gets registered)

### ALWAYS

0. **Cover letter:** If the form has an option to attach or write a cover letter, ALWAYS include one. Generate PDF with the same visual design as the CV. Content: JD quotes mapped to proof points, links to relevant case studies. 1 page max.
1. Read cv.md and article-digest.md (if exists) before evaluating any offer
1b. **First evaluation of each session:** Run `node cv-sync-check.mjs` with Bash. If it reports warnings, notify the candidate before continuing
2. Detect the role archetype and adapt framing
3. Cite exact lines from CV when matching
4. Use WebSearch for comp and company data
5. Register in tracker after evaluating
6. Generate content in the language of the JD (EN default)
7. Be direct and actionable -- no fluff
8. When generating English text (PDF summaries, bullets, LinkedIn messages, STAR stories): native tech English, not translated. Short sentences, action verbs, no unnecessary passive voice.
8b. **Case study URLs in PDF Professional Summary:** If the PDF mentions case studies or demos, URLs MUST appear in the first paragraph (Professional Summary). The recruiter may only read the summary. All URLs with `white-space: nowrap` in HTML.
9. **Tracker additions as TSV** -- NEVER edit applications.md to add new entries. Write TSV in `batch/tracker-additions/` and `merge-tracker.mjs` handles the merge.
10. **Include `**URL:**` in every report header** -- between Score and PDF.

### Tools

| Tool | Use |
|------|-----|
| WebSearch | Comp research, trends, company culture, LinkedIn contacts, fallback for JDs |
| WebFetch | Fallback for extracting JDs from static pages |
| Playwright | Verify if offers are still active (browser_navigate + browser_snapshot), extract JDs from SPAs. **CRITICAL: NEVER launch 2+ agents with Playwright in parallel -- they share a single browser instance.** |
| Read | cv.md, article-digest.md, cv-template.html |
| Write | Temporary HTML for PDF, applications.md, reports .md |
| Edit | Update tracker |
| Bash | `node generate-pdf.mjs` |
