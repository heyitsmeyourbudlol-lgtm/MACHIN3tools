# Integration proof — Newdrop subscriber PII export Soft residual (#201)

- **When:** 2026-09-08T14:17Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #200` (tip #200 cron ISR; work after #200)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/201
  - branch `peer/factory-hf73-pii-soft-after200`
  - product commit `932986d`
  - merge commit `b97a8ad204f597077d218d08d63302dfb6247cb8` on `main`
- **Needle:** Hard-Fix #73 Soft residual · `docs/ops/PII_EXPORT.md` + SECURITY_AUDIT §21.26 · owner CSV + audit Soft-accepted · PITR/backup/vendor retention Soft · **UI untouched** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **516 passed** EXIT 0
  - `npm run check:controls` — **288 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (ops Soft residual only; no UI chrome / skip dogfood)
- **Next step:** leave Active **Newdrop tip-cover after #201**
