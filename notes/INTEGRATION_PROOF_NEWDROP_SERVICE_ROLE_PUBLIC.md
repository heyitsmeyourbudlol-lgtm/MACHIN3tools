# Integration proof — Newdrop service-role public + route/admin share (#97)

- PR: [#179](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/179) merge `3d6b607` · product `b5e7955`
- Scope: Hard-Fix #97 residual after #177 — shared `publicAdminClient` (public API + `/c/[slug]`); migrate OTP/Stripe/ops/unlock/dashboard onto domain helpers (22 → 8 `createAdminClient` sites); `check:service-role` max 8; DEFINER RPC split still residual
- Verify: npm test 501 · check:controls 206ok · **UI untouched** · NO PAY
- Date: 2026-09-08
