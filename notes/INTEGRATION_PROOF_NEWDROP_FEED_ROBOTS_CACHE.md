# Integration proof — Newdrop feed unlisted/password robots + cache (#231)

- **When:** 2026-09-08T22:10Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #230`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/231
  - branch `peer/factory-dist-seo-after230`
  - product commit `59e2eb0`
  - merge commit `16ccbc924f62b1b48ef00a75a57347af56079da7` on `main`
- **Needle:** `feedXRobotsTag` / `feedCacheControl` / `withFeedRobotsHeaders` · RSS + JSON Feed `X-Robots-Tag: noindex, nofollow` for unlisted/password (HTML robots parity) · unlisted `private, max-age=60` (no shared CDN) · password `no-store` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **590 passed** EXIT 0
  - `npm run check:controls` — **410 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed robots/cache only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #232** (landed via [#232](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/232))
