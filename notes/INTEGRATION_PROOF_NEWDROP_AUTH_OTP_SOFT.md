# Integration proof — Newdrop Auth OTP Soft residual (#191)

- **When:** 2026-09-08T12:50Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #189` (tip raced through #190 CI GHA harden Soft; rebased onto #190; worked after #190)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/191
  - branch `peer/factory-hf23-auth-otp-soft-after189`
  - product commit `0359c7c`
  - merge commit `8b422bc7edcfc409fa454a67c352cab6b371fd59` on `main`
- **Needle:** Hard-Fix #23 Soft residual · app `/api/auth/otp` 8/hr/IP + 4/hr/email fail-closed Soft-accepted · Auth dashboard / GoTrue RL operator Soft · `docs/ops/AUTH_OTP.md` · SECURITY_AUDIT §21.7 · Accept “Auth dashboard RL ≤ app RL” still open
- **Native verify (pre-merge, post-rebase on #190):**
  - `npm test` — **502 passed** EXIT 0
  - `npm run check:controls` — **249 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Next step:** leave Active **Newdrop tip-cover after #191**
