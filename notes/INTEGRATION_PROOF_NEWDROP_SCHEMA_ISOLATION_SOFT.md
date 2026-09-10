# Integration proof — Newdrop Schema isolation Soft residual (#173)

- **When:** 2026-09-08T11:10Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/173
  - branch `peer/factory-hf38-schema-soft-after172`
  - product commit `97c797c`
  - merge commit `e62032d` on `main`
- **Needle:** Hard-Fix #38 Soft residual · `0016_schema_isolation_security` unrehearsed until staging (#39 Soft) · omit `SUPABASE_DB_SCHEMA=prod` · `docs/ops/STAGING.md` · SECURITY_AUDIT §21.12 · AGENT_WORKFLOW · Accept still open
- **Native verify (tip at merge):**
  - `npm test` — **501 passed** EXIT 0
  - `npm run check:controls` — **203 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY** · **migration not applied**
- **Same wave:** [#172](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/172) service-role · [#171](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/171) cover Soft · [#162](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/162) Staging Soft
- **Next step:** leave Active tip-cover after #173
