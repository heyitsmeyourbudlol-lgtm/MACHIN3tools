# Integration proof — Newdrop Postgres RL Soft residual (#156)

- **When:** 2026-09-08T05:22Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop production — next meaningful non-UI merge` (after #155 → #156; tip raced through #142→#155)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/156
  - branch `peer/factory-hf64-rl-after155`
  - product commit `a20ef1f`
  - merge commit `a20ef1f` on `main`
- **Needle:** Hard-Fix #64 · Soft residual · Postgres `consume_rate_limit` + failClosed · `docs/ops/RATE_LIMIT.md` · SECURITY_AUDIT §21.11 · Redis/Upstash deferred until abuse/ARR
- **Native verify (pre-merge tip):**
  - `npm test` — **495 passed** EXIT 0
  - `npm run check:controls` — **175 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Same wave:** [#155](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/155) editor trial · [#153](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/153) service-role · [#151](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/151) CDN/WAF
- **Next step:** closed — leave Active after #156 open
