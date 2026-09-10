# Integration proof — Newdrop service-role shared email/ops/auth clients (#97)

- PR: [#176](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/176) merge `7fe3019` · product `44978fe`
- Scope: Hard-Fix #97 residual after #175 — shared `emailAdminClient` / `opsAdminClient` / `authAdminClient` (45 → 33 `createAdminClient` sites); `check:service-role` max 33; DEFINER RPC split still residual
- Verify: npm test 501 · check:controls 206ok · **UI untouched** · NO PAY
- Date: 2026-09-08
