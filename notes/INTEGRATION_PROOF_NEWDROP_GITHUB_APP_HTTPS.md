# Integration proof — Newdrop HTTPS-only GitHub App install/callback/resume redirect SoT (#255)

- **When:** 2026-09-09T00:29Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #254`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/255
  - branch `peer/factory-dist-seo-after254`
  - product commit `46ada71`
  - merge commit `ccd35eaec900a909acc89654140f13e2e80859ea` on `main`
- **Needle:** `githubAppCallbackRedirect` + GitHub App install/callback/resume dashboard/login redirects → `marketingHttpsAppUrl` · webhook/API stay this-deployment `appUrl()` · extends #254 auth redirect HTTPS SoT · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **628 passed** EXIT 0
  - `npm run check:controls` — **501 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #255**
