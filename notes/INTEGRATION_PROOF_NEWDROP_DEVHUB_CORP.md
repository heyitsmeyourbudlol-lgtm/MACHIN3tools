# Integration proof — Newdrop agent packs hub + embed CORP (#293)

- **When:** 2026-09-09T06:01Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #292` (retarget after tip race #292 embed.v2 crawl)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/293
  - branch `peer/factory-devhub-corp-after292-20260909T060014Z`
  - product commit `6c0d5f93`
  - merge commit `2aea15e75092ef45d76d2ef040715ed1b410658b` on `main`
- **Needle:** `llms.txt` + marketing sitemap + robots Allow pin `/dev/index.html` (agent packs hub; pairs with `/dev/packs.md`) · cookieless CORS `*` + typed HTML for the hub · `Cross-Origin-Resource-Policy: cross-origin` on `/embed.js` + `/embed.v2.js` + agent distribution statics + `llms.txt` + `security.txt` (COEP `require-corp` hosts; parity with public feed CORP) · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only** · **does not duplicate #292**
- **Native verify (pre-merge):**
  - `npm test` — **743 passed** EXIT 0
  - `npm run check:controls` — **551 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution SEO crawl + CORP only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #293**
