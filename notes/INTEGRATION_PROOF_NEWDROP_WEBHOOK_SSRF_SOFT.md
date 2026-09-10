# Integration proof — Newdrop webhook SSRF Soft residual (#197)

- **When:** 2026-09-08T13:09Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #195` (tip raced → work after #196)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/197
  - branch `peer/factory-hf54-ssrf-soft-after196`
  - product commit `405906e`
  - merge commit `361082f47ec9ef3f493c1de00c97b78b48e217b4` on `main`
- **Needle:** Hard-Fix #54 Soft residual · `docs/ops/WEBHOOK_SSRF.md` + SECURITY_AUDIT §21.24 · DNS pin Soft-accepted · plain-`fetch` / IP-reassignment / preview re-resolve residual · **UI untouched** · **NO PAY** · **0016 not applied**
- **Native verify (pre-merge):**
  - `npm test` — **514 passed** EXIT 0
  - `npm run check:controls` — **278 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (ops Soft residual only; no UI chrome / no dogfood publish)
- **Next step:** leave Active **Newdrop tip-cover after #197**
