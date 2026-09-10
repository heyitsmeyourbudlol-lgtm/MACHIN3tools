# Integration proof — Newdrop Schedule UTC Soft (#166)

- **When:** 2026-09-08T05:28Z
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop production — next meaningful non-UI merge` (after #148 tip race → after #163)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/166
  - branch `peer/factory-hf56-hf72-after158`
  - product commit `c0bbfc5`
  - merge commit `1081605` on `main`
- **Needle:** Hard-Fix #56 Soft · `hasExplicitUtcOrOffset` + `parseScheduleWhen` reject bare datetime-local · restore #72 `check:controls` · SECURITY_AUDIT §21.13
- **Native verify (pre-merge):**
  - `npm test` — **501 passed** EXIT 0
  - `npm run check:controls` — **186 ok · 0 fail** EXIT 0
  - schedule-time unit — **10 passed**
- **UI:** untouched · **NO PAY**
- **Next step:** closed — leave Active after #166 open
