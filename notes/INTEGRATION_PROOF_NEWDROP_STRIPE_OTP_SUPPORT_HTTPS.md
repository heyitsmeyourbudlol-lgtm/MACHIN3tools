# Integration proof — Newdrop HTTPS-only Stripe return + auth OTP + support dashboard cites SoT (#253)

- **When:** 2026-09-09T00:18Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #252`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/253
  - branch `peer/factory-dist-seo-after252`
  - product commit `d15dfa6`
  - merge commit `ccc98fe5278bf4372a28bba7e3180e3dee71bb28` on `main`
- **Needle:** Stripe Checkout success/cancel + Portal return_url → `marketingHttpsAppUrl` · auth OTP `emailRedirectTo` HTTPS SoT · support KB/presets dashboard/billing/team/security cites HTTPS SoT · embed.js + CSP stay on this-deployment `appUrl()` · extends #252 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **622 passed** EXIT 0
  - `npm run check:controls` — **496 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #253**
