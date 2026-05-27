# Ariadne Atlas Current State

generated_at: 2026-05-27T08:46:37.1571127Z
state_freshness: FRESH
stale_after: 2026-05-28T08:46:37.1591988Z
atlas_version: ATLAS_P3E_PUBLIC_POINTER_QUALITY_2026-05-27

## Role Split

- Ariadne Window: live control surface and request gate.
- Ariadne Atlas: public evidence map and external re-entry layer.
- Source of truth: Ariadne private runtime/control-plane records, not this public repo.

## Window Health

- stable_endpoint: https://ariadne-window.paulseongminpark.workers.dev
- status_endpoint: https://ariadne-window.paulseongminpark.workers.dev/status
- health_endpoint: https://ariadne-window.paulseongminpark.workers.dev/health
- state_endpoint: https://ariadne-window.paulseongminpark.workers.dev/state/current
- service_status: ok
- health_status: ok
- service: ariadne-window-workers-dev
- workers_dev_entrypoint: True
- current_state_generated_at: 2026-05-26T09:45:32.379652+00:00
- current_state_age: 23.0 hours old

## MCP Status

- remote_mcp_endpoint: https://ariadne-window.paulseongminpark.workers.dev/mcp
- advertised_endpoint: /mcp
- protocol_versions: 2025-03-26, 2025-06-18
- write_surface: request-only
- approval_endpoint: blocked

## Postgres Control Plane Status

- projection_status: LIMITED_CONNECTION_VARIABLES_ABSENT
- postgres_role_from_window: control_plane
- socket_from_window: not_configured
- row_projection: not queried in this run
- recent_window_request_summary: unavailable without local PG connection variables
- allowed_scope_if_available: ariadne_workbench.window_* tables only

## Atlas Local Index Status

- run_index_rows_source: 263
- handoff_index_rows_source: 156
- report_index_rows_source: 194
- contract_index_rows_source: 496
- window_index_rows_source: 25
- public_index_filtering:
- RUN_INDEX.jsonl: source_rows=263, public_rows=263, filtered_rows=0
- HANDOFF_INDEX.jsonl: source_rows=156, public_rows=156, filtered_rows=0
- REPORT_INDEX.jsonl: source_rows=194, public_rows=194, filtered_rows=0
- CONTRACT_INDEX.jsonl: source_rows=496, public_rows=496, filtered_rows=0
- WINDOW_INDEX.jsonl: source_rows=25, public_rows=25, filtered_rows=0

## GDrive Publish Status

- gdrive_atlas_root: G:\내 드라이브\Ariadne Atlas
- pointer_folder_present: True
- index_folder_present: True
- handoff_zip_count: 153
- latest_pointer_path: G:\내 드라이브\Ariadne Atlas\00_POINTERS\LATEST_POINTER.md
- publish_status: PASS_FOR_POINTER_UPDATE

## Public GitHub Publish Status

- public_repo: https://github.com/paulseongminpark/ariadne-atlas
- local_repo: D:\dev\ariadne-atlas
- public_target: D:\dev\ariadne-atlas\context\atlas
- raw_latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- raw_current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- publish_scope: README.md plus context/atlas pointer and index files
- bulk_evidence_in_github: absent by policy

## Latest Runs

- `ATLAS_P0_CONTRACT_AND_LOCAL_INDEXER` | status=`PASS` | final_report=`harness/runs/ATLAS_P0_CONTRACT_AND_LOCAL_INDEXER/FINAL_REPORT.md` | latest=`2026-05-27T05:41:01.051692+00:00`
- `interactive_d9fa3f61` | status=`UNKNOWN` | final_report=`NONE` | latest=`2026-05-27T05:37:51.491522+00:00`
- `interactive_573da2e1` | status=`UNKNOWN` | final_report=`NONE` | latest=`2026-05-27T05:35:41.779362+00:00`
- `interactive_86cabe2d` | status=`UNKNOWN` | final_report=`NONE` | latest=`2026-05-27T05:28:57.508749+00:00`
- `ARIADNE_FIRST_FULL_AUDIT_HERMES_OPS_RUNTIME` | status=`UNKNOWN` | final_report=`NONE` | latest=`2026-05-27T05:27:19.597083+00:00`
- `interactive_f0a335f3` | status=`UNKNOWN` | final_report=`NONE` | latest=`2026-05-27T05:18:41.444352+00:00`
- `interactive_89db0434` | status=`UNKNOWN` | final_report=`NONE` | latest=`2026-05-27T05:18:38.172940+00:00`
- `interactive_661db01e` | status=`UNKNOWN` | final_report=`NONE` | latest=`2026-05-27T05:15:22.460003+00:00`
- `interactive_cf62d234` | status=`UNKNOWN` | final_report=`NONE` | latest=`2026-05-27T05:14:50.572168+00:00`
- `ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526` | status=`UNKNOWN` | final_report=`harness/runs/ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526/FINAL_REPORT.md` | latest=`2026-05-27T05:10:54.825334+00:00`

## Latest Handoffs

- `ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526_handoff.zip` | run=`ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526` | size=48776 | latest=`2026-05-27T05:10:54.825334+00:00`
- `ARIADNE_FIRST_FULL_AUDIT_CODEX_DB_LEDGER_handoff.zip` | run=`ARIADNE_FIRST_FULL_AUDIT_CODEX_DB_LEDGER` | size=16347 | latest=`2026-05-27T05:08:31.532943+00:00`
- `ARIADNE_FIRST_FULL_AUDIT_GEMINI_ADVERSARIAL_REVIEW_handoff.zip` | run=`ARIADNE_FIRST_FULL_AUDIT_GEMINI_ADVERSARIAL_REVIEW` | size=1651 | latest=`2026-05-27T04:58:01.319197+00:00`
- `ARIADNE_FIRST_FULL_AUDIT_CLAUDE_SYSTEM_GOVERNANCE_handoff.zip` | run=`ARIADNE_FIRST_FULL_AUDIT_CLAUDE_SYSTEM_GOVERNANCE` | size=6613 | latest=`2026-05-27T04:42:01.893008+00:00`
- `CAD_IR_TRUTH_GATE_AND_EXPERIMENTAL_DB_APPLY_20260527_CODEX_handoff.zip` | run=`CAD_IR_TRUTH_GATE_AND_EXPERIMENTAL_DB_APPLY_20260527_CODEX` | size=24227225 | latest=`2026-05-27T02:37:13.934006+00:00`
- `ARIADNE_AUDIT_AUTORESEARCH_AND_CROSS_COVERAGE_UPGRADE_handoff.zip` | run=`ARIADNE_AUDIT_AUTORESEARCH_AND_CROSS_COVERAGE_UPGRADE` | size=5793 | latest=`2026-05-27T02:23:44.168075+00:00`
- `ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_DRYRUN_20260526_handoff.zip` | run=`ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_DRYRUN_20260526` | size=83138 | latest=`2026-05-27T02:23:16.424989+00:00`
- `CAD_IR_DB_INGEST_RHINOCOMMON_VALIDATE_20260527_CODEX_handoff.zip` | run=`CAD_IR_DB_INGEST_RHINOCOMMON_VALIDATE_20260527_CODEX` | size=24154895 | latest=`2026-05-27T01:42:29.387795+00:00`
- `WINDOW_V2D_WEB_AI_OPERATIONS_PLAYBOOK_handoff.zip` | run=`WINDOW_V2D_WEB_AI_OPERATIONS_PLAYBOOK` | size=15025 | latest=`2026-05-27T01:26:12.744060+00:00`
- `WINDOW_V2C_GEMINI_READONLY_REVIEWER_SETUP_handoff.zip` | run=`WINDOW_V2C_GEMINI_READONLY_REVIEWER_SETUP` | size=34197 | latest=`2026-05-27T01:09:33.292150+00:00`

## Latest Reports

- `harness/runs/ATLAS_P0_CONTRACT_AND_LOCAL_INDEXER/FINAL_REPORT.md` | run=`ATLAS_P0_CONTRACT_AND_LOCAL_INDEXER` | status=`PASS` | latest=`2026-05-27T05:40:35.941044+00:00`
- `harness/runs/ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526/FINAL_REPORT.md` | run=`ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526` | status=`UNKNOWN` | latest=`2026-05-27T05:10:13.151209+00:00`
- `harness/runs/ARIADNE_FIRST_FULL_AUDIT_CODEX_DB_LEDGER/FINAL_REPORT.md` | run=`ARIADNE_FIRST_FULL_AUDIT_CODEX_DB_LEDGER` | status=`PARTIAL_PASS` | latest=`2026-05-27T05:06:22.091405+00:00`
- `harness/runs/CAD_IR_TRUTH_GATE_AND_EXPERIMENTAL_DB_APPLY_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_TRUTH_GATE_AND_EXPERIMENTAL_DB_APPLY_20260527_CODEX` | status=`UNKNOWN` | latest=`2026-05-27T02:36:26.403066+00:00`
- `harness/runs/ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_DRYRUN_20260526/FINAL_REPORT.md` | run=`ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_DRYRUN_20260526` | status=`UNKNOWN` | latest=`2026-05-27T02:22:45.072846+00:00`
- `harness/runs/CAD_IR_DB_INGEST_RHINOCOMMON_VALIDATE_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_DB_INGEST_RHINOCOMMON_VALIDATE_20260527_CODEX` | status=`UNKNOWN` | latest=`2026-05-27T01:42:28.270407+00:00`
- `harness/runs/WINDOW_V2D_WEB_AI_OPERATIONS_PLAYBOOK/FINAL_REPORT.md` | run=`WINDOW_V2D_WEB_AI_OPERATIONS_PLAYBOOK` | status=`UNKNOWN` | latest=`2026-05-27T01:25:59.154872+00:00`
- `harness/runs/WINDOW_V2C_GEMINI_READONLY_REVIEWER_SETUP/FINAL_REPORT.md` | run=`WINDOW_V2C_GEMINI_READONLY_REVIEWER_SETUP` | status=`UNKNOWN` | latest=`2026-05-27T01:06:44.702419+00:00`
- `harness/runs/WINDOW_V2C_GEMINI_CLI_READONLY_REVIEWER/FINAL_REPORT.md` | run=`WINDOW_V2C_GEMINI_CLI_READONLY_REVIEWER` | status=`UNKNOWN` | latest=`2026-05-27T00:33:46.652229+00:00`
- `harness/runs/ARIADNE_PACKET_SOURCE_GAPS_FULL_BACKFILL_ATTEMPT/FINAL_REPORT.md` | run=`ARIADNE_PACKET_SOURCE_GAPS_FULL_BACKFILL_ATTEMPT` | status=`PASS` | latest=`2026-05-26T10:10:32.605724+00:00`

## Dirty Or Relevant Repo Notes

- public_repo_initial_status: clean before this packet generated pointer updates
- window_reported_unrelated_workspace_dirt: yes, unrelated to this public pointer repo
- ariadne_root_git_status: not a standalone Git repo per Window state

## Safety Posture

- raw_command: absent
- raw_sql: absent
- direct_file_mutation: absent
- approval_endpoint: blocked
- write_surface: request-only
- public_repo_bulk_payloads: absent
- public_pointer_files: metadata and routing only

## Known Warnings

- Postgres table rows were not queried because local PG connection variables were absent.
- Public index copies may omit labels that are not suitable for a public pointer layer.
- GDrive archive contents are intentionally not mirrored to GitHub.
- Window state should be refreshed when stale_after passes.

## Next Recommended Actions

1. Run ATLAS_P4_SCHEDULED_PUBLISH for scheduled refresh.
2. Configure local PG connection variables before any future row-level Window control-plane projection.
3. Keep GitHub pointer files small, public, and AI-readable.
4. Keep GDrive as the bulk evidence archive.

## Deeper Index Links

- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/RUN_INDEX.jsonl
- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/HANDOFF_INDEX.jsonl
- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/REPORT_INDEX.jsonl
- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CONTRACT_INDEX.jsonl
- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/WINDOW_INDEX.jsonl
