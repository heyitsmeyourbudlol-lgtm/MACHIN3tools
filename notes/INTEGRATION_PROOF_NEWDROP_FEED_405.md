# Integration proof — Newdrop feed 405 method-not-allowed (#240)

- **When:** 2026-09-08T23:02Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #239`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/240
  - branch `peer/factory-dist-seo-after239`
  - product commit `ad1b706`
  - merge commit `4b8ea7a7e24d38eb2dd30f8be5e3769f6c75d69b` on `main`
- **Needle:** Explicit `POST`/`PUT`/`PATCH`/`DELETE` on RSS + JSON Feed → **405** with `Allow: GET, HEAD, OPTIONS` + early RL (same bucket as GET; skip slug RPC) · `feedMethodNotAllowedHeaders` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **600 passed** EXIT 0
  - `npm run check:controls` — **444 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (405 + Allow only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #240**
