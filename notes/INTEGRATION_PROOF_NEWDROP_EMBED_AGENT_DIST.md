# Integration proof — Newdrop embed.js + agent-static distribution (#289)

- **When:** 2026-09-09T05:46Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #288`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/289
  - branch `peer/factory-embed-dist-after288-20260909T054422Z`
  - product commit `85cadfa1`
  - merge commit `c8fb1726462b19b7b4ae6a370ba903520c3a2857` on `main`
- **Needle:** `llms.txt` + marketing sitemap + robots Allow pin `/embed.js` (product widget for AI crawl) · cookieless CORS `*` + typed `Content-Type` + cache for agent statics (OpenAPI / ide-agent / packs / Write SDK+CLI / GitHub Action) · HTTPS-only crawl base unchanged · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **741 passed** EXIT 0
  - `npm run check:controls` — **532 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution SEO crawl + agent-static CORS/Content-Type only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #289**
