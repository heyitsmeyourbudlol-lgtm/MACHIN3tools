# Integration proof — Newdrop HTTPS-only public changelog head + auth redirect SoT (#254)

- **When:** 2026-09-09T00:24Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #253`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/254
  - branch `peer/factory-dist-seo-after253`
  - product commit `3b5a5e6`
  - merge commit `f236d01f29f2ef7f8abc2621bf1b5e45c37d48e0` on `main`
- **Needle:** `buildPublicChangelogMetadata` absolute HTTPS canonical + RSS/JSON Feed `rel=alternate` via `publicChangelogUrl` (verified custom domain or marketing SoT) · server `authCallbackUrl` / `emailConfirmUrl` → `marketingHttpsAppUrl` (browser keeps this-deployment origin) · extends #244–#253 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **626 passed** EXIT 0
  - `npm run check:controls` — **499 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #254**
