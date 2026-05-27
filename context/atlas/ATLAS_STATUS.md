# Ariadne Atlas Status

generated_at: 2026-05-27T08:46:37.1571127Z
stale_after: 2026-05-28T08:46:37.1591988Z
atlas_version: ATLAS_P3E_PUBLIC_POINTER_QUALITY_2026-05-27
status: PASS_FOR_PUBLIC_POINTER_UPDATE

## Layer Status

- Window live fetch: PASS
- Postgres row projection: LIMITED_CONNECTION_VARIABLES_ABSENT
- Atlas local indexes: PRESENT
- GDrive pointer folder: PRESENT
- GDrive index folder: PRESENT
- Public GitHub repo: PRESENT
- Public raw target: pending post-push verification

## Counts

- source_run_rows: 263
- source_handoff_rows: 156
- source_report_rows: 194
- source_contract_rows: 496
- source_window_rows: 25
- gdrive_handoff_zips: 153

## Public Filtering

- RUN_INDEX.jsonl: source_rows=263, public_rows=263, filtered_rows=0
- HANDOFF_INDEX.jsonl: source_rows=156, public_rows=156, filtered_rows=0
- REPORT_INDEX.jsonl: source_rows=194, public_rows=194, filtered_rows=0
- CONTRACT_INDEX.jsonl: source_rows=496, public_rows=496, filtered_rows=0
- WINDOW_INDEX.jsonl: source_rows=25, public_rows=25, filtered_rows=0

## Policy

Atlas is generated. Window and Ariadne private runtime/control-plane records remain canonical. GitHub carries only compact pointers and public-safe indexes.
