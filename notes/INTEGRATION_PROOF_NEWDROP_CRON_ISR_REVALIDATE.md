# Integration proof — Newdrop cron / scheduled publish ISR revalidate (#200)

- **When:** 2026-09-08T13:17Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #199`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/200
  - branch `peer/factory-cron-isr-revalidate-after199`
  - product commit `f4a4aa3`
  - merge commit `e15d34f39ab06b87d21126bffd620521cfc55d21` on `main`
- **Needle:** `publishDueScheduledUpdates` → `revalidatePublicChangelogSurfaces` · HTML + RSS + `/feed.json` ISR bust on Hobby cron nests + dashboard opportunistic flush · #198 Write/GitHub/MCP parity · `check:controls` pin · **UI untouched** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **516 passed** EXIT 0
  - `npm run check:controls` — **285 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (backend ISR parity; no UI chrome / skip dogfood)
- **Next step:** leave Active **Newdrop tip-cover after #200**
