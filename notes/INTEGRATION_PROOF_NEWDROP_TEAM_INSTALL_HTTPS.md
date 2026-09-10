# Integration proof — Newdrop HTTPS-only team invite + install-pack distribution SoT (#250)

- **When:** 2026-09-09T00:00Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #249`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/250
  - branch `peer/factory-dist-seo-after249`
  - product commit `f26ae7e`
  - merge commit `3b3e7d8cb6561c37ab60eef1da7e003ad236d739` on `main`
- **Needle:** team invite accept + Team fallback cites → `marketingHttpsAppUrl` · install-pack `/install/{token}` share URLs HTTPS SoT · ops slug-change page public `/c/{slug}` cites HTTPS SoT · extends #249 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **620 passed** EXIT 0
  - `npm run check:controls` — **486 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (invite/install HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #250**
