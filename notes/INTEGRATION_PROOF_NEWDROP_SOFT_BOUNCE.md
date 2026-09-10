# Integration proof — Newdrop soft-bounce suppress guard (#148)

- **PR:** [#148](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/148) merge `d210081` · product `b4d5f48`
- **Follow-up scrub:** [#149](https://github.com/heyitsmeyourbudlol-lgtm/caas-changelog/pull/149) merge `f22f5fc` (CHANGELOG/AGENT_MEMORY markers)
- **Verify:** `npm test` 487 · `check:controls` 156ok (tip scrub 164ok) · **UI untouched** · NO PAY
- **Needle:** Hard-Fix #57 residual — Permanent/hard `email.bounced` + complaint suppress; Transient/soft → `ignored: soft_bounce`
- **Paths:** `src/lib/email/resend-webhook.ts` (`isPermanentBounceType`) · `src/app/api/webhooks/resend/route.ts`
