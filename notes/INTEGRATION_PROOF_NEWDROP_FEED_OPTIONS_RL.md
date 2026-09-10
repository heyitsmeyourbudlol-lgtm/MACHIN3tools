# Integration proof — Newdrop feed early OPTIONS rate-limit + canonical query 308 (#238)

- **When:** 2026-09-08T22:53Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #237`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/238
  - branch `peer/factory-dist-seo-after237`
  - product commit `7713ec1`
  - merge commit `3ab6b6ca3273527e4828fd3cd03c9d6b2a057317` on `main`
- **Needle:** `Early feed OPTIONS rate-limit (before slug RPC)` · same GET bucket `failClosed: true` · `feedHasDisallowedQuery` / `feedCanonicalRequestUrl` · GET query → **308** pathname-only · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **599 passed** EXIT 0
  - `npm run check:controls` — **438 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (OPTIONS RL + canonical 308 only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #238**
