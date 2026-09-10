# Integration proof — Newdrop ops handoff capability-URL noindex (#299)

- **When:** 2026-09-09T06:10Z (Mac hub agent)
- **Repo:** Newdrop (CaaS) @ `/Users/togi/CaaS`
- **Assignment:** `[top10] Newdrop tip-cover after #297`
- **Irreversible artifact:** merged PR https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/299
  - branch `peer/factory-ops-capurl-noindex-after297-20260909T060900Z`
  - product commit `ab114d53`
  - merge commit `547a50497eb8ba2ab65efb63a04ad8fe7adbab5e` on `main`
- **Needle:** `CAPABILITY_URL_NOINDEX_SOURCES` + `/ops/support/:path*` + `/ops/slug-change/:path*` → HTTP `X-Robots-Tag: noindex, nofollow` (parity #290 preview/install; revive closed unmerged #296 onto tip #297; does not widen `/ops/:path*`; does not duplicate #297 CORP) · `check:controls` pin · **UI untouched** · **0016 not applied** · **NO PAY** · **not Wave-7 Soft docs** · **not thin Dublin Core-only**
- **Native verify (pre-merge):**
  - `npm test` — **752 passed** EXIT 0
  - `npm run check:controls` — **555 ok · 0 fail** EXIT 0
- **UI:** untouched · **NO PAY**
- **Deploy:** push to `main` via Git → Vercel (ops handoff X-Robots-Tag only; no UI chrome)
- **Next step:** leave Active **Newdrop tip-cover after #299**
