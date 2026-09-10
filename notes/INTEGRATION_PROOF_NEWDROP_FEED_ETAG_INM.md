# Integration proof — Newdrop feed ETag + If-None-Match 304 (#216)

- **When:** 2026-09-08T20:46Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #215`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/216
  - branch `peer/factory-dist-seo-after215`
  - product commit `1eba79a6d2007458c812069eea2dada4628c388a`
  - merge commit `b406a818b965d5c6423584af514ebc17deb8d2c4` on `main`
- **Needle:** `feedWeakEtag` / `feedIfNoneMatchNotModified` · public RSS + JSON Feed weak **ETag** + **If-None-Match → 304** · RFC 7232 INM precedence over IMS · fail-closed bad INM → 200 · password feeds stay `401`/`no-store` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **556 passed** EXIT 0
  - `npm run check:controls` — **344 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed headers only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #216**
