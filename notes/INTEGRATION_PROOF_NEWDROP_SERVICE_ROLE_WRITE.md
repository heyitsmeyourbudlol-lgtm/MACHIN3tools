# Newdrop — Hard-Fix #97 residual (service-role write/telemetry/team)

- **PR:** [#172](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/172)
- **Merge:** `c30fd21` · product `7457c86`
- **Change:** Module `serviceRoleClient` helpers for write-api, security-telemetry, support-telemetry, notify, team-actions (63→53 sites); `check:service-role` max 53; DEFINER RPC split still residual
- **Verify:** `npm test` 501 · `check:controls` 197ok · `check:service-role` 53/53
- **UI:** untouched · **NO PAY**
- **Date:** 2026-09-08
