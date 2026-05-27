# Atlas — Status

- generator: `atlas-indexer/1.0.0 (P0)`
- generated_at: 2026-05-27T05:41:01.952546+00:00
- build_at: 2026-05-27T05:41:02.042731+00:00
- config tier mode: `yaml`
- status: **PASS**

## Indexed

- total: 4404
- by tier: `{"TIER_2_SELECTED": 462, "TIER_1_MIRROR": 3942}`

## Built outputs (rows)

- `RUN_INDEX.jsonl`: 264
- `HANDOFF_INDEX.jsonl`: 156
- `REPORT_INDEX.jsonl`: 195
- `CONTRACT_INDEX.jsonl`: 496
- `WINDOW_INDEX.jsonl`: 25

## Exclude counters (security)

- secret_like_skipped: 274
- db_raw_skipped: 1662
- binary_skipped: 1
- cad_skipped: 6
- protected_root_skipped: 0
- vcs_build_skipped: 0
- read_errors: 0

notes: none

## GDrive Publish (P2) — snapshot

- gdrive publish: **PASS** (2026-05-27)
- gdrive_atlas_root: `G:\내 드라이브\Ariadne Atlas`
- copied: 1261 files (~68.4 MB), 153 handoff zips, 0 security violations
- durable record: `operator/atlas/ATLAS_PUBLISH_STATUS.md`
- github publish: NOT_IMPLEMENTED_BY_DESIGN (next: ATLAS_P3_GITHUB_POINTER_PUBLISHER)
