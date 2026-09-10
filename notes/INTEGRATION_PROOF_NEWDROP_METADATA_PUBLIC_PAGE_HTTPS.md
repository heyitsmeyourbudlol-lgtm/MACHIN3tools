# Integration proof — Newdrop HTTPS-only metadataBase + Write/MCP public_page SoT (#245)

- **When:** 2026-09-08T23:35Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #244`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/245
  - branch `peer/factory-dist-seo-after244`
  - product commit `fec3487`
  - merge commit `83798ed4ece30f62d005d326b02c810370f7d2ae` on `main`
- **Needle:** root `metadataBase` / Open Graph → `marketingHttpsAppUrl` · Write API + MCP `public_page` / RSS / JSON Feed → `publicChangelog*` HTTPS SoT · extends #243/#244 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **611 passed** EXIT 0
  - `npm run check:controls` — **467 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (HTTPS SoT / metadata gates only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #245**
