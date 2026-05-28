# Ariadne Atlas Current State

generated_at: 2026-05-28T08:10:25.8785660Z
state_freshness: FRESH
stale_after: 2026-05-28T08:40:25.8785660Z
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
- current_state_age: 22.6 hours old

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

- run_index_rows_source: 343
- handoff_index_rows_source: 218
- report_index_rows_source: 263
- contract_index_rows_source: 515
- window_index_rows_source: 26

## GDrive Publish Status

- gdrive_atlas_root: G:\내 드라이브\Ariadne Atlas
- pointer_folder_present: True
- index_folder_present: True
- handoff_zip_count: 206
- publish_status: SCHEDULED_APPLY_GATED

## Public GitHub Publish Status

- public_repo: https://github.com/paulseongminpark/ariadne-atlas
- local_repo: D:\dev\ariadne-atlas
- public_target: D:\dev\ariadne-atlas\context\atlas
- raw_latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- raw_current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- publish_scope: README.md plus context/atlas pointer and index files

## Latest Runs

- `ARIADNE_C4_DUCKDB_FINALREPORT_PROJECTION_DRIFT` | status=`UNKNOWN` | latest=`2026-05-28T08:05:41.008940+00:00`
- `interactive_869b45e6` | status=`UNKNOWN` | latest=`2026-05-28T08:00:43.713110+00:00`
- `interactive_32b06739` | status=`UNKNOWN` | latest=`2026-05-28T08:00:41.423461+00:00`
- `interactive_98888b27` | status=`UNKNOWN` | latest=`2026-05-28T08:00:37.273530+00:00`
- `interactive_c16b7de5` | status=`UNKNOWN` | latest=`2026-05-28T08:00:36.199507+00:00`
- `interactive_b9e12c43` | status=`UNKNOWN` | latest=`2026-05-28T08:00:25.910110+00:00`
- `interactive_63d2cfdb` | status=`UNKNOWN` | latest=`2026-05-28T07:57:43.167220+00:00`
- `interactive_9174475d` | status=`UNKNOWN` | latest=`2026-05-28T07:57:30.903899+00:00`
- `ATLAS_P2_GDRIVE_PUBLISHER` | status=`PASS` | latest=`2026-05-28T07:55:03.421057+00:00`
- `interactive_6ca1e74b` | status=`UNKNOWN` | latest=`2026-05-28T07:23:25.319853+00:00`

## Latest Handoffs

- `ARIADNE_C4_DUCKDB_FINALREPORT_PROJECTION_DRIFT_handoff.zip` | run=`ARIADNE_C4_DUCKDB_FINALREPORT_PROJECTION_DRIFT` | latest=`2026-05-28T08:05:41.008940+00:00`
- `ARIADNE_RUNTIME_HOOK_V1_12_CODEX_PROJECT_SCOPE_INSTALL_P6_20260528_handoff.zip` | run=`ARIADNE_RUNTIME_HOOK_V1_12_CODEX_PROJECT_SCOPE_INSTALL_P6_20260528` | latest=`2026-05-28T06:02:00.315083+00:00`
- `CAD_IR_GOLDEN_REVIEW_BOOTSTRAP_V01_20260527_CODEX_handoff.zip` | run=`CAD_IR_GOLDEN_REVIEW_BOOTSTRAP_V01_20260527_CODEX` | latest=`2026-05-28T05:50:48.605013+00:00`
- `ARIADNE_C8_FALSE_POSITIVE_ACCEPTANCE_POLICY_handoff.zip` | run=`ARIADNE_C8_FALSE_POSITIVE_ACCEPTANCE_POLICY` | latest=`2026-05-28T05:37:36.117196+00:00`
- `ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528_handoff.zip` | run=`ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528` | latest=`2026-05-28T05:34:00.010170+00:00`
- `CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX_handoff.zip` | run=`CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX` | latest=`2026-05-28T05:26:58.681045+00:00`
- `ARIADNE_C8_L0_REDACTED_LOCATOR_FOLLOWUP_V2_handoff.zip` | run=`ARIADNE_C8_L0_REDACTED_LOCATOR_FOLLOWUP_V2` | latest=`2026-05-28T04:55:12.764915+00:00`
- `CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX_handoff.zip` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | latest=`2026-05-28T04:52:54.917526+00:00`
- `ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528_handoff.zip` | run=`ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528` | latest=`2026-05-28T04:51:59.404745+00:00`
- `ARIADNE_C8_REDACTED_SAMPLE_POLICY_DECISION_handoff.zip` | run=`ARIADNE_C8_REDACTED_SAMPLE_POLICY_DECISION` | latest=`2026-05-28T04:41:11.213494+00:00`

## Latest Reports

- `logs/ARIADNE_C4_DUCKDB_FINALREPORT_PROJECTION_DRIFT.md` | run=`UNKNOWN` | status=`PASS_WITH_NOTE` | latest=`2026-05-28T08:05:25.664011+00:00`
- `harness/runs/ARIADNE_RUNTIME_HOOK_V1_12_CODEX_PROJECT_SCOPE_INSTALL_P6_20260528/FINAL_REPORT.md` | run=`ARIADNE_RUNTIME_HOOK_V1_12_CODEX_PROJECT_SCOPE_INSTALL_P6_20260528` | status=`FAIL` | latest=`2026-05-28T06:01:24.784489+00:00`
- `harness/runs/CAD_IR_GOLDEN_REVIEW_BOOTSTRAP_V01_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_GOLDEN_REVIEW_BOOTSTRAP_V01_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T05:50:48.517060+00:00`
- `harness/runs/ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528/FINAL_REPORT.md` | run=`ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T05:33:44.438346+00:00`
- `harness/runs/CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T05:26:58.647520+00:00`
- `harness/runs/CAD_IR_GOLDEN_REVIEW_BOOTSTRAP_V01_20260527_CODEX/input/prior_evidence/FINAL_REPORT.md` | run=`CAD_IR_GOLDEN_REVIEW_BOOTSTRAP_V01_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T05:26:58.647520+00:00`
- `harness/runs/CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:52:51.385669+00:00`
- `harness/runs/CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX/input/FINAL_REPORT.md` | run=`CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:52:51.385669+00:00`
- `harness/runs/ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528/FINAL_REPORT.md` | run=`ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T04:51:34.000839+00:00`
- `harness/runs/CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX/input/prior_evidence/FINAL_REPORT.md` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:35:39.273802+00:00`

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
