# Integration proof — Newdrop Soft Soft tip-stamp #56 schedule timezone / DST

- **When:** 2026-09-09T01:49Z (Mac hub agent Soft Soft tip-stamp)
- **Product:** CaaS / Newdrop Soft Soft residual Hard-Fix #56
- **Soft Soft land:** `0cf901f9` (CLEAN Soft Soft — `peer/soft-hf56-schedule-tz-20260908T155557`)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/258
  - branch `peer/soft-tip-hf56-schedule-tz-20260909T014757Z`
  - product commit `157a6a2c0fee39a7642420e30fb92806a8706050`
  - merge commit `953684541053df5926b3d5230bbb4311abadca60` on `main`
- **Ship:** `scheduleInputHasExplicitOffset` + `parseScheduleWhen` reject bare `datetime-local` (no `Z`/`±HH:MM`) · Soft Soft alias `hasExplicitUtcOrOffset` (Soft controls pin) · `docs/ops/SCHEDULE_TIMEZONE_DST.md` · SECURITY_AUDIT §21.50 · HARD_FIXES Soft Soft stamp · `schedule-timezone-dst-soft.test.ts` + schedule-time tests
- **Gate:** npm test **643** · `check:controls` **507ok** · Soft Soft pin 4ok · schedule-time tests ok
- **UI:** untouched · **NO PAY** · **0016 not applied**
- **Needle:** Soft Soft residual = Hard Accept when browser IANA TZ captured at schedule time + DST does not shift local intent + PR merge
- **Hub writeback:** Soft Soft tip-stamp #56 Active `[x]` · EXTERNAL_PROOF + FACTORY_PROOF + scoreboard · tip-cover → after #258
