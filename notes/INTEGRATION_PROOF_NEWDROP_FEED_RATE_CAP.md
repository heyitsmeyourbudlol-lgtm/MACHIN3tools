# Integration proof — Newdrop feed GET rate-limit + item cap (#236)

- **When:** 2026-09-08T22:42Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #235`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/236
  - branch `peer/factory-dist-seo-after235`
  - product commit `e024ca2`
  - merge commit `15df4a7c0bf1ac35a70453be8b3abc01c53fb3c8` on `main`
- **Needle:** `FEED_MAX_ITEMS` / `clampFeedItems` (50 newest-first) · `feedRateLimitKey` / `FEED_RATE_LIMIT` 120/min IP+slug · Postgres `consume_rate_limit` `failClosed: true` · 429 + `Retry-After` before published-updates RPC · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **597 passed** EXIT 0
  - `npm run check:controls` — **429 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed rate-limit + item clamp only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #236**
