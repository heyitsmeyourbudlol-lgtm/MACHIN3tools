# Integration proof — Newdrop feed HTML alternate + Dublin Core date (#225)

- **When:** 2026-09-08T21:39Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #224`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/225
  - branch `peer/factory-dist-seo-after224`
  - product commit `54fa49c`
  - merge commit `989f5a0a95f6cd0afa47b744bfaf0c246afc720b` on `main`
- **Needle:** `FEED_HTML_ALTERNATE_TYPE` / `htmlHref` / `feedRssDcDate` · HTTP Link + RSS `atom:link` HTML alternate · RSS `<dc:date>` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **587 passed** EXIT 0
  - `npm run check:controls` — **392 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed discovery + dc:date only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #225**
