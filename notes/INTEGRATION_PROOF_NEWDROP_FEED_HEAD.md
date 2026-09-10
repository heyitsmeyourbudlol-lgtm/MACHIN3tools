# Integration proof — Newdrop feed explicit HEAD + Allow header (#239)

- **When:** 2026-09-08T22:59Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #238`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/239
  - branch `peer/factory-dist-seo-after238`
  - product commit `0d37e68`
  - merge commit `30e65aa7e635b2f5d49fdba24549c2bc4b390ba0` on `main`
- **Needle:** Explicit `HEAD` on RSS + JSON Feed (same early RL / 308 / gates / validators as GET; **skip body build**) · `Allow: GET, HEAD, OPTIONS` via `withFeedSecurityHeaders` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **599 passed** EXIT 0
  - `npm run check:controls` — **441 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (HEAD + Allow only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #239**
