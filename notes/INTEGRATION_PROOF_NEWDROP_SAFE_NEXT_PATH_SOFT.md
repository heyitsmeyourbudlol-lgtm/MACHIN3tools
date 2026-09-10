# Integration proof — Newdrop Hard-Fix #70 Soft (safeNextPath residual)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `d8536a77` |
| Docs | `docs/ops/SAFE_NEXT_PATH.md` · SECURITY_AUDIT §21.31 |
| Code | Tip Soft-shipped `safeNextPath` allowlist + traversal/`%2e` reject (`src/lib/auth/safe-redirect.ts`); Soft new-route drift checklist — no UI |
| Verify | `npm test` / vitest 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document Soft residual (tip Soft-shipped allowlist; Soft new-route drift) + Soft checklist (no UI)
- [x] Soft checklist (no UI)
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
