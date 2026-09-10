# Integration proof — Newdrop account erasure (#146)

- **Date:** 2026-09-08
- **Assignment:** `[top10] Newdrop production — next meaningful non-UI merge` (after #143/#145 tip → #146)
- **PR:** [#146](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/146) **MERGED** `6e74712`
- **Product:** `7b9b16a` on `peer/factory-hf72-land`
- **Verify:** `npm test` 492 PASS · `check:controls` 162ok · **UI untouched** · NO PAY
- **Needle:** Hard-Fix #72 · `eraseOwnedAccount` + `eraseAccountAction` typed `DELETE` + RL · soft-delete projects · Stripe cancel · Auth `deleteUser` · PITR residual
- **Hard-Fix:** #72
- **Files:** `src/lib/auth/erase-account.ts` · `src/app/dashboard/actions.ts` · service-role max 88
- **Same wave:** [#145](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/145) founding race · [#143](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/143) data-backup retry
- **Next step:** closed — tip after #146; Active after #146 left open
