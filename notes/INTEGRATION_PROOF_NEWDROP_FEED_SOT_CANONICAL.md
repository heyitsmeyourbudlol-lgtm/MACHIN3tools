# Integration proof — Newdrop feed SoT canonical + rel=canonical (#241)

- **When:** 2026-09-08T23:08Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #240`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/241
  - branch `peer/factory-dist-seo-after240`
  - product commit `660daa9`
  - merge commit `d15911f183a38e7783a3a0617b838611f2330fe3` on `main`
- **Needle:** After resolve, RSS + JSON Feed **308** to `publicChangelog*` SoT host/path when request Host/path drifts or query remains · discovery `Link` adds **`rel=canonical`** · password **`Vary: Cookie`** · `feedNeedsSoTCanonicalRedirect` / `feedCanonicalLinkHeader` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **602 passed** EXIT 0
  - `npm run check:controls` — **450 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (canonical 308 + Link + Vary only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #241**
