# Integration proof — Newdrop public widget API CORP (#297)

- **When:** 2026-09-09T06:07Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #294` (retarget; closed unmerged #295 CORP revived + rebased onto #294; closed #296 ops capurl to avoid double-merge)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/297
  - branch `peer/factory-public-corp-after294-20260909T060615Z`
  - product commit `64d3c780`
  - merge commit `0ba46f20ddf1185d6564420a0f2e391cc13ed82d` on `main`
- **Needle:** `withPublicCors` + `/api/v1/public/*` edge headers set `Cross-Origin-Resource-Policy: cross-origin` so COEP `require-corp` customer pages that load `/embed.js` (#293) can also fetch cookieless widget APIs (parity embed + public feed CORP; still no credentials) · `PUBLIC_WIDGET_CORP` + vitest + `check:controls` · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only** · **does not duplicate #293/#294**
- **Native verify (pre-merge):**
  - `npm test` — **752 passed** EXIT 0
  - `npm run check:controls` — **554 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (widget API CORP only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #297**
