# Integration proof — Newdrop HTTPS-only publicChangelog SoT + security.txt (#244)

- **When:** 2026-09-08T23:26Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #243`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/244
  - branch `peer/factory-dist-seo-after243`
  - product commit `45e1d80`
  - merge commit `847d7556f942c5b00d3bba7865059991c0727a4e` on `main`
- **Needle:** `publicChangelogUrl` → `marketingHttpsAppUrl` (feed body / notify SoT) · `security.txt` Canonical/Policy HTTPS-only · `feedRssDcIdentifier` + `feedJsonAuthors` HTTPS-only · extends #243 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **609 passed** EXIT 0
  - `npm run check:controls` — **462 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (HTTPS SoT gates only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #244**
