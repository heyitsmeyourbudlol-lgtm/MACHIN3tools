# Integration proof — Newdrop CSP Soft residual (#195)

- **When:** 2026-09-08T13:03Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #194` (tip was robots+security.txt #194; landed CSP Soft as #195)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/195
  - branch `peer/factory-csp-soft-after194`
  - product commit `e398212`
  - merge commit `88524d739e239ff9ab421546c82dd00de177ade7` on `main`
- **Needle:** Hard-Fix #71 CSP Soft residual · `docs/ops/CSP.md` + SECURITY_AUDIT §21.23 · `'unsafe-eval'` dropped Soft-accepted · `'unsafe-inline'` + nonces deferred until Next/Stripe cutover · `check:controls` pins · **UI untouched** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **511 passed** EXIT 0
  - `npm run check:controls` — **266 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (ops Soft docs + header Soft pointer; no UI chrome; skip dogfood — internal/security Soft)
- **Next step:** leave Active **Newdrop tip-cover after #195**
