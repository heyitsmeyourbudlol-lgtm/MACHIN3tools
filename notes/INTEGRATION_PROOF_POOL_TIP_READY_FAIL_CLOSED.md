# Integration proof — pool tip_ready fail-closed

Needle: `OVERSEER_POOL_READY_FAIL_CLOSED_TIP_2026_09_08`  
Date: 2026-09-08 · NO PAY · flaw-scan Factory Engineer upgrade

## What

`pool_ready` no longer means “floor dirs exist.” When FS HEADs are readable and any pool slot is `HEAD≠hub`, inventory + `ensure-pool` report `tip_ready=false` / `pool_skew`.

## Evidence

- `scripts/peer_worktree.py` · `pool_tip_skew_report` + inventory + CLI warn
- Live: `./scripts/peer ensure-pool` → `warn: pool_skew head≠hub=8 matched=0` · `tip_ready=false`
- Unittest: `tests.test_pool_ready_fail_closed_tip` (2 OK) + inventory TTL suite still green

## Non-goals

- Does not hard-reset dirty WIP (continue_on_dirty)
- Does not invent Active porcelain→0 theater
