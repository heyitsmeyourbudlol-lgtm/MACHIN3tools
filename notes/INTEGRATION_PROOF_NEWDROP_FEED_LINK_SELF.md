# Integration proof — Newdrop feed Link rel=self discovery (#217)

- **When:** 2026-09-08T20:52Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #216`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/217
  - branch `peer/factory-dist-seo-after216`
  - product commit `888c8d1`
  - merge commit `18ed73402c27a8d21fd0a15ff0d71fd64b0b6050` on `main`
- **Needle:** `feedSelfLinkHeader` / `feedDiscoveryLinkHeader` · public RSS + JSON Feed RFC 8288 **`Link: rel=self`** + **`rel=alternate`** (incl. **304**) · empty href fail-closed omit Link · HTTP-layer parity with `atom:link rel="self"` / JSON Feed `feed_url` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **559 passed** EXIT 0
  - `npm run check:controls` — **347 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed headers only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #217**
