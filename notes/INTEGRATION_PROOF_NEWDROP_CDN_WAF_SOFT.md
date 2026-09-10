# Integration proof — Newdrop Hard-Fix #63 Soft (CDN/WAF edge)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `25c0c11b` |
| Docs | `docs/ops/CDN_WAF.md` · SECURITY_AUDIT §21.21 |
| Code | existing Postgres `consume_rate_limit` via `rateLimit()` — no Cloudflare enabled |
| Verify | `npm test` 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document app-layer Postgres RL-only residual
- [x] Document DNS/WAF cutover posture (Soft does not put Cloudflare live)
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
