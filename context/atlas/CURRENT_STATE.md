# Ariadne Atlas Current State

generated_at: 2026-06-30T05:41:46.8436232Z
state_freshness: FRESH
stale_after: 2026-06-30T06:11:46.8436232Z
atlas_version: ATLAS_P4_SCHEDULED_PUBLISH

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
- current_state_generated_at: 2026-06-30T05:35:03.872018+00:00
- current_state_age: 0.1 hours old

## MCP Status

- remote_mcp_endpoint: https://ariadne-window.paulseongminpark.workers.dev/mcp
- advertised_endpoint: /mcp
- protocol_versions: 2025-03-26, 2025-06-18
- write_surface: request-only
- approval_endpoint: blocked

## Postgres Control Plane Status

- projection_status: LIMITED_CONNECTION_VARIABLES_DEPENDENT
- postgres_role_from_window: control_plane
- socket_from_window: reachable
- row_projection: scheduled pointer publication does not read SQL directly
- allowed_scope_if_enabled_later: ariadne_workbench.window_* tables only

## Atlas Local Index Status

- run_index_rows_source: 885
- handoff_index_rows_source: 282
- report_index_rows_source: 316
- contract_index_rows_source: 540
- window_index_rows_source: 26

## GDrive Publish Status

- gdrive_atlas_root: C:\Users\PAUL\내 드라이브\Ariadne Atlas
- pointer_folder_present: True
- index_folder_present: True
- handoff_zip_count: 264
- publish_status: SCHEDULED_APPLY_GATED

## Public GitHub Publish Status

- public_repo: https://github.com/paulseongminpark/ariadne-atlas
- local_repo: D:\dev\ariadne-atlas
- public_target: D:\dev\ariadne-atlas\context\atlas
- raw_latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- raw_current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- publish_scope: README.md plus context/atlas pointer and index files

## Latest Runs

- `interactive_9de1511a` | status=`UNKNOWN` | latest=`2026-06-30T05:34:42.854540+00:00`
- `ATLAS_P2_GDRIVE_PUBLISHER` | status=`PASS` | latest=`2026-06-30T05:25:17.054974+00:00`
- `interactive_c6ae0a2a` | status=`UNKNOWN` | latest=`2026-06-30T05:19:56.223259+00:00`
- `interactive_d8be037a` | status=`UNKNOWN` | latest=`2026-06-30T05:19:26.860170+00:00`
- `interactive_373c13ff` | status=`UNKNOWN` | latest=`2026-06-30T05:01:06.150867+00:00`
- `interactive_b29043c8` | status=`UNKNOWN` | latest=`2026-06-30T04:46:18.983961+00:00`
- `interactive_387660c5` | status=`UNKNOWN` | latest=`2026-06-30T04:40:12.132196+00:00`
- `interactive_a4d9d44f` | status=`UNKNOWN` | latest=`2026-06-30T04:30:19.444217+00:00`
- `interactive_1902838b` | status=`UNKNOWN` | latest=`2026-06-30T04:29:48.579746+00:00`
- `interactive_b57de855` | status=`UNKNOWN` | latest=`2026-06-30T04:29:38.953192+00:00`

## Latest Handoffs

- `RUN-003_LAB2_knowledge_pack_20260615.zip` | run=`RUN-003_LAB2_knowledge_pack_20260615.zip` | latest=`2026-06-15T01:20:56.445839+00:00`
- `ARIADNE_AGENTIC_MACHINE_COUNTER_AUDIT_CODEX_20260605_handoff.zip` | run=`ARIADNE_AGENTIC_MACHINE_COUNTER_AUDIT_CODEX_20260605` | latest=`2026-06-05T09:38:14.997110+00:00`
- `ARIADNE_AGENTIC_MACHINE_DEEP_AUDIT_CODEX_20260604_handoff.zip` | run=`ARIADNE_AGENTIC_MACHINE_DEEP_AUDIT_CODEX_20260604` | latest=`2026-06-04T08:53:12.086585+00:00`
- `CAD_TRANSFORMATION_MVP_PHASE_0_5_REGION_ISOLATION_MVP001_20260604_handoff.zip` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_5_REGION_ISOLATION_MVP001_20260604` | latest=`2026-06-04T08:42:51.809657+00:00`
- `CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604_handoff.zip` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604` | latest=`2026-06-04T08:34:33.294778+00:00`
- `ARIADNE_FULL_SCOPE_BASELINE_AUDIT_AND_INDEX_CODEX_20260604_handoff.zip` | run=`ARIADNE_FULL_SCOPE_BASELINE_AUDIT_AND_INDEX_CODEX_20260604` | latest=`2026-06-04T08:30:10.038831+00:00`
- `CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604_handoff.zip` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_1_20260604` | latest=`2026-06-04T08:18:26.561827+00:00`
- `CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604_handoff.zip` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_2_SINGLE_PAIR_DWG_SANDBOX_MVP001_20260604` | latest=`2026-06-04T08:18:26.561827+00:00`
- `CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604_handoff.zip` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_3_DWG_ROUTE_FIX_MVP001_20260604` | latest=`2026-06-04T08:18:26.561827+00:00`
- `CAD_TRANSFORMATION_MVP_PHASE_0_3_DWG_ROUTE_FIX_MVP001_20260604_handoff.zip` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_1_20260604` | latest=`2026-06-04T07:58:16.964065+00:00`

## Latest Reports

- `harness/runs/ARIADNE_AGENTIC_MACHINE_COUNTER_AUDIT_CODEX_20260605/FINAL_REPORT.md` | run=`ARIADNE_AGENTIC_MACHINE_COUNTER_AUDIT_CODEX_20260605` | status=`PASS_WITH_DEFERRAL` | latest=`2026-06-05T09:36:44.113915+00:00`
- `harness/runs/RUN-003-ir-projection-sandbox/FINAL_REPORT.md` | run=`RUN-003-ir-projection-sandbox` | status=`UNKNOWN` | latest=`2026-06-04T09:02:17.990154+00:00`
- `harness/runs/ARIADNE_AGENTIC_MACHINE_DEEP_AUDIT_CODEX_20260604/FINAL_REPORT.md` | run=`ARIADNE_AGENTIC_MACHINE_DEEP_AUDIT_CODEX_20260604` | status=`UNKNOWN` | latest=`2026-06-04T08:52:49.411298+00:00`
- `harness/runs/CAD_TRANSFORMATION_MVP_PHASE_0_5_REGION_ISOLATION_MVP001_20260604/handoff/FINAL_REPORT.md` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_5_REGION_ISOLATION_MVP001_20260604` | status=`UNKNOWN` | latest=`2026-06-04T08:42:26.667825+00:00`
- `harness/runs/ARIADNE_FULL_SCOPE_BASELINE_AUDIT_AND_INDEX_CODEX_20260604/FINAL_REPORT.md` | run=`ARIADNE_FULL_SCOPE_BASELINE_AUDIT_AND_INDEX_CODEX_20260604` | status=`UNKNOWN` | latest=`2026-06-04T08:28:56.758071+00:00`
- `harness/runs/CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604/handoff/FINAL_REPORT.md` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604` | status=`UNKNOWN` | latest=`2026-06-04T08:18:23.892325+00:00`
- `harness/runs/CAD_TRANSFORMATION_MVP_PHASE_0_3_DWG_ROUTE_FIX_MVP001_20260604/handoff/FINAL_REPORT.md` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_3_DWG_ROUTE_FIX_MVP001_20260604` | status=`UNKNOWN` | latest=`2026-06-04T07:58:16.271959+00:00`
- `harness/runs/CAD_IR_HOME_SLOPE_NORMAL_DETAIL_REGROUP_V01_20260604_CLAUDE/FINAL_REPORT.md` | run=`CAD_IR_HOME_SLOPE_NORMAL_DETAIL_REGROUP_V01_20260604_CLAUDE` | status=`UNKNOWN` | latest=`2026-06-04T05:06:04.532976+00:00`
- `harness/runs/ARIADNE_FU7_ATLAS_APPLY_PUBLICONLY_POINTERINDEXONLY_RERUN_CODEX_20260604/FINAL_REPORT.md` | run=`ARIADNE_FU7_ATLAS_APPLY_PUBLICONLY_POINTERINDEXONLY_RERUN_CODEX_20260604` | status=`UNKNOWN` | latest=`2026-06-04T04:59:34.978016+00:00`
- `harness/runs/CAD_IR_GH_METRIC_BACKFILL_FOR_DNY_V01_20260602_CLAUDE/FINAL_REPORT.md` | run=`CAD_IR_GH_METRIC_BACKFILL_FOR_DNY_V01_20260602_CLAUDE` | status=`UNKNOWN` | latest=`2026-06-04T04:46:56.767749+00:00`

## Safety Posture

- raw_command: absent
- raw_sql: absent
- direct_file_mutation: absent
- approval_endpoint: blocked
- write_surface: request-only
- public_repo_bulk_payloads: absent by scheduled safety scan

## Scheduled Publish

- task_name: AriadneAtlasScheduledPublish
- cadence: at logon, repeat every 15 minutes for 1 day
- default_script_mode: dry-run
- scheduled_action_mode: apply public-only

## Known Warnings

- Private orchestration update is optional and only allowed when explicitly requested and clean.
- GDrive can contain bulk evidence; GitHub must remain pointer-only.
- If public raw access fails, run the GitHub push repair packet.

## Next Recommended Actions

1. Confirm one unattended scheduled cycle after registration.
2. Run ATLAS_P5_WINDOW_INTEGRATION.
3. Keep scheduled publication compact and pointer-only for GitHub.

## Deeper Index Links

- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/RUN_INDEX.jsonl
- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/HANDOFF_INDEX.jsonl
- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/REPORT_INDEX.jsonl
- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CONTRACT_INDEX.jsonl
- https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/WINDOW_INDEX.jsonl
