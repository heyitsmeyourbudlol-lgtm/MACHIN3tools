# Integration proof — Newdrop capability-URL noindex + crawl brief CORS (#290)

- **When:** 2026-09-09T05:50Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #289`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/290
  - branch `peer/factory-capurl-noindex-after289-20260909T054825Z`
  - product commit `71d9e795`
  - merge commit `065da06fdb51438c372dc3114a26367f81a57bed` on `main`
- **Needle:** robots Disallow `/preview/` + `/install/` · HTTP `X-Robots-Tag: noindex, nofollow` on capability-URL preview/install · cookieless CORS `*` on `llms.txt` + `security.txt` (parity #289 agent fetch) · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **743 passed** EXIT 0
  - `npm run check:controls` — **536 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (crawl fail-closed + disclosure/llms CORS only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #290**
