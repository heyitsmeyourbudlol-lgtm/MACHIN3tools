# Integration proof — Newdrop Hard-Fix #65 Soft (trusted proxy / XFF)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `d7b90b0d` |
| Docs | `docs/ops/TRUSTED_PROXY.md` · SECURITY_AUDIT §21.15 |
| Code | existing `clientIpFromHeaders` (platform / rightmost XFF) |
| Verify | `npm test` 323 PASS |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document Vercel first-hop / rightmost XFF trust
- [x] Spoof ignored (tests + runbook)
- [x] `npm test` green
- [x] No UI
- [ ] PR merged (await creds)
