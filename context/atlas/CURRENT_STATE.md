# Ariadne Atlas Current State

generated_at: 2026-05-28T05:40:17.6603590Z
state_freshness: FRESH
stale_after: 2026-05-28T06:10:17.6603590Z
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
- current_state_age: 20.1 hours old

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

- run_index_rows_source: 338
- handoff_index_rows_source: 215
- report_index_rows_source: 259
- contract_index_rows_source: 515
- window_index_rows_source: 26

## GDrive Publish Status

- gdrive_atlas_root: G:\내 드라이브\Ariadne Atlas
- pointer_folder_present: True
- index_folder_present: True
- handoff_zip_count: 203
- publish_status: SCHEDULED_APPLY_GATED

## Public GitHub Publish Status

- public_repo: https://github.com/paulseongminpark/ariadne-atlas
- local_repo: D:\dev\ariadne-atlas
- public_target: D:\dev\ariadne-atlas\context\atlas
- raw_latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- raw_current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- publish_scope: README.md plus context/atlas pointer and index files

## Latest Runs

- `ARIADNE_C8_FALSE_POSITIVE_ACCEPTANCE_POLICY` | status=`UNKNOWN` | latest=`2026-05-28T05:37:36.117196+00:00`
- `ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T05:34:22.451699+00:00`
- `CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T05:26:58.684555+00:00`
- `interactive_9b0752e7` | status=`UNKNOWN` | latest=`2026-05-28T05:26:56.938170+00:00`
- `ATLAS_P2_GDRIVE_PUBLISHER` | status=`PASS` | latest=`2026-05-28T05:25:03.410695+00:00`
- `interactive_651cbfe2` | status=`UNKNOWN` | latest=`2026-05-28T05:23:01.689940+00:00`
- `interactive_3e843206` | status=`UNKNOWN` | latest=`2026-05-28T05:22:33.893157+00:00`
- `interactive_9174475d` | status=`UNKNOWN` | latest=`2026-05-28T05:15:09.099769+00:00`
- `interactive_a837d842` | status=`UNKNOWN` | latest=`2026-05-28T05:15:02.455071+00:00`
- `interactive_b66bd687` | status=`UNKNOWN` | latest=`2026-05-28T05:12:38.889338+00:00`

## Latest Handoffs

- `ARIADNE_C8_FALSE_POSITIVE_ACCEPTANCE_POLICY_handoff.zip` | run=`ARIADNE_C8_FALSE_POSITIVE_ACCEPTANCE_POLICY` | latest=`2026-05-28T05:37:36.117196+00:00`
- `ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528_handoff.zip` | run=`ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528` | latest=`2026-05-28T05:34:00.010170+00:00`
- `CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX_handoff.zip` | run=`CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX` | latest=`2026-05-28T05:26:58.681045+00:00`
- `ARIADNE_C8_L0_REDACTED_LOCATOR_FOLLOWUP_V2_handoff.zip` | run=`ARIADNE_C8_L0_REDACTED_LOCATOR_FOLLOWUP_V2` | latest=`2026-05-28T04:55:12.764915+00:00`
- `CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX_handoff.zip` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | latest=`2026-05-28T04:52:54.917526+00:00`
- `ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528_handoff.zip` | run=`ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528` | latest=`2026-05-28T04:51:59.404745+00:00`
- `ARIADNE_C8_REDACTED_SAMPLE_POLICY_DECISION_handoff.zip` | run=`ARIADNE_C8_REDACTED_SAMPLE_POLICY_DECISION` | latest=`2026-05-28T04:41:11.213494+00:00`
- `CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX_handoff.zip` | run=`CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX` | latest=`2026-05-28T04:35:39.750216+00:00`
- `ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE_handoff.zip` | run=`ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE` | latest=`2026-05-28T04:34:51.799303+00:00`
- `ARIADNE_AUDIT_AGENTS_SKILLS_INSTALL_POINTER_PLAN_handoff.zip` | run=`ARIADNE_AUDIT_AGENTS_SKILLS_INSTALL_POINTER_PLAN` | latest=`2026-05-28T04:34:10.763359+00:00`

## Latest Reports

- `harness/runs/ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528/FINAL_REPORT.md` | run=`ARIADNE_CLAUDE_PROJECT_HOOK_BURN_IN_OBSERVATION_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T05:33:44.438346+00:00`
- `harness/runs/CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T05:26:58.647520+00:00`
- `harness/runs/CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:52:51.385669+00:00`
- `harness/runs/CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX/input/FINAL_REPORT.md` | run=`CAD_IR_EXACT_REBUILD_TO_090_WITH_SCORE_CONFIDENCE_AUDIT_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:52:51.385669+00:00`
- `harness/runs/ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528/FINAL_REPORT.md` | run=`ARIADNE_RUNTIME_HOOK_V1_12_CLAUDE_PROJECT_SCOPE_INSTALL_P5_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T04:51:34.000839+00:00`
- `harness/runs/CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX/input/prior_evidence/FINAL_REPORT.md` | run=`CAD_IR_EXACT_GEOMETRY_REBUILD_TO_090_LOOP_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:35:39.273802+00:00`
- `harness/runs/CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_FULL_GEOMETRY_SERIALIZATION_AND_REBUILD_V01_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-28T04:35:39.273802+00:00`
- `harness/runs/ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE/FINAL_REPORT.md` | run=`ARIADNE_WINDOW_ATLAS_OPERATIONAL_BASELINE_FREEZE` | status=`PASS` | latest=`2026-05-28T04:34:16.343837+00:00`
- `harness/runs/ARIADNE_CONTEXT_REFRESH_AND_RUNTIME_HOOK_CANDIDATE_V1_12_20260528/FINAL_REPORT.md` | run=`ARIADNE_CONTEXT_REFRESH_AND_RUNTIME_HOOK_CANDIDATE_V1_12_20260528` | status=`PASS_WITH_DEGRADED_FEATURES` | latest=`2026-05-28T04:33:54.476640+00:00`
- `harness/runs/WINDOW_ATLAS_V3B_WARNING_REPAIR/FINAL_REPORT.md` | run=`WINDOW_ATLAS_V3B_WARNING_REPAIR` | status=`PASS` | latest=`2026-05-28T04:19:12.955292+00:00`

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
