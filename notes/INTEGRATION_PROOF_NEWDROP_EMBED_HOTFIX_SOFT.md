# Integration proof — Newdrop Hard-Fix #88 Soft (embed hotfix purge)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `059f7e2b` |
| Docs | `docs/ops/EMBED_HOTFIX.md` · SECURITY_AUDIT §21.19 |
| Code | existing `next.config.ts` `/embed.js` Cache-Control (`s-maxage=15`) |
| Verify | `npm test` 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document short TTL already shipped
- [x] Document CDN purge / redeploy checklist
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
