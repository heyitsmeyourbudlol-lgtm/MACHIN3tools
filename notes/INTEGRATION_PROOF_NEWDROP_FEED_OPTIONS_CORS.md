# Integration proof — Newdrop feed OPTIONS CORS visibility fail-closed (#234)

- **When:** 2026-09-08T22:27Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #233`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/234
  - branch `peer/factory-dist-seo-after233`
  - product commit `686eee8`
  - merge commit `3280dd0039eed1c56f9edc04bc1806c5715a1f7d` on `main`
- **Needle:** `feedCorsPreflightHeaders(visibility)` · RSS + JSON Feed `OPTIONS` look up project visibility · omit `Access-Control-Allow-Origin` for **unlisted** / **password** / missing / inactive (GET/HEAD parity; closes always-public preflight residual) · public preflight unchanged · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **594 passed** EXIT 0
  - `npm run check:controls` — **418 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (OPTIONS preflight headers only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #234**
