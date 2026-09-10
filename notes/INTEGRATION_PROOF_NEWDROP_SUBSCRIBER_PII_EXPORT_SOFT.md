# Integration proof — Newdrop Hard-Fix #73 Soft (subscriber PII export / legal hold)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `1d65b779` |
| Docs | `docs/ops/SUBSCRIBER_PII_EXPORT.md` · SECURITY_AUDIT §21.24 |
| Code | owner CSV exists (`exportSubscribersCsv`); Soft residual = audit log + legal-hold freeze + GDPR/hold checklists — no new export UI |
| Verify | `npm test` 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document no-first-class-audit / legal-hold residual (owner CSV named)
- [x] Soft GDPR timeline + legal-hold checklists (no UI)
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
