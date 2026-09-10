# Integration proof — Newdrop HTTPS-only Write SDK + GitHub Action API base SoT (#260)

- **When:** 2026-09-09T02:00Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #259`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/260
  - branch `peer/factory-dist-seo-after259`
  - product commit `dd74ecae31054667a97ce89b56da9693d2114c9d`
  - merge commit `9a1a208267bc0fea68e85072e355595c5590b48a` on `main`
- **Needle:** Write SDK `baseUrl` → `resolveHttpsApiBase` fail-closed · GitHub Action `api_url` HTTPS-only before CLI curl · extends #259 CLI SoT · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **653 passed** EXIT 0
  - `npm run check:controls` — **512 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #260**
