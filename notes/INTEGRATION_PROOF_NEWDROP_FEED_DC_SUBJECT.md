# Integration proof — Newdrop feed Dublin Core subject (#227)

- **When:** 2026-09-08T21:49Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #226`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/227
  - branch `peer/factory-dist-seo-after226`
  - product commit `fc570d2`
  - merge commit `ef286ef2dcce86006a06902ee3d0b5fa66ea67f8` on `main`
- **Needle:** `feedRssDcSubject` · RSS `<dc:subject>` from update tag · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **587 passed** EXIT 0
  - `npm run check:controls` — **398 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed dc:subject only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #227**
