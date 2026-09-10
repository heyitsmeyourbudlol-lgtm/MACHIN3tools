# Integration proof — Newdrop feed permalink ?u= head SEO (#207)

- **When:** 2026-09-08T19:45Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #205` (tip raced Soft #206; landed distribution SEO code as #207 after tip #206)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/207
  - branch `peer/factory-dist-seo-after206`
  - product commit `be16e81`
  - merge commit `d4b64039849a5a2ba759a54f6988beee5ba6c79d` on `main`
- **Needle:** Feed `?u=` permalinks → per-update title/description/canonical/OG/Twitter (+ HTTPS-safe cover `og:image`) via `buildPublicChangelogMetadata` · unknown id fail-soft · password fail-closed · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **529 passed** EXIT 0
  - `npm run check:controls` — **303 ok · 0 fail** EXIT 0
  - `npx tsc --noEmit` — clean
  - CI `test` job — **SUCCESS** (CodeQL Soft-fail: scanning not enabled on private free GH)
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (head metadata only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #207**
