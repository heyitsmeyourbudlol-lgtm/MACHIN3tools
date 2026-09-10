# Integration proof — Newdrop publish-scheduled notify-ledger retry

- **Date:** 2026-09-08
- **Assignment:** `[top10] Newdrop production — next meaningful non-UI merge` (past tip #149/#148)
- **PR:** [#150](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/150) merge `0f2d7ae` · branch `peer/factory-hf53-publish-retry-after145` · product `18a99af`
- **Verify:** `npm test` 493 · `check:controls` 161ok · **UI untouched** · NO PAY
- **Needle:** Hard-Fix #53 residual · `/api/cron/publish-scheduled` nests `retryFailedNotificationDeliveries` after primary 05:00 UTC drain · Hobby notify-retry now covers purge / data-backup / publish / billing / clone-spike
- **Hub:** EXTERNAL_PROOF + FACTORY_PROOF + scoreboard writeback
