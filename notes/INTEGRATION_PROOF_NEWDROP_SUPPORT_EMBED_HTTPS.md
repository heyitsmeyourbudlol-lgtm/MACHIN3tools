# Integration proof — Newdrop HTTPS-only support embed + CSP cite SoT (#267)

- **When:** 2026-09-09T02:04Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #265`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/267
  - branch `peer/factory-dist-seo-after265` (rebased over Soft Soft #100 [#266](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/266))
  - product commit `f03fb5aa00acab21c9c7f37eff905fdde48f3790`
  - merge commit `ac3fa9f13be0bda16ab633a7dc028e0ae3b5aeb2` on `main`
- **Needle:** Support presets + site KB `embed.js` + CSP hosts → `marketingHttpsAppUrl` fail-closed · parity with Setup/docs #252/#264 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge, post-rebase onto tip ≥#266):**
  - `npm test` — **681 passed** EXIT 0
  - `npm run check:controls` — **515 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #267**
