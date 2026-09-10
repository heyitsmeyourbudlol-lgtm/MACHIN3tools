# Integration proof — Newdrop RSS/JSON Feed item permalinks (#202)

- **When:** 2026-09-08T18:53Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #201`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/202
  - branch `peer/factory-feed-item-permalinks-after201`
  - product commit `31f1503`
  - merge commit `2f43d1fce829a4d9ec9044d39bb36acaa6a586f6` on `main`
- **Needle:** `publicChangelogUpdateUrl` · JSON Feed `item.url` + RSS `<link>` use `?u=<updateId>` · aggregators no longer see every item as the changelog home · `check:controls` pins · **UI untouched** · **NO PAY** · **0016 not applied**
- **Native verify (pre-merge):**
  - `npm test` — **518 passed** EXIT 0
  - `npm run check:controls` — **291 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed distribution; no UI chrome / no dogfood widget note — aggregator link shape only)
- **Next step:** leave Active **Newdrop tip-cover after #202**
