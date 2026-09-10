# Newdrop — Hard-Fix #97 billing share residual (service-role)

- **PR:** [#175](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/175)
- **Merge:** `2b3b31f` · product `f9c428e`
- **Change:** Shared `billingAdminClient` for billing modules + module-local helpers for ensure-account and containment (53→45 sites); `check:service-role` max 45
- **Verify:** `npm test` 501 · `check:controls` 207ok
- **UI:** untouched · **NO PAY**
- **Date:** 2026-09-08
