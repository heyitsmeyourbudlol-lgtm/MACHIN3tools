# Integration proof — Newdrop Staging Soft residual (#162)

- **When:** 2026-09-08T05:26Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/162
  - branch `peer/factory-hf39-staging-soft-after158`
  - product commit `0f0a33a`
  - merge commit `cd38281` on `main`
  - scrub follow-up [#163](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/163) `e303743`
- **Needle:** Hard-Fix #39 Soft residual · no dedicated staging Supabase · `docs/ops/STAGING.md` · SECURITY_AUDIT §21.12 · never point staging service-role at prod · Accept still open
- **Native verify (tip at merge):**
  - `npm test` — **497 passed** EXIT 0
  - `npm run check:controls` — **178 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Same wave:** [#161](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/161) RL hotpath · [#158](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/158) service-role deep · [#156](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/156) Postgres RL Soft
- **Next step:** closed — Active advanced (tip raced; leave open after current tip)

