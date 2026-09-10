# Integration proof — Newdrop custom Auth domain residual (#142)

- **When:** 2026-09-08T05:07Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop production — next meaningful non-UI merge` (after #97; tip advanced through #140 before land)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/142
  - branch `peer/factory-hf25-land2`
  - product commit `27bf676`
  - merge commit `187dcf441a92cbf6098532ec019efcb091a87acc` on `main`
- **Needle:** Hard-Fix #25 · Auth stays on Supabase host until Wave 7 / material ARR · SECURITY_AUDIT §21.9 + AGENT_WORKFLOW checklist · `check:controls` pins
- **Native verify (pre-merge tip):**
  - `npm run check:controls` — **151 ok · 0 fail** EXIT 0
  - prior wave `npm test` — **470 passed** (HF25 docs-only; suite green on tip)
- **UI:** untouched · **NO PAY**
- **Same wave:** [#140](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/140) Resend bounce · [#138](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/138) billing notify retry · [#129](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/129) service-role #97
- **Next step:** closed — leave Active after #142 open
