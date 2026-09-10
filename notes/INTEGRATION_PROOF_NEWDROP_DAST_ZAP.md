# Integration proof — Newdrop DAST ZAP baseline schedule (#134)

- **When:** 2026-09-08T05:01Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop production — next meaningful non-UI merge` (after #111 → tip raced to #137 → land #134)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/134
  - branch `peer/factory-hf84-dast-after129`
  - product commit `36739bd052596bda460837b1d17848e39f1d6c31`
  - merge commit `30df05bc3c01d042c96a5b68205fb2b3bf8578f9` on `main`
- **Needle:** Hard-Fix #84 · `.github/workflows/dast-zap.yml` weekly/manual ZAP baseline · skips without `DAST_TARGET_URL` · `docs/ops/DAST.md`
- **Native verify (pre-merge tip):**
  - `npm test` — **475 passed** EXIT 0
  - `npm run check:controls` — **143 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Same wave:** [#137](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/137) session revoke · [#135](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/135) PII export · [#131](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/131) clone notify retry · [#110](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/110)/[#111](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/111) editor notify + obs alerts
- **Next step:** closed — leave Active after #134 open
