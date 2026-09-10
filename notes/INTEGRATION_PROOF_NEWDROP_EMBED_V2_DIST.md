# Integration proof — Newdrop embed.v2.js distribution crawl pins (#292)

- **When:** 2026-09-09T05:58Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #291`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/292
  - branch `peer/factory-embed-v2-dist-after291-20260909T055552Z`
  - product commit `e942df66`
  - merge commit `d3d94fdbd45ba0debb581bed4e8285ea21a44c8d` on `main`
- **Needle:** `llms.txt` / marketing sitemap / robots Allow pin `/embed.v2.js` (Hard-Fix #62 versioned dual-serve; same script as `/embed.js`) · extends #289/#291 widget distribution · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **743 passed** EXIT 0
  - `npm run check:controls` — **545 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (crawl pins only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #292**
