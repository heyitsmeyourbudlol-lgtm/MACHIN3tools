# Integration proof — Newdrop branch protection Soft residual (#188)

- **When:** 2026-09-08T12:41Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #187` (tip had advanced past #186 via race #187 Soft #25)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/188
  - branch `peer/factory-hf83-branch-protection-soft-after187`
  - product commit `120e8cf`
  - merge commit `3d748b8b9f8a58e76268c8b89e88760893aa2988` on `main`
- **Needle:** `docs/ops/BRANCH_PROTECTION.md` · SECURITY_AUDIT §21.3 Soft residual · AGENT_WORKFLOW Soft residual · Actions job `test` soft gate · never open repo public
- **Hard-Fix:** #83 (Soft residual; classic protection / required checks deferred until GitHub Pro/Team)
- **Native verify:**
  - `npm test` — **501 passed** EXIT 0
  - `npm run check:controls` — **238 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY** · **0016 not applied**
- **Residual:** Enable required checks on `main` when GitHub Pro/Team is available; flip BRANCH_PROTECTION.md to Live
