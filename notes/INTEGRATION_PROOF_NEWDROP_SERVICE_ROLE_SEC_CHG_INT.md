# Newdrop — Hard-Fix #97 security/changelog/integrations share residual

- **PR:** [#177](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/177)
- **Merge:** `5908743` · product `c47dd87`
- **Change:** Shared `securityAdminClient` / `changelogAdminClient` / `integrationsAdminClient` + team-actions → `authAdminClient` (33→22 sites); `check:service-role` max 22; DEFINER RPC split still residual
- **Verify:** `npm test` 501 · `check:controls` 206ok · `check:service-role` 22/22
- **UI:** untouched · **NO PAY** · 0016 not applied
- **Date:** 2026-09-08
