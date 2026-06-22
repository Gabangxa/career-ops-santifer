# Greenhouse API Scan — 2026-06-22 — FAILED

**Status:** ❌ Network failure — 0 new offers added

## Root Cause

All outbound HTTP is blocked in the remote execution environment (Claude Code on the web). Every request returned `403 Forbidden`:

| What was tried | Result |
|---|---|
| `boards-api.greenhouse.io/v1/boards/*/jobs` × 14 companies | 403 Forbidden |
| `job-boards.greenhouse.io/*` HTML fallback | 403 Forbidden |
| `discord.com` webhook notification | 403 Forbidden |
| `httpbin.org` connectivity test | 403 Forbidden |

This is an **environment network policy** block, not a Greenhouse outage.

## Companies NOT Scanned

FactSet, Wise, Airwallex, Nium, Tipalti, Paddle, Chainalysis, Fireblocks, Paxos, Luno, Mercury, Elastic, Oyster HR, Deel

## Action Required

1. **Run locally:** Open Claude Code on your machine (full network access) and run `/career-ops scan`
2. **Or fix network policy:** In your Claude Code on the Web session settings, enable egress to `*.greenhouse.io` and `discord.com`

---
*Automated scan bot · 2026-06-22 · sokwakhana@gmail.com*
