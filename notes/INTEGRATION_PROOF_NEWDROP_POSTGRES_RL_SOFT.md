# Integration proof — Newdrop Hard-Fix #64 Soft (Postgres RL hot-path)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `f05ce4e1` |
| Docs | `docs/ops/POSTGRES_RL.md` · SECURITY_AUDIT §21.22 |
| Code | existing Postgres `consume_rate_limit` via `rateLimit()` — Redis deferred; PG failClosed backup kept |
| Verify | `npm test` 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document Postgres RL hot-path contention residual
- [x] Document Redis/Upstash deferred + keep PG failClosed backup
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
