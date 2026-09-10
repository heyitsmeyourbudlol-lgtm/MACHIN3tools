# Integration proof — Newdrop HF64 hotpath alias scrub (#161+#163)

- **When:** 2026-09-08T05:26Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Irreversible artifacts:**
  - [#161](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/161) merge `3a55817` · product `35fc25a` · `RATE_LIMIT_HOTPATH.md` Soft residual + controls
  - [#163](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/163) merge `e303743` · product `c162c92` · scrub HARD_FIXES #64 conflict markers; alias HOTPATH → `RATE_LIMIT.md`
- **Needle:** Hard-Fix #64 Soft residual hygiene · canonical `docs/ops/RATE_LIMIT.md` · SECURITY_AUDIT §21.11
- **Native verify (tip `e303743`):**
  - `npm run check:controls` — **178 ok · 0 fail** EXIT 0
  - `npm test` — pending/parallel tip verify
- **UI:** untouched · **NO PAY**
- **Next step:** closed — leave Active after #163 open
