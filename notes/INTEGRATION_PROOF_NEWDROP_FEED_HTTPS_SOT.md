# Integration proof — Newdrop feed HTTPS-only SoT canonical (#242)

- **When:** 2026-09-08T23:14Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #241`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/242
  - branch `peer/factory-dist-seo-after241`
  - product commit `2ae5c48`
  - merge commit `59f9e8728cdbdcdcbcd08fd40c06fe57d1f54d84` on `main`
- **Needle:** `feedHttpsSoTUrl` · RSS + JSON Feed SoT **308** only when target is **https:** · `Link: rel=canonical` omitted for non-HTTPS SoT (local `http://` keeps self/alternate) · never cleartext/localhost downgrade from `NEXT_PUBLIC_APP_URL` misconfig · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core**
- **Native verify (pre-merge):**
  - `npm test` — **603 passed** EXIT 0
  - `npm run check:controls` — **453 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (HTTPS SoT gate only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #242**
