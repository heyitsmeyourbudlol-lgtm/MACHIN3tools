# Integration proof — Newdrop HTTPS-only auth confirm/signout + legacy email 308 + proxy hostname SoT (#256)

- **When:** 2026-09-09T00:34Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #255`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/256
  - branch `peer/factory-dist-seo-after255`
  - product commit `fb7927a`
  - merge commit `635fe5029fa5b45758fc2cb453593c789539eda8` on `main`
- **Needle:** `/auth/confirm` + `/auth/signout` Locations + legacy `/api/email/confirm` + `/api/email/unsubscribe` 308 + proxy `appHostname` → `marketingHttpsAppUrl` · extends #254–#255 auth redirect HTTPS SoT · `check:controls` pins · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **633 passed** EXIT 0
  - `npm run check:controls` — **504 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (distribution HTTPS SoT only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #256**
