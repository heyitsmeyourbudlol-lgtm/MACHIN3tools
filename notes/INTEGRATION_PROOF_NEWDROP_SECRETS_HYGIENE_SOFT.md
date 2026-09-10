# Integration proof — Newdrop Hard-Fix #69 Soft (secrets hygiene)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror; Mac `/Users/togi/CaaS` missing) |
| Branch | `peer/external-proof-caas` |
| Commit | `c9ef6ab7` |
| Docs | `docs/ops/SECRETS_HYGIENE.md` · SECURITY_AUDIT §21.14 · AGENT_WORKFLOW rotate checklist · LONG_TERM ops follow-ups link |
| Verify | `npm test` 323 PASS · `check:controls` 13 ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` (`OVERSEER_DEMOTE_PUSH_DEFERRED_2026_09_08`) |
| NO PAY | yes |

## AC checklist

- [x] Quarterly rotate runbook for ADMIN_SECRET / CRON_SECRET / webhooks
- [x] Linked from LONG_TERM + AGENT_WORKFLOW + §21.14
- [x] `npm test` + `check:controls` green (on CLEAN tree)
- [x] No UI
- [ ] PR merged (await CLEAN git creds or Mac `gh`)
- [ ] EXTERNAL_PROOF / FACTORY_PROOF / scoreboard row after merge

## Hub needles

- Soft residual land: this file
- Queue demote: `OVERSEER_DEMOTE_PUSH_DEFERRED_2026_09_08`
