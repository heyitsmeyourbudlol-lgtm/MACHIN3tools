# Integration proof — Newdrop session revoke-all (#100)

- **PR:** [#137](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/137) **MERGED** `9916146`
- **Product:** `8d5e127` · branch `peer/factory-hf100-revoke`
- **Verify (tip):** `npm test` 475 PASS · `check:controls` 139ok · UI untouched · NO PAY
- **Change:** `revokeAllSessions` pins GoTrue `signOut({ scope: "global" })`; `/auth/signout` uses helper; rate-limited `revokeAllSessionsAction` (5/hr). Device inventory residual.
- **Needle:** Hard-Fix #100 · `OVERSEER_NEWDROP_SESSION_REVOKE_2026_09_08`
