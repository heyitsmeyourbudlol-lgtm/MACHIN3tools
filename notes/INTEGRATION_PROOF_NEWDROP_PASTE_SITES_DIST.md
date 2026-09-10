# Integration proof — Newdrop paste-sites + embed MIME distribution (#291)

- **When:** 2026-09-09T05:53Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #290` (retarget after tip race #290)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/291
  - branch `peer/factory-paste-sites-after289-20260909T054858Z` (rebased onto #290)
  - product commit `a731c4ce`
  - merge commit `6a7240e48c7d284ad71856755a32fc284ed7f9a2` on `main`
- **Needle:** `llms.txt` + marketing sitemap + robots Allow pin `/install/paste-sites.md` (Framer/Webflow/WordPress paste guide) · carve-out from #290: install capability X-Robots-Tag + no-referrer match base64url tokens only (`[A-Za-z0-9_-]+`) so public `.md` stays crawlable while `/install/` Disallow still covers pack tokens · cookieless CORS `*` + typed markdown for paste-sites · `/embed.js` + `/embed.v2.js` fail-closed `Content-Type: text/javascript` · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only** · **does not duplicate #290**
- **Native verify (pre-merge):**
  - `npm test` — **743 passed** EXIT 0
  - `npm run check:controls` — **542 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution SEO crawl + embed MIME only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #291**
