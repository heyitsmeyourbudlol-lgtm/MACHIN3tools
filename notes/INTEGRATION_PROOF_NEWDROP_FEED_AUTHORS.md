# Integration proof — Newdrop feed authors + RSS attribution (#220)

- **When:** 2026-09-08T21:11Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #219`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/220
  - branch `peer/factory-dist-seo-after219`
  - product commit `df4748f`
  - merge commit `e84e16047367e5fa83f36bf6a16c1a7d66fa8659` on `main`
- **Needle:** `feedJsonAuthors` / `feedChannelCopyright` / `feedChannelWebMaster` / `FEED_RSS_DOCS_URL` · JSON Feed 1.1 `authors` + RSS `<docs>`/`<copyright>`/`<webMaster>` · dogfood name dedupe · control-char strip · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **570 passed** EXIT 0
  - `npm run check:controls` — **366 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed attribution only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #220**
