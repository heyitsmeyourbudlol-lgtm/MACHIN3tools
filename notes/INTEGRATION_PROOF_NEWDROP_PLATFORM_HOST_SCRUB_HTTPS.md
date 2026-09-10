# Integration proof — Newdrop HTTPS-only public changelog platform host + preview + support scrub SoT (#257)

- **When:** 2026-09-09T01:40Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #256`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/257
  - branch `peer/factory-dist-seo-after256`
  - product commit `0cb43cd`
  - merge commit `016a9d805326ebee249e2a91ea1de0183bf8d5c5` on `main`
- **Needle:** `/c/{slug}` platform `appHost` + `isGetnewdropPreviewHost` + support scrub `deploymentHttpsHost` → `marketingHttpsAppUrl` / HTTPS-only · parity with proxy `appHostname` #256 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **637 passed** EXIT 0
  - `npm run check:controls` — **507 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #257**
