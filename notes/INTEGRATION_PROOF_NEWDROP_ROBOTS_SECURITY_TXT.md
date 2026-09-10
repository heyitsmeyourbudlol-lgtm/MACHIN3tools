# Integration proof — Newdrop robots + security.txt distribution (#194)

- **When:** 2026-09-08T12:58Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #193` (tip was HIBP Soft #193; landed distribution crawl pins as #194)
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/194
  - branch `peer/factory-robots-security-dist-after193`
  - product commit `fa23c90`
  - merge commit `dfdeab26f821e7fe5136b5550784802d1c1b4cb7` on `main`
- **Needle:** robots Allow pins for `/llms.txt` + `/.well-known/security.txt` + first-party dogfood HTML/RSS · security.txt in sitemap · `buildSecurityTxt` + Vitest · `check:controls` pins · customer `/c/{slug}` never auto-indexed · **UI untouched** · **NO PAY**
- **Native verify (pre-merge):**
  - `npm test` — **511 passed** EXIT 0
  - `npm run check:controls` — **263 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (robots/security.txt/sitemap; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #194**
