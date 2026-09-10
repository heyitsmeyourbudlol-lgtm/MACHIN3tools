# Integration proof — Newdrop dogfood sitemap lastmod + RSS guid (#203)

- **When:** 2026-09-08T19:06Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #202` (tip raced Soft #201 → feed permalinks #202; this land is next distribution SEO code)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/203
  - branch `peer/factory-sitemap-dogfood-lastmod-after202-20260908T190304`
  - product commit `a68245f`
  - merge commit `bbb11efb189e83a4bf2f615f727d15ee3a0ae9e3` on `main`
- **Needle:** `fetchSiteDogfoodLastModified` → marketing sitemap dogfood HTML/RSS/`feed.json` `lastModified` · RSS `<guid isPermaLink="true">` matches `?u=` link · fail-soft if Supabase unavailable · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **521 passed** EXIT 0
  - `npm run check:controls` — **294 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (sitemap lastmod + RSS guid; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #203**
