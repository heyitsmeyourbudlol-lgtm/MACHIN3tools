# Integration proof — Newdrop CI GHA harden Soft residual (#190)

- **When:** 2026-09-08T12:48Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #188` / Active after #189 (tip raced #189 CORS Soft; worked after #189)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/190
  - branch `peer/factory-ci-gha-harden-after189`
  - product commit `15c9c82`
  - merge commit `531e34f9b7d75689b786b14fb08a1fee0422bd7a` on `main`
- **Needle:** Hard-Fix #83/#84 CI harden Soft · workflow `permissions: contents: read` · checkout `persist-credentials: false` · actions `@v5` (CI/CodeQL/Semgrep) · `verifyGithubSignature` empty-secret fail-closed · BRANCH_PROTECTION + SECURITY_AUDIT §21.3/§21.4 · classic branch protection still Soft until Pro
- **Native verify (pre-merge):**
  - `npm test` — **502 passed** EXIT 0
  - `npm run check:controls` — **247 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Next step:** leave Active **Newdrop tip-cover after #190** — Soft floor thinning; prefer real code / product distribution over empty Wave-7 Soft docs
