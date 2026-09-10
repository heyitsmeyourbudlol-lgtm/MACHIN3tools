# Integration proof — Newdrop crawl-brief OPTIONS + 405 (#294)

- **When:** 2026-09-09T06:05Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #293`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/294
  - branch `peer/factory-crawl-brief-options-after293-20260909T060200Z`
  - product commit `e7b986b7`
  - merge commit `09819cf536341e5e0d711e4d5317fb5adaa0837e` on `main`
- **Needle:** shared `crawlBriefCors` — `/llms.txt` + `/.well-known/security.txt` honor CORS `OPTIONS` preflight (204 + Max-Age) and fail-closed write probes with **405** + `Allow: GET, HEAD, OPTIONS` (parity feed #234/#240); does **not** duplicate #293 hub/CORP · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **750 passed** EXIT 0
  - `npm run check:controls` — **552 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (crawl-brief method gate only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #294**
