# Integration proof — Newdrop HTTPS-only marketing crawl + feed discovery Link (#243)

- **When:** 2026-09-08T23:20Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #242`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/243
  - branch `peer/factory-dist-seo-after242`
  - product commit `558d8ff`
  - merge commit `ff99b76a2dd730274bb250438ec0730b49cc8816` on `main`
- **Needle:** `marketingHttpsAppUrl` · sitemap / robots / llms.txt HTTPS-only crawl base (fallback `https://getnewdrop.com`) · feed discovery `Link` self/alternate/HTML require `feedHttpsSoTUrl` (omit entire header on cleartext) · extends #242 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **606 passed** EXIT 0
  - `npm run check:controls` — **458 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (HTTPS crawl gates only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #243**
