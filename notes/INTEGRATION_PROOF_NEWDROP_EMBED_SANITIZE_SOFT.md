# Integration proof — Newdrop Hard-Fix #61 Soft (embed Shadow DOM / sanitize)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror) |
| Branch | `peer/external-proof-caas` |
| Commit | `461cda53` |
| Docs | `docs/ops/EMBED_SANITIZE.md` · SECURITY_AUDIT §21.20 |
| Code | existing `CHANGELOG_SANITIZE` + open `attachShadow` in `public/embed.js` |
| Verify | `npm test` 323 PASS · `check:controls` 13ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` |
| NO PAY | yes |

## AC checklist

- [x] Document open Shadow DOM XSS residual
- [x] Document markdown sanitize allowlist posture
- [x] `npm test` + `check:controls` green
- [x] No UI
- [ ] PR merged (await creds)
