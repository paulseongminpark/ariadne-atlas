# Ariadne Atlas Latest Pointer

generated_at: 2026-07-06T04:55:16.3847114Z
stale_after: 2026-07-06T05:25:16.3847114Z
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
- window_state_generated_at: 2026-07-06T04:50:01.797612+00:00
- window_state_age: 0.1 hours old

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

- gdrive_atlas_root: C:\Users\PAUL\내 드라이브\Ariadne Atlas
- pointer_folder: C:\Users\PAUL\내 드라이브\Ariadne Atlas\00_POINTERS
- index_folder: C:\Users\PAUL\내 드라이브\Ariadne Atlas\06_INDEX
- handoff_archive_folder: C:\Users\PAUL\내 드라이브\Ariadne Atlas\02_HANDOFFS
- gdrive_handoff_zip_count: 264
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
- indexed_latest_report_status: PASS_WITH_DEFERRAL
- indexed_latest_handoff_zip: harness/runs/RUN-003_LAB2_knowledge_pack_20260615.zip
- indexed_latest_handoff_name: RUN-003_LAB2_knowledge_pack_20260615.zip

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
