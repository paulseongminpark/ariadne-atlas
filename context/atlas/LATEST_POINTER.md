# Ariadne Atlas Latest Pointer

generated_at: 2026-05-28T00:55:18.4368341Z
stale_after: 2026-05-28T01:25:18.4368341Z
atlas_version: ATLAS_P4_SCHEDULED_PUBLISH
freshness_status: FRESH

## Source Of Truth

Ariadne Window and Ariadne private runtime/control-plane records remain the source of truth. Atlas is a generated public evidence map and scheduled external re-entry layer.

## First Links For Web AI

1. Live Window status: https://ariadne-window.paulseongminpark.workers.dev/status
2. Live Window health: https://ariadne-window.paulseongminpark.workers.dev/health
3. Live Window state: https://ariadne-window.paulseongminpark.workers.dev/state/current
4. Public latest pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
5. Public current state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
6. Public Window endpoint guide: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/WINDOW_ENDPOINT.md
7. Public Atlas status: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/ATLAS_STATUS.md

## Stable Window Endpoint

- stable_window_endpoint: https://ariadne-window.paulseongminpark.workers.dev
- window_state_endpoint: https://ariadne-window.paulseongminpark.workers.dev/state/current
- remote_mcp_endpoint: https://ariadne-window.paulseongminpark.workers.dev/mcp
- mcp_protocol_versions: 2025-03-26, 2025-06-18
- window_health: ok
- window_state_generated_at: 2026-05-27T09:34:20.553922+00:00
- window_state_age: 15.3 hours old

## Public Atlas Raw URLs

- latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- window_endpoint: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/WINDOW_ENDPOINT.md
- atlas_status: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/ATLAS_STATUS.md
- next_actions: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/NEXT_ACTIONS.md
- run_index: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/RUN_INDEX.jsonl
- handoff_index: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/HANDOFF_INDEX.jsonl
- report_index: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/REPORT_INDEX.jsonl
- contract_index: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CONTRACT_INDEX.jsonl
- window_index: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/WINDOW_INDEX.jsonl

## GDrive Atlas

- gdrive_atlas_root: G:\내 드라이브\Ariadne Atlas
- pointer_folder: G:\내 드라이브\Ariadne Atlas\00_POINTERS
- index_folder: G:\내 드라이브\Ariadne Atlas\06_INDEX
- handoff_archive_folder: G:\내 드라이브\Ariadne Atlas\02_HANDOFFS
- gdrive_handoff_zip_count: 188
- note: GDrive contains bulk evidence. GitHub contains only small pointers and indexes.

## Latest Scheduled Publication

- scheduled_task: AriadneAtlasScheduledPublish
- latest_publication_run: ATLAS_P4_SCHEDULED_PUBLISH
- latest_scheduled_status_json: ariadne:/operator/atlas/public/ATLAS_SCHEDULE_STATUS.json
- latest_FINAL_REPORT_reference: ariadne:/harness/runs/ATLAS_P4_SCHEDULED_PUBLISH/FINAL_REPORT.md
- latest_NEXT_PACKET_RECOMMENDATION: ATLAS_P5_WINDOW_INTEGRATION

## Latest Indexed Evidence

- indexed_latest_run_id: ATLAS_P2_GDRIVE_PUBLISHER
- indexed_latest_final_report: harness/runs/ATLAS_P2_GDRIVE_PUBLISHER/FINAL_REPORT.md
- indexed_latest_report_status: PASS_STRONG
- indexed_latest_handoff_zip: harness/runs/CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX/handoff/CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX_handoff.zip
- indexed_latest_handoff_name: CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX_handoff.zip

## Recommended Read Order

1. Read Window /status and /health.
2. Read Window /state/current.
3. Read this file for latest routing and publication status.
4. Read CURRENT_STATE.md for dense operating-state summary.
5. Use JSONL indexes to locate specific evidence.
6. Use GDrive Atlas only for bulk handoff/report evidence.

## Known Warnings

- Scheduled publish is gated by script safety checks before commit/push.
- Postgres row-level projection remains limited when PG connection variables are absent.
- Public indexes are filtered when labels are unsuitable for public pointer publication.
- Atlas is generated and must not be treated as canonical state.

## Next Action

Run ATLAS_P5_WINDOW_INTEGRATION after the scheduled task has run at least one unattended cycle.
