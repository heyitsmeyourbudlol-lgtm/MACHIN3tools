# Integration proof — Newdrop feed plain-text summary + content_text (#222)

- **When:** 2026-09-08T21:22Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #221`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/222
  - branch `peer/factory-dist-seo-after221`
  - product commit `a9e0b5d`
  - merge commit `45514ea1464ec35402ed7781c1e73cec8e6abf02` on `main`
- **Needle:** `feedItemContentText` / `feedItemSummary` / `htmlToFeedPlainText` · JSON Feed `content_text` + optional `summary` + RSS `<description>` from sanitized HTML (Hard-Fix #61) · HTML-only posts non-empty · truncate 500/280 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **580 passed** EXIT 0
  - `npm run check:controls` — **375 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (feed plain-text fields only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #222**
