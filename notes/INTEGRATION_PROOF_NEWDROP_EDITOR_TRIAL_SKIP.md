# Integration proof — Newdrop invite-only editor trial skip (#35)

- **Date:** 2026-09-08
- **PR:** [#155](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/155) **MERGED**
- **Merge SHA:** `ae05cc0`
- **Hard-Fix:** #35
- **Needle:** `ensureAccountProvisioned` skips empty personal trial when active `account_members`; `force: true` on createProject + Billing
- **Verify:**
  - `npm test` — **497 passed**
  - `npm run check:controls` — **171 ok · 0 fail** EXIT 0
- **UI untouched** · **NO PAY**
