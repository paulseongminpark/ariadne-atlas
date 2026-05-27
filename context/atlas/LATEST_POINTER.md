# Ariadne Atlas Latest Pointer

generated_at: 2026-05-27T08:46:37.1571127Z
stale_after: 2026-05-28T08:46:37.1591988Z
atlas_version: ATLAS_P3E_PUBLIC_POINTER_QUALITY_2026-05-27
freshness_status: FRESH

## Source Of Truth

Ariadne Window and Ariadne private runtime/control-plane records remain the source of truth. Atlas is a generated public evidence map and re-entry layer.

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
- window_state_generated_at: 2026-05-26T09:45:32.379652+00:00
- window_state_age: 23.0 hours old

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
- gdrive_handoff_zip_count: 153
- note: GDrive contains bulk evidence. GitHub contains only small pointers and indexes.

## Latest Publication Run

- latest_run_id: ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION
- latest_FINAL_REPORT: ariadne:/harness/runs/ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION/FINAL_REPORT.md
- latest_handoff_zip_reference: ariadne:/harness/runs/ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION/handoff/ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION_handoff.zip
- latest_NEXT_PACKET_RECOMMENDATION: ATLAS_P4_SCHEDULED_PUBLISH

## Latest Indexed Evidence Before This Publication

- indexed_latest_run_id: ATLAS_P0_CONTRACT_AND_LOCAL_INDEXER
- indexed_latest_final_report: harness/runs/ATLAS_P0_CONTRACT_AND_LOCAL_INDEXER/FINAL_REPORT.md
- indexed_latest_report_status: PASS
- indexed_latest_handoff_zip: harness/runs/ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526/handoff/ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526_handoff.zip
- indexed_latest_handoff_name: ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526_handoff.zip

## Recommended Read Order

1. Read Window /status and /health for live service reachability.
2. Read Window /state/current for live operating state.
3. Read this file for latest routing and public evidence pointers.
4. Read CURRENT_STATE.md for dense operating-state summary.
5. Use RUN_INDEX.jsonl, HANDOFF_INDEX.jsonl, and REPORT_INDEX.jsonl to locate deeper evidence.
6. Use GDrive Atlas only for bulk handoff/report evidence; do not expect bulk evidence in GitHub.

## Known Warnings

- Postgres row-level projection is limited in this run because local PG connection variables were absent.
- Public indexes are filtered when labels are not suitable for the public pointer layer.
- The Window state materialized view is 23.0 hours old; refresh if it exceeds the stale_after timestamp.
- Atlas is a publication layer; do not treat a public pointer as canonical state.

## Next Action

Run ATLAS_P4_SCHEDULED_PUBLISH: scheduled refresh of Window, Atlas local indexes, GDrive pointers, and public GitHub pointer files.
