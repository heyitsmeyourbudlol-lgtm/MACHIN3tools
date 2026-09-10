# Integration proof — Newdrop HTTPS-only preview probe + CLI API base SoT (#259)

- **When:** 2026-09-09T01:51Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #257` (tip raced Soft Soft #258; land is after #258 / PR #259)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/259
  - branch `peer/factory-dist-seo-after257`
  - product commit `4845eaa433b6bbaef8b83ee4dfb442e7f02e5dca`
  - merge commit `d4cce57ca8efcbc12ea6011f30bb1f982b0884ca` on `main`
- **Needle:** `/api/preview/check` + `probePreviewSite` origin → `marketingHttpsAppUrl` · CLI `NEWDROP_API_URL` `resolveHttpsApiBase` fail-closed → HTTPS-only · extends #257 preview SoT · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge, post-rebase onto #258):**
  - `npm test` — **649 passed** EXIT 0
  - `npm run check:controls` — **510 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #259**
