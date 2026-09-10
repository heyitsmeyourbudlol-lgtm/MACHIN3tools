# Integration proof — Newdrop service-role blast radius residual (#153)

- **When:** 2026-09-08T05:20Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop production — next meaningful non-UI merge` (after #112 → tip advanced; writeback tip #153)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/153
  - branch `peer/factory-hf97-after146`
  - product commit `dc0d340`
  - merge commit `abc1e86b723f1466b8a77fd281d8dc1a57938c80` on `main`
- **Needle:** Stripe webhook auto-refund reuses POST admin client · `loadOpsOverview` shared admin (−4 sites) · `check:service-role` max 84
- **Hard-Fix:** #97 residual (service-role blast radius)
- **Native verify (tip):**
  - `npm test` — **495 passed** EXIT 0
  - `npm run check:controls` — **167 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Next step:** closed — tip after #153; Active after #153 open
