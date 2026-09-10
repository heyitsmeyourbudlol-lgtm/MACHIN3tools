# Integration proof — Newdrop HTTPS-only Write/MCP static agent docs distribution SoT (#251)

- **When:** 2026-09-09T00:06Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #250`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/251
  - branch `peer/factory-dist-seo-after250`
  - product commit `e5e2730`
  - merge commit `10165f990548800fb81a26b5eb8982ec780652b6` on `main`
- **Needle:** Write `/api/v1/write/me` static docs (`openapi` / `playbook` / `cli` / `packs`) → `marketingHttpsAppUrl` · MCP `newdrop_whoami` playbook → marketing HTTPS SoT · write/MCP API endpoints stay on this-deployment `appUrl()` · extends #245 · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **621 passed** EXIT 0
  - `npm run check:controls` — **488 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (agent docs HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #251**
