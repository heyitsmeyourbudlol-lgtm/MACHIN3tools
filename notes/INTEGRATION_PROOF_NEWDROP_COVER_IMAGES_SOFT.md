# Integration proof — Newdrop Hard-Fix #75 Soft (cover image hotlink)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `8f1acd5b` |
| Docs | `docs/ops/COVER_IMAGES.md` · SECURITY_AUDIT §21.16 |
| Code | existing `sanitizeHttpsImageUrl` (HTTPS + SSRF host block) |
| Verify | `npm test` 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document hotlink residual (tracking / breakage / no scan)
- [x] Document deferred Storage ACL (#94)
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
