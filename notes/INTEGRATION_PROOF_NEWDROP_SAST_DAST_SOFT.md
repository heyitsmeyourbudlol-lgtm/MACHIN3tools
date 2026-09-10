# Integration proof — Newdrop Hard-Fix #84 Soft (CodeQL/Semgrep/DAST residual)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `12b0034e` |
| Docs | `docs/ops/SAST_DAST.md` · SECURITY_AUDIT §21.29 |
| Code | Tip Soft-shipped CodeQL/Semgrep named; DAST/auth DAST Soft residual + Soft checklist — no UI |
| Verify | `npm test` / vitest 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document Soft residual (CodeQL/Semgrep Soft-shipped on tip; DAST/auth DAST residual) + Soft checklist (no UI)
- [x] Soft checklist (no UI)
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
