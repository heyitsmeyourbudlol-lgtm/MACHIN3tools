# Integration proof — Newdrop feed unlisted/password Referrer-Policy (#232)

- **When:** 2026-09-08T22:16Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #231`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/232
  - branch `peer/factory-dist-seo-after231`
  - product commit `0e74285`
  - merge commit `ffd382ddbd1c586be8975857c54e67202e01c395` on `main`
- **Needle:** `feedReferrerPolicy` / `FEED_REFERRER_POLICY_NO_REFERRER` / `withFeedRobotsHeaders` · RSS + JSON Feed `Referrer-Policy: no-referrer` for unlisted/password (capability-URL privacy; HTML `referrer` metadata parity) · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **592 passed** EXIT 0
  - `npm run check:controls` — **413 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed/HTML referrer headers only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #232**
