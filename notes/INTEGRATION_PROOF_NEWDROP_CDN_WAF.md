# Integration proof — Newdrop CDN/WAF Soft residual (#151)

- **When:** 2026-09-08T05:18Z (Mac hub agent verify)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop production — next meaningful non-UI merge` (after #142 tip-raced through #150 → #151)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/151
  - branch `peer/factory-hf63-waf-after146`
  - product commit `e0784c8`
  - merge commit `ca0fff940310c06e4e297b6096d01966a641a9ae` on `main`
- **Needle:** Hard-Fix #63 · Soft residual · Vercel edge + app Postgres RL today · `docs/ops/CDN_WAF.md` Cloudflare cutover · SECURITY_AUDIT §21.10 · edge WAF live deferred
- **Native verify (pre-merge tip):**
  - `npm test` — **495 passed** EXIT 0
  - `npm run check:controls` — **166 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Next step:** closed — leave Active after #151 open
