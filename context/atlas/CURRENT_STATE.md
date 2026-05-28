# Ariadne Atlas Current State

generated_at: 2026-05-28T04:10:18.2484782Z
state_freshness: FRESH
stale_after: 2026-05-28T04:40:18.2484782Z
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
- current_state_age: 18.6 hours old

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

- run_index_rows_source: 314
- handoff_index_rows_source: 201
- report_index_rows_source: 248
- contract_index_rows_source: 505
- window_index_rows_source: 25

## GDrive Publish Status

- gdrive_atlas_root: G:\내 드라이브\Ariadne Atlas
- pointer_folder_present: True
- index_folder_present: True
- handoff_zip_count: 190
- publish_status: SCHEDULED_APPLY_GATED

## Public GitHub Publish Status

- public_repo: https://github.com/paulseongminpark/ariadne-atlas
- local_repo: D:\dev\ariadne-atlas
- public_target: D:\dev\ariadne-atlas\context\atlas
- raw_latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- raw_current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- publish_scope: README.md plus context/atlas pointer and index files

## Latest Runs

- `ATLAS_P2_GDRIVE_PUBLISHER` | status=`PASS` | latest=`2026-05-28T03:55:03.056110+00:00`
- `ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527` | status=`PASS` | latest=`2026-05-28T02:51:09.059016+00:00`
- `CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T02:18:02.791278+00:00`
- `WINDOW_ATLAS_V3_OPERATIONAL_TRIAL` | status=`PASS_WITH_NOTES` | latest=`2026-05-28T02:14:08.955860+00:00`
- `CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-27T09:55:31.383514+00:00`
- `ATLAS_P5_WINDOW_INTEGRATION` | status=`PASS` | latest=`2026-05-27T09:38:07.639447+00:00`
- `ARIADNE_PACKET_TRACE_AND_BOOT_CONTEXT_CONSUMPTION_PHASE2_5_3_20260527` | status=`PASS` | latest=`2026-05-27T09:36:52.128092+00:00`
- `ARIADNE_SCHEMA_V0_CLOSEOUT_AND_AGENT_PACKET_LEDGER_AUDIT_20260527` | status=`UNKNOWN` | latest=`2026-05-27T09:34:15.941815+00:00`
- `interactive_b7e6c9da` | status=`UNKNOWN` | latest=`2026-05-27T09:33:52.155591+00:00`
- `ARIADNE_DOMAIN_SCHEMA_BOUNDARY_AND_EVOLUTION_REVIEW_V0_20260527` | status=`UNKNOWN` | latest=`2026-05-27T09:16:55.814344+00:00`

## Latest Handoffs

- `ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527_handoff.zip` | run=`ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527` | latest=`2026-05-28T02:51:09.059016+00:00`
- `CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX_handoff.zip` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | latest=`2026-05-28T02:18:02.390092+00:00`
- `CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX_attempt_2_repeat_handoff.zip` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | latest=`2026-05-28T02:17:59.133833+00:00`
- `WINDOW_ATLAS_V3_OPERATIONAL_TRIAL_handoff.zip` | run=`WINDOW_ATLAS_V3_OPERATIONAL_TRIAL` | latest=`2026-05-28T02:14:08.955860+00:00`
- `CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX_attempt_1_fresh_handoff.zip` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | latest=`2026-05-28T02:11:27.344846+00:00`
- `SYN_WINDOW_PACKET_REQUEST_BRIDGE_handoff.zip` | run=`ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527` | latest=`2026-05-28T02:06:27.267235+00:00`
- `CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX_handoff.zip` | run=`CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX` | latest=`2026-05-27T09:55:31.383514+00:00`
- `ATLAS_P5_WINDOW_INTEGRATION_handoff.zip` | run=`ATLAS_P5_WINDOW_INTEGRATION` | latest=`2026-05-27T09:38:07.639447+00:00`
- `ARIADNE_PACKET_TRACE_AND_BOOT_CONTEXT_CONSUMPTION_PHASE2_5_3_20260527_handoff.zip` | run=`ARIADNE_PACKET_TRACE_AND_BOOT_CONTEXT_CONSUMPTION_PHASE2_5_3_20260527` | latest=`2026-05-27T09:36:52.128092+00:00`
- `ARIADNE_SCHEMA_V0_CLOSEOUT_AND_AGENT_PACKET_LEDGER_AUDIT_20260527_handoff.zip` | run=`ARIADNE_SCHEMA_V0_CLOSEOUT_AND_AGENT_PACKET_LEDGER_AUDIT_20260527` | latest=`2026-05-27T09:34:15.941815+00:00`

## Latest Reports

- `harness/runs/ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527/FINAL_REPORT.md` | run=`ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527` | status=`PASS` | latest=`2026-05-28T02:50:59.443540+00:00`
- `harness/runs/CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | status=`PASS_PARTIAL` | latest=`2026-05-28T02:17:59.598211+00:00`
- `harness/runs/CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX/attempts/attempt_2_repeat/FINAL_REPORT.md` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T02:17:57.991194+00:00`
- `harness/runs/WINDOW_ATLAS_V3_OPERATIONAL_TRIAL/FINAL_REPORT.md` | run=`WINDOW_ATLAS_V3_OPERATIONAL_TRIAL` | status=`PASS_WITH_NOTES` | latest=`2026-05-28T02:13:34.048283+00:00`
- `harness/runs/CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX/attempts/attempt_1_fresh/FINAL_REPORT.md` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T02:11:26.017841+00:00`
- `harness/runs/ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527/synthetic_runs/SYN_WINDOW_PACKET_REQUEST_BRIDGE/FINAL_REPORT.md` | run=`ARIADNE_WINDOW_PACKET_INGRESS_DISPATCH_BRIDGE_20260527` | status=`PASS` | latest=`2026-05-28T02:06:26.825806+00:00`
- `harness/runs/CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-27T09:55:29.491074+00:00`
- `harness/runs/CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX/input/previous_run/FINAL_REPORT.md` | run=`CAD_IR_STAGE1_STAGE2_REPEATABILITY_SCORING_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-27T09:55:29.491074+00:00`
- `harness/runs/ATLAS_P5_WINDOW_INTEGRATION/FINAL_REPORT.md` | run=`ATLAS_P5_WINDOW_INTEGRATION` | status=`PASS` | latest=`2026-05-27T09:37:03.834523+00:00`
- `harness/runs/ARIADNE_PACKET_TRACE_AND_BOOT_CONTEXT_CONSUMPTION_PHASE2_5_3_20260527/FINAL_REPORT.md` | run=`ARIADNE_PACKET_TRACE_AND_BOOT_CONTEXT_CONSUMPTION_PHASE2_5_3_20260527` | status=`PASS` | latest=`2026-05-27T09:35:59.041586+00:00`

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
