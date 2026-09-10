# Integration proof — Newdrop feed early GET rate-limit + RateLimit headers (#237)

- **When:** 2026-09-08T22:48Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #236`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/237
  - branch `peer/factory-dist-seo-after236`
  - product commit `cc31479`
  - merge commit `e54f5b993dbd12f67dabec1d64cf9caf0ef8f06e` on `main`
- **Needle:** `Early feed GET rate-limit (before slug RPC)` · `feedRateLimitHeaders` · `RateLimit-Limit` / `RateLimit-Remaining` / `RateLimit-Reset` · CORS expose RateLimit-* + `Retry-After` · Postgres `consume_rate_limit` `failClosed: true` before `get_project_by_slug` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **598 passed** EXIT 0
  - `npm run check:controls` — **433 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed early RL + RateLimit headers only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #237**
