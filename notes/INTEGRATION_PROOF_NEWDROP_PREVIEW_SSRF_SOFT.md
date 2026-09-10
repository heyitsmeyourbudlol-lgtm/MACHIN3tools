# Integration proof — Newdrop Preview SSRF Soft residual (#206)

- **When:** 2026-09-08T19:21Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** tip-cover after #204 (tip raced #205 OG/SEO; Soft residual rebased onto #205 → landed #206)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/206
  - branch `peer/factory-hf99-preview-ssrf-soft-after204`
  - product commit `990519bb4c9ea833e87ad534e1b8503c1b13cafb`
  - merge commit `a4edf716def442b634c84e18d412a787fde021e8` on `main`
- **Needle:** Hard-Fix #99 Soft residual · `docs/ops/PREVIEW_SSRF.md` + SECURITY_AUDIT §21.27 · re-resolve Soft-accepted without DNS pin Soft · pin Soft / allowlist egress deferred · `check:controls` pins · **UI untouched** · **NO PAY** · **0016 not applied**
- **Native verify (pre-merge):**
  - `npm test` — **523 passed** EXIT 0
  - `npm run check:controls` — **300 ok · 0 fail** EXIT 0
  - CI `test` job — **SUCCESS**
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (ops Soft residual only; no UI chrome / skip dogfood)
- **Next step:** leave Active **Newdrop tip-cover after #206**
