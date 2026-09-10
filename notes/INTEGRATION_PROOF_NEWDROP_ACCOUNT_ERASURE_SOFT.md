# Integration proof — Newdrop account erasure Soft residual (#199)

- **When:** 2026-09-08T13:14Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #197` (tip raced → #198 JSON Feed ISR; work after #198)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/199
  - branch `peer/factory-hf72-erasure-soft-after198`
  - product commit `72ce14b`
  - merge commit `3317886c1e263a63e729a296aa967c0ef54b3a78` on `main`
- **Needle:** Hard-Fix #72 Soft residual · `docs/ops/ACCOUNT_ERASURE.md` + SECURITY_AUDIT §21.25 · owner erase Soft-accepted · PITR/backup/vendor retention Soft · **UI untouched** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **516 passed** EXIT 0
  - `npm run check:controls` — **284 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (ops Soft residual only; no UI chrome / skip dogfood)
- **Next step:** leave Active **Newdrop tip-cover after #199**
