# Ariadne Atlas Current State

generated_at: 2026-05-28T04:55:20.8579185Z
state_freshness: FRESH
stale_after: 2026-05-28T05:25:20.8579185Z
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
- current_state_generated_at: 2026-05-27T09:34:20.553922+00:00
- current_state_age: 19.4 hours old

## MCP Status

- remote_mcp_endpoint: https://ariadne-window.paulseongminpark.workers.dev/mcp
- advertised_endpoint: /mcp
- protocol_versions: 2025-03-26, 2025-06-18
- write_surface: request-only
- approval_endpoint: blocked

## Postgres Control Plane Status

- projection_status: LIMITED_CONNECTION_VARIABLES_DEPENDENT
- postgres_role_from_window: control_plane
- socket_from_window: not_configured
- row_projection: scheduled pointer publication does not read SQL directly
- allowed_scope_if_enabled_later: ariadne_workbench.window_* tables only

## Atlas Local Index Status

- run_index_rows_source: 330
- handoff_index_rows_source: 211
- report_index_rows_source: 256
- contract_index_rows_source: 515
- window_index_rows_source: 26

## GDrive Publish Status

- gdrive_atlas_root: G:\내 드라이브\Ariadne Atlas
- pointer_folder_present: True
- index_folder_present: True
- handoff_zip_count: 199
- publish_status: SCHEDULED_APPLY_GATED

## Public GitHub Publish Status

- public_repo: https://github.com/paulseongminpark/ariadne-atlas
- local_repo: D:\dev\ariadne-atlas
- public_target: D:\dev\ariadne-atlas\context\atlas
- raw_latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- raw_current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- publish_scope: README.md plus context/atlas pointer and index files

## Latest Runs

- `CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:52:55.210856+00:00`
- `ARIADNE_C8_L0_REDACTED_LOCATOR_FOLLOWUP_V2` | status=`UNKNOWN` | latest=`2026-05-28T04:52:45.862279+00:00`
- `interactive_3bf56356` | status=`UNKNOWN` | latest=`2026-05-28T04:52:44.005119+00:00`
- `ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T04:51:59.404745+00:00`
- `interactive_b103215c` | status=`UNKNOWN` | latest=`2026-05-28T04:49:19.731687+00:00`
- `interactive_8150af4f` | status=`UNKNOWN` | latest=`2026-05-28T04:49:13.951937+00:00`
- `ARIADNE_C8_REDACTED_SAMPLE_POLICY_DECISION` | status=`UNKNOWN` | latest=`2026-05-28T04:41:11.213494+00:00`
- `ATLAS_P2_GDRIVE_PUBLISHER` | status=`PASS` | latest=`2026-05-28T04:40:03.246071+00:00`
- `CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:35:39.791328+00:00`
- `ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE` | status=`PASS` | latest=`2026-05-28T04:34:51.799303+00:00`

## Latest Handoffs

- `CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX_handoff.zip` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | latest=`2026-05-28T04:52:54.917526+00:00`
- `ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528_handoff.zip` | run=`ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528` | latest=`2026-05-28T04:51:59.404745+00:00`
- `ARIADNE_C8_REDACTED_SAMPLE_POLICY_DECISION_handoff.zip` | run=`ARIADNE_C8_REDACTED_SAMPLE_POLICY_DECISION` | latest=`2026-05-28T04:41:11.213494+00:00`
- `CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX_handoff.zip` | run=`CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX` | latest=`2026-05-28T04:35:39.750216+00:00`
- `ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE_handoff.zip` | run=`ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE` | latest=`2026-05-28T04:34:51.799303+00:00`
- `ARIADNE_AUDIT_AGENTS_SKILLS_INSTALL_POINTER_PLAN_handoff.zip` | run=`ARIADNE_AUDIT_AGENTS_SKILLS_INSTALL_POINTER_PLAN` | latest=`2026-05-28T04:34:10.763359+00:00`
- `ARIADNE_CONTEXT_REFRESH_AND_RUNTIME_HOOK_CANDIDATE_V1_12_20260528_handoff.zip` | run=`ARIADNE_CONTEXT_REFRESH_AND_RUNTIME_HOOK_CANDIDATE_V1_12_20260528` | latest=`2026-05-28T04:34:03.036587+00:00`
- `ARIADNE_CHROMA_HEALTHCHECK_PATCH_APPROVAL_REQUIRED_handoff.zip` | run=`ARIADNE_CHROMA_HEALTHCHECK_PATCH_APPROVAL_REQUIRED` | latest=`2026-05-28T04:30:31.324398+00:00`
- `ARIADNE_DUCKDB_SCHEDULED_RUN_OBSERVATION_handoff.zip` | run=`ARIADNE_DUCKDB_SCHEDULED_RUN_OBSERVATION` | latest=`2026-05-28T04:26:01.904423+00:00`
- `WINDOW_ATLAS_V3B_WARNING_REPAIR_handoff.zip` | run=`WINDOW_ATLAS_V3B_WARNING_REPAIR` | latest=`2026-05-28T04:19:47.205076+00:00`

## Latest Reports

- `harness/runs/CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:52:51.385669+00:00`
- `harness/runs/ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528/FINAL_REPORT.md` | run=`ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T04:51:34.000839+00:00`
- `harness/runs/CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX/input/prior_evidence/FINAL_REPORT.md` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:35:39.273802+00:00`
- `harness/runs/CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:35:39.273802+00:00`
- `harness/runs/ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE/FINAL_REPORT.md` | run=`ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE` | status=`PASS` | latest=`2026-05-28T04:34:16.343837+00:00`
- `harness/runs/ARIADNE_CONTEXT_REFRESH_AND_RUNTIME_HOOK_CANDIDATE_V1_12_20260528/FINAL_REPORT.md` | run=`ARIADNE_CONTEXT_REFRESH_AND_RUNTIME_HOOK_CANDIDATE_V1_12_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T04:33:54.476640+00:00`
- `harness/runs/WINDOW_ATLAS_V3B_WARNING_REPAIR/FINAL_REPORT.md` | run=`WINDOW_ATLAS_V3B_WARNING_REPAIR` | status=`PASS` | latest=`2026-05-28T04:19:12.955292+00:00`
- `harness/runs/ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527/FINAL_REPORT.md` | run=`ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527` | status=`PASS` | latest=`2026-05-28T02:50:59.443540+00:00`
- `harness/runs/CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | status=`PASS_PARTIAL` | latest=`2026-05-28T02:17:59.598211+00:00`
- `harness/runs/CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX/attempts/attempt_2_repeat/FINAL_REPORT.md` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T02:17:57.991194+00:00`

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
