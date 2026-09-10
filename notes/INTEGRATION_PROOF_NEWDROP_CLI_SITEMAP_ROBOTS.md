# Integration proof — Newdrop sitemap + robots Write CLI (#287)

- **When:** 2026-09-09T05:38Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #286`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/287
  - branch `peer/factory-cli-sitemap-after286`
  - product commit `ace17bff`
  - merge commit `f0df23cc4cd97eea48c76db7a992b83b54952a3d` on `main`
- **Needle:** marketing sitemap + robots Allow pin `/cli/newdrop.mjs` (parity with SDK/GHA #282; already cited in llms.txt) · HTTPS-only crawl base via `marketingHttpsAppUrl` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **736 passed** EXIT 0
  - `npm run check:controls` — **528 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution SEO crawl pins only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #287** (superseded → after #288 Soft Soft tip race #50)
