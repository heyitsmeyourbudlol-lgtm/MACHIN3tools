# INTEGRATION_PROOF — metric_snapshot live git_head

Needle: `OVERSEER_METRIC_SNAP_LIVE_GIT_HEAD_2026_09_08`

## Bug

`peer_oversight_events.metric_snapshot` copied `last_cycle.git_head` only.
Self-heal rehydrate / thin last_cycle often omit `git_head` → oversight snaps
stored `git_head=""` forever. HEAD-stall detection stayed blind (comparable
SHA empty) while WORKING agents looked “unchanged” in theater scores that
still mixed with verify FAIL / tests hold.

## Fix

When last_cycle lacks a comparable SHA (`_comparable_git_head`), fill from
live `peer_transcript.git_head_oneline()`.

## Proof

- Unittest: `PeerLoopTests.test_metric_snapshot_live_git_head_needle`
- Unittest: `OverseerStagActiveFpTests.test_metric_snapshot_live_git_head_when_last_cycle_blank`
- `./scripts/peer test-quick` → 218 OK (2026-09-08)
- EXPECTED pin: `scripts/EXPECTED_peer_oversight_events.py.md5`

## Related

Linux mtime event watch: `OVERSEER_LINUX_MTIME_EVENT_WATCH_2026_09_08`
(`PeerEventWatcher._setup_mtime` + signal-wake unittest).
