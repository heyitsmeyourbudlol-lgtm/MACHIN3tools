# Integration proof — Newdrop Hard-Fix #66 Soft (kill switches)

_Date: 2026-09-08_ · CLEAN Soft land · **PR pending** (push auth blocked)

## Land

| Field | Value |
|-------|-------|
| Repo | `/home/arnavrastogi/CaaS` (CLEAN mirror; Mac `/Users/togi/CaaS` missing) |
| Branch | `peer/external-proof-caas` |
| Commit | `95c1a617` |
| Rule | **env mirrors DB** for shared keys (`widgets`/`subscribe`) |
| Docs | `docs/ops/KILL_SWITCHES.md` · SECURITY_AUDIT §21.13 |
| Code | `buildEffectiveKillReport` → containment GET/status + deep `/api/health?deep=1` |
| Verify | `npm test` 323 PASS · `check:controls` 13 ok |
| UI | untouched |
| Push | **blocked** — empty `~/.git-credentials` / no `gh` (`OVERSEER_DEMOTE_PUSH_DEFERRED_2026_09_08`) |
| NO PAY | yes |

## AC checklist

- [x] One documented kill path (env mirrors DB)
- [x] `npm test` + `check:controls` green (on CLEAN tree)
- [x] No UI
- [ ] PR merged (await CLEAN git creds or Mac `gh`)
- [ ] EXTERNAL_PROOF / FACTORY_PROOF / scoreboard row after merge

## Hub needles

- Soft residual land: this file
- Queue demote gap fixed: `OVERSEER_DEMOTE_PUSH_DEFERRED_2026_09_08` in `scripts/project_automation.py`
