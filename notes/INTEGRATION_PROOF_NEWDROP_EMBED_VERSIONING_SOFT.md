# Integration proof — Newdrop Hard-Fix #62 Soft (embed versioning)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `33093631` |
| Docs | `docs/ops/EMBED_VERSIONING.md` · SECURITY_AUDIT §21.18 |
| Code | existing `public/embed.js` + `next.config.ts` `/embed.js` Cache-Control (`s-maxage=15`) |
| Verify | `npm test` 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document unversioned `/embed.js` residual
- [x] Document dual-serve / `embed.vN.js` cutover posture
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
