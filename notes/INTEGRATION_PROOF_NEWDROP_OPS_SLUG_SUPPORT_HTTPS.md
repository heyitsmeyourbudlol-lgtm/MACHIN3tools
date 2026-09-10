# Integration proof — Newdrop HTTPS-only ops slug-change + support-handoff distribution SoT (#249)

- **When:** 2026-09-08T23:56Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #248`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/249
  - branch `peer/factory-dist-seo-after248`
  - product commit `a6a2fd4`
  - merge commit `abb6a21281c18fa0edf5a17f574d2ef6410d555d` on `main`
- **Needle:** ops slug-change review tokens + customer `/c/{slug}` cites in decision emails → `marketingHttpsAppUrl` · ops support-handoff review URLs → marketing HTTPS SoT · extends #248 ops HTTPS SoT · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **619 passed** EXIT 0
  - `npm run check:controls` — **483 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (ops HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #249**
