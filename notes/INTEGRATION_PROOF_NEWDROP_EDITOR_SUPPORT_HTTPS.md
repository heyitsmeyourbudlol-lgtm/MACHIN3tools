# Integration proof — Newdrop HTTPS-only editor publish + support distribution SoT (#247)

- **When:** 2026-09-08T23:46Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #246`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/247
  - branch `peer/factory-dist-seo-after246`
  - product commit `da13344`
  - merge commit `267f916d196c8923a20fef519d0d627c00150220` on `main`
- **Needle:** `sendEditorPublishEmail` “View public changelog” → `publicChangelogUrl` (+ `projectSlug`) · support KB/presets public What’s New / RSS / docs / security → `marketingHttpsAppUrl` / `SITE_DOGFOOD_SLUG` · embed.js/dashboard/API stay `appUrl()` · reply scrubber `isAllowedSupportUrl` (marketing HTTPS survives cleartext APP_URL) · extends #246 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **615 passed** EXIT 0
  - `npm run check:controls` — **475 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (email/support HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #247**
