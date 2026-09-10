# Integration proof — Newdrop feed Dublin Core rights (#229)

- **When:** 2026-09-08T21:58Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #228`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/229
  - branch `peer/factory-dist-seo-after228`
  - product commit `3a605aa`
  - merge commit `b93cdd8070ba504b7e11232cbb38cfe521bd5f96` on `main`
- **Needle:** `feedRssDcRights` · RSS `<dc:rights>` channel+items (parity with `<copyright>`) · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **587 passed** EXIT 0
  - `npm run check:controls` — **405 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed dc:rights only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #229**
