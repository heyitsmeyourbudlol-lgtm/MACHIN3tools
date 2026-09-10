# Integration proof — Newdrop HTTPS-only email brand + changelog + feed favicon SoT (#246)

- **When:** 2026-09-08T23:38Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #245`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/246
  - branch `peer/factory-dist-seo-after245`
  - product commit `e147b8d`
  - merge commit `f8297d5f5c52c70d712cc25d652ed0b88a2bdd5e` on `main`
- **Needle:** email brand home / trial docs / `sendUpdateEmail` What’s New fallback → `marketingHttpsAppUrl` / `publicChangelogUrl` · RSS/JSON Feed platform favicon → `marketingHttpsAppUrl()` · extends #243–#245 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **613 passed** EXIT 0
  - `npm run check:controls` — **471 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (email/feed HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #246**
