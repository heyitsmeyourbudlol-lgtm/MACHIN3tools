# Integration proof — Newdrop feed Link alternate + ttl + XML Char (#212)

- **When:** 2026-09-08T20:30Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #211`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/212
  - branch `peer/factory-dist-seo-link-ttl-after211`
  - product commit `52c8ff2`
  - merge commit `b35a3fd88dae1720e036b0f7a84f8a9ce15b0cee` on `main`
- **Needle:** RFC 8288 mutual `Link: rel=alternate` (RSS↔JSON Feed) · RSS `<ttl>1</ttl>` · `stripIllegalXmlChars` fail-closed · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **541 passed** EXIT 0
  - `npm run check:controls` — **324 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed headers/payload only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #212**
