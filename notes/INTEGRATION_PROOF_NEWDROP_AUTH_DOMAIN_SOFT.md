# Integration proof — Newdrop custom Auth domain Soft residual (#187)

- **When:** 2026-09-08T12:39Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #185` (tip raced through #186; worked after #186)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/187
  - branch `peer/factory-hf25-auth-domain-soft-after186`
  - product commit `b5bf887`
  - merge commit `1267b83a453e9e9c2673b50830a015047b918fc4` on `main`
- **Needle:** Hard-Fix #25 Soft residual · stay on Supabase Auth host · `docs/ops/AUTH_DOMAIN.md` · SECURITY_AUDIT §21.9 · CSP unlock pointer · Accept still open
- **Native verify (pre-merge):**
  - `npm test` — **501 passed** EXIT 0
  - `npm run check:controls` — **236 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Prior residual:** [#142](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/142) deferred checklist; Soft ops runbook upgrades residual → Soft residual pattern
- **Next step:** leave Active **Newdrop tip-cover after #187**
