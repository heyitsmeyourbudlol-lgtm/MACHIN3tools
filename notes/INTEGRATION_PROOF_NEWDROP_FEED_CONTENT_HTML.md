# Integration proof — Newdrop feed content_html + RSS content:encoded (#221)

- **When:** 2026-09-08T21:17Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #220`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/221
  - branch `peer/factory-dist-seo-after220`
  - product commit `9121fe6`
  - merge commit `37eb43a57ee7c84fdd7ec125c7be4c16cd3d6c79` on `main`
- **Needle:** `feedItemContentHtml` / `buildRssContentEncoded` · JSON Feed 1.1 `content_html` + RSS `content:encoded` (`xmlns:content`) via Hard-Fix #61 `resolveUpdateBodyHtml` · empty post-sanitize omit (fail-closed) · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **576 passed** EXIT 0
  - `npm run check:controls` — **370 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed HTML bodies only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #221**
