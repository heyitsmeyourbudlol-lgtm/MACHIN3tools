# Integration proof — Newdrop feed CORS + Content-Language (#219)

- **When:** 2026-09-08T21:05Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #218`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/219
  - branch `peer/factory-dist-seo-after218`
  - product commit `e3f3831`
  - merge commit `5add89be5a0b72c7d1182b602e459d80a28a95e0` on `main`
- **Needle:** `withFeedPublicCorsHeaders` / `feedCorsPreflightHeaders` / `FEED_CONTENT_LANGUAGE` · public RSS + JSON Feed CORS (`ACAO *`, methods, expose ETag/Last-Modified/Link) on 200/304 + OPTIONS · password feeds omit ACAO · Content-Language parity · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **566 passed** EXIT 0
  - `npm run check:controls` — **362 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed headers only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #220** (landed #220; see `notes/INTEGRATION_PROOF_NEWDROP_FEED_AUTHORS.md`)
