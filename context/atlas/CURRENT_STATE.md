# Ariadne Atlas Current State

generated_at: 2026-07-08T04:40:17.8656137Z
state_freshness: FRESH
stale_after: 2026-07-08T05:10:17.8656137Z
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
- current_state_generated_at: 2026-07-08T04:35:02.695230+00:00
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

- run_index_rows_source: 348
- handoff_index_rows_source: 289
- report_index_rows_source: 320
- contract_index_rows_source: 542
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

- `ATLAS_P2_GDRIVE_PUBLISHER` | status=`PASS` | latest=`2026-07-08T04:25:11.534406+00:00`
- `.remember` | status=`UNKNOWN` | latest=`2026-07-08T04:22:14.428332+00:00`
- `CAD_IR_T1_AND_FD_D2_INCLUSION_PROOF_20260707` | status=`UNKNOWN` | latest=`2026-07-08T03:27:40.975755+00:00`
- `_archive` | status=`UNKNOWN` | latest=`2026-07-08T03:05:33.954737+00:00`
- `ariadne_codex_audit_team_liveness` | status=`UNKNOWN` | latest=`2026-07-07T19:02:21.988124+00:00`
- `CAD_RHINO_IR_ALL_FAMILY_EVIDENCE_INVESTIGATION_20260707` | status=`UNKNOWN` | latest=`2026-07-07T08:17:27.941261+00:00`
- `CAD_RHINO_IR_PATENT_FAMILY_DOSSIER_20260707` | status=`UNKNOWN` | latest=`2026-07-07T05:53:24.827706+00:00`
- `CAD_RHINO_IR_ONTOLOGY_FULL_TERRAIN_INDEX_20260706` | status=`UNKNOWN` | latest=`2026-07-07T03:07:49.377427+00:00`
- `OCTAVIUS_OCTOLOOP_LOCAL_DISCOVERY_20260706` | status=`UNKNOWN` | latest=`2026-07-06T12:23:55.511028+00:00`
- `CAD_RHINO_IR_PATENT_EVIDENCE_SCAN_20260706` | status=`UNKNOWN` | latest=`2026-07-06T11:43:14.217304+00:00`

## Latest Handoffs

- `CAD_IR_T1_AND_FD_D2_INCLUSION_PROOF_20260707_handoff.zip` | run=`CAD_IR_T1_AND_FD_D2_INCLUSION_PROOF_20260707` | latest=`2026-07-08T03:27:40.975755+00:00`
- `interactive_pre20260708.zip` | run=`_archive` | latest=`2026-07-08T03:05:33.954737+00:00`
- `CAD_RHINO_IR_ALL_FAMILY_EVIDENCE_INVESTIGATION_20260707_handoff.zip` | run=`CAD_RHINO_IR_ALL_FAMILY_EVIDENCE_INVESTIGATION_20260707` | latest=`2026-07-07T08:10:35.828705+00:00`
- `CAD_RHINO_IR_PATENT_FAMILY_DOSSIER_20260707_handoff.zip` | run=`CAD_RHINO_IR_PATENT_FAMILY_DOSSIER_20260707` | latest=`2026-07-07T05:53:04.637627+00:00`
- `CAD_RHINO_IR_ONTOLOGY_FULL_TERRAIN_INDEX_20260706_handoff.zip` | run=`CAD_RHINO_IR_ONTOLOGY_FULL_TERRAIN_INDEX_20260706` | latest=`2026-07-07T03:07:04.355634+00:00`
- `OCTAVIUS_OCTOLOOP_LOCAL_DISCOVERY_20260706_handoff.zip` | run=`OCTAVIUS_OCTOLOOP_LOCAL_DISCOVERY_20260706` | latest=`2026-07-06T12:23:55.511028+00:00`
- `CAD_RHINO_IR_PATENT_EVIDENCE_SCAN_20260706_handoff.zip` | run=`CAD_RHINO_IR_PATENT_EVIDENCE_SCAN_20260706` | latest=`2026-07-06T11:43:14.217304+00:00`
- `RUN-003_LAB2_knowledge_pack_20260615.zip` | run=`RUN-003_LAB2_knowledge_pack_20260615.zip` | latest=`2026-06-15T01:20:56.445839+00:00`
- `ARIADNE_AGENTIC_MACHINE_COUNTER_AUDIT_CODEX_20260605_handoff.zip` | run=`ARIADNE_AGENTIC_MACHINE_COUNTER_AUDIT_CODEX_20260605` | latest=`2026-06-05T09:38:14.997110+00:00`
- `ARIADNE_AGENTIC_MACHINE_DEEP_AUDIT_CODEX_20260604_handoff.zip` | run=`ARIADNE_AGENTIC_MACHINE_DEEP_AUDIT_CODEX_20260604` | latest=`2026-06-04T08:53:12.086585+00:00`

## Latest Reports

- `harness/runs/CAD_IR_T1_AND_FD_D2_INCLUSION_PROOF_20260707/FINAL_REPORT.md` | run=`CAD_IR_T1_AND_FD_D2_INCLUSION_PROOF_20260707` | status=`UNKNOWN` | latest=`2026-07-08T03:25:03.613498+00:00`
- `harness/runs/CAD_RHINO_IR_ALL_FAMILY_EVIDENCE_INVESTIGATION_20260707/FINAL_REPORT.md` | run=`CAD_RHINO_IR_ALL_FAMILY_EVIDENCE_INVESTIGATION_20260707` | status=`UNKNOWN` | latest=`2026-07-07T08:07:39.200107+00:00`
- `harness/runs/CAD_RHINO_IR_PATENT_FAMILY_DOSSIER_20260707/FINAL_REPORT.md` | run=`CAD_RHINO_IR_PATENT_FAMILY_DOSSIER_20260707` | status=`UNKNOWN` | latest=`2026-07-07T05:52:25.451260+00:00`
- `harness/runs/CAD_RHINO_IR_ONTOLOGY_FULL_TERRAIN_INDEX_20260706/FINAL_REPORT.md` | run=`CAD_RHINO_IR_ONTOLOGY_FULL_TERRAIN_INDEX_20260706` | status=`UNKNOWN` | latest=`2026-07-07T03:05:22.835318+00:00`
- `harness/runs/ARIADNE_AGENTIC_MACHINE_COUNTER_AUDIT_CODEX_20260605/FINAL_REPORT.md` | run=`ARIADNE_AGENTIC_MACHINE_COUNTER_AUDIT_CODEX_20260605` | status=`PASS_WITH_DEFERRAL` | latest=`2026-06-05T09:36:44.113915+00:00`
- `harness/runs/RUN-003-ir-projection-sandbox/FINAL_REPORT.md` | run=`RUN-003-ir-projection-sandbox` | status=`UNKNOWN` | latest=`2026-06-04T09:02:17.990154+00:00`
- `harness/runs/ARIADNE_AGENTIC_MACHINE_DEEP_AUDIT_CODEX_20260604/FINAL_REPORT.md` | run=`ARIADNE_AGENTIC_MACHINE_DEEP_AUDIT_CODEX_20260604` | status=`UNKNOWN` | latest=`2026-06-04T08:52:49.411298+00:00`
- `harness/runs/CAD_TRANSFORMATION_MVP_PHASE_0_5_REGION_ISOLATION_MVP001_20260604/handoff/FINAL_REPORT.md` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_5_REGION_ISOLATION_MVP001_20260604` | status=`UNKNOWN` | latest=`2026-06-04T08:42:26.667825+00:00`
- `harness/runs/ARIADNE_FULL_SCOPE_BASELINE_AUDIT_AND_INDEX_CODEX_20260604/FINAL_REPORT.md` | run=`ARIADNE_FULL_SCOPE_BASELINE_AUDIT_AND_INDEX_CODEX_20260604` | status=`UNKNOWN` | latest=`2026-06-04T08:28:56.758071+00:00`
- `harness/runs/CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604/handoff/FINAL_REPORT.md` | run=`CAD_TRANSFORMATION_MVP_PHASE_0_4_MANUAL_INSPECTION_MVP001_20260604` | status=`UNKNOWN` | latest=`2026-06-04T08:18:23.892325+00:00`

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
