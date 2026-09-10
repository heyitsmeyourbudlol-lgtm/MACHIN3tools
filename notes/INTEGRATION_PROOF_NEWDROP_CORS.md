# Integration proof — Newdrop public CORS Soft residual (#189)

- **When:** 2026-09-08T12:44Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #187` (tip raced through #188 Hard-Fix #83 Soft; worked after #188)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/189
  - branch `peer/factory-hf42-cors-soft-after188`
  - product commit `4800834`
  - merge commit `74d6e9af90ebf6afff5ce234608ed5901c174fa1` on `main`
- **Needle:** Hard-Fix #42 Soft residual · shared `withPublicCors` · reflect Origin Soft-accepted while cookieless · Origin allowlist / credentialed CORS deferred · `docs/ops/CORS.md` · SECURITY_AUDIT §21.22 · Accept still open
- **Native verify (pre-merge):**
  - `npm test` — **501 passed** EXIT 0
  - `npm run check:controls` — **242 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Next step:** leave Active **Newdrop tip-cover after #189**
