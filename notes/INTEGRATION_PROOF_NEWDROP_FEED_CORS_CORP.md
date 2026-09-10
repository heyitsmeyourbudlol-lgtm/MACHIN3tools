# Integration proof — Newdrop feed CORS Allow-Headers + CORP visibility (#235)

- **When:** 2026-09-08T22:33Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #234`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/235
  - branch `peer/factory-dist-seo-after234`
  - product commit `41e9793`
  - merge commit `ea3e6bdec9b14ef37f688ac159137407498a3662` on `main`
- **Needle:** `FEED_CORS_ALLOW_HEADERS` (`If-None-Match, If-Modified-Since`) on public RSS/JSON Feed CORS · `feedCrossOriginResourcePolicy` / `FEED_CORP_CROSS_ORIGIN` / `FEED_CORP_SAME_ORIGIN` · public `Cross-Origin-Resource-Policy: cross-origin` · unlisted/password `same-origin` (no-cors capability-URL fail-closed; complements omitting ACAO) · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **594 passed** EXIT 0
  - `npm run check:controls` — **423 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed CORS/CORP headers only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #235**
