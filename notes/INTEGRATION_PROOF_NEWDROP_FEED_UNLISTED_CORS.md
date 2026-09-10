# Integration proof — Newdrop feed unlisted CORS fail-closed (#233)

- **When:** 2026-09-08T22:22Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #232`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/233
  - branch `peer/factory-dist-seo-after232`
  - product commit `a0decf8`
  - merge commit `7964856e82a0583e1f0a829a234a62213d78d9fa` on `main`
- **Needle:** `feedVisibilityAllowsPublicCors` / `withFeedBrowserInteropHeaders` / `withFeedContentLanguageHeaders` · RSS + JSON Feed omit `Access-Control-Allow-Origin` for **unlisted** (password parity; capability-URL privacy) · unlisted keeps `Content-Language` without ACAO · public CORS unchanged · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **593 passed** EXIT 0
  - `npm run check:controls` — **415 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed CORS/interop headers only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #233**
