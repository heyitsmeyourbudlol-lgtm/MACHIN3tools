# Newdrop — Hard-Fix #97 DEFINER Soft residual

- **PR:** [#181](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/181)
- **Merge:** `f53b989` · product `acd856f`
- **Change:** Soft residual docs — eight domain wrappers share one service-role JWT; DEFINER/custom-role split deferred (`docs/ops/SERVICE_ROLE_DEFINER.md` + SECURITY_AUDIT §21.16); site floor remains **8→8**; 0016 not applied
- **Verify:** `npm test` 501 · `check:controls` 214ok · `check:service-role` 8/8
- **UI:** untouched · **NO PAY**
- **Date:** 2026-09-08
