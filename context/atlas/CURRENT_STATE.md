# Ariadne Atlas Current State

generated_at: 2026-05-27T09:25:23.0448319Z
state_freshness: FRESH
stale_after: 2026-05-27T09:55:23.0448319Z
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
- current_state_generated_at: 2026-05-26T09:45:32.379652+00:00
- current_state_age: 23.7 hours old

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

- run_index_rows_source: 307
- handoff_index_rows_source: 191
- report_index_rows_source: 234
- contract_index_rows_source: 504
- window_index_rows_source: 25

## GDrive Publish Status

- gdrive_atlas_root: G:\내 드라이브\Ariadne Atlas
- pointer_folder_present: True
- index_folder_present: True
- handoff_zip_count: 185
- publish_status: SCHEDULED_APPLY_GATED

## Public GitHub Publish Status

- public_repo: https://github.com/paulseongminpark/ariadne-atlas
- local_repo: D:\dev\ariadne-atlas
- public_target: D:\dev\ariadne-atlas\context\atlas
- raw_latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- raw_current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- publish_scope: README.md plus context/atlas pointer and index files

## Latest Runs

- `CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-27T09:25:02.518570+00:00`
- `ARIADNE_DOMAIN_SCHEMA_BOUNDARY_AND_EVOLUTION_REVIEW_V0_20260527` | status=`UNKNOWN` | latest=`2026-05-27T09:16:55.814344+00:00`
- `ATLAS_P4_SCHEDULED_PUBLISH` | status=`PASS_WITH_NOTES` | latest=`2026-05-27T09:13:39.094616+00:00`
- `ARIADNE_AGENT_WRAPPER_BOOT_CONTEXT_AUTOGENERATE_PHASE2_20260527` | status=`PASS` | latest=`2026-05-27T09:10:38.642813+00:00`
- `ATLAS_P2_GDRIVE_PUBLISHER` | status=`PASS` | latest=`2026-05-27T09:10:02.376413+00:00`
- `CAD_IR_BBOX_V02_IDEMPOTENT_STRESS_RERUN_AND_BOUNDED_NEO4J_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-27T08:54:13.139611+00:00`
- `ARIADNE_DB_TO_AGENT_BOOT_CONTEXT_GENERATOR_PHASE1_20260527` | status=`PASS` | latest=`2026-05-27T08:50:05.199382+00:00`
- `ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION` | status=`PASS_WITH_NOTES` | latest=`2026-05-27T08:49:18.339788+00:00`
- `ARIADNE_SCHEMA_PACK_V0_REAL_FIXTURE_BATCH_TRIAL_EXTERNAL_3DM_20260527` | status=`UNKNOWN` | latest=`2026-05-27T08:40:49.772916+00:00`
- `interactive_9b0752e7` | status=`UNKNOWN` | latest=`2026-05-27T08:40:45.632025+00:00`

## Latest Handoffs

- `CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX_handoff.zip` | run=`CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX` | latest=`2026-05-27T09:24:26.215583+00:00`
- `ARIADNE_DOMAIN_SCHEMA_BOUNDARY_AND_EVOLUTION_REVIEW_V0_20260527_handoff.zip` | run=`ARIADNE_DOMAIN_SCHEMA_BOUNDARY_AND_EVOLUTION_REVIEW_V0_20260527` | latest=`2026-05-27T09:16:55.814344+00:00`
- `ATLAS_P4_SCHEDULED_PUBLISH_handoff.zip` | run=`ATLAS_P4_SCHEDULED_PUBLISH` | latest=`2026-05-27T09:13:39.094616+00:00`
- `ARIADNE_AGENT_WRAPPER_BOOT_CONTEXT_AUTOGENERATE_PHASE2_20260527_handoff.zip` | run=`ARIADNE_AGENT_WRAPPER_BOOT_CONTEXT_AUTOGENERATE_PHASE2_20260527` | latest=`2026-05-27T09:10:38.642813+00:00`
- `CAD_IR_BBOX_V02_IDEMPOTENT_STRESS_RERUN_AND_BOUNDED_NEO4J_20260527_CODEX_handoff.zip` | run=`CAD_IR_BBOX_V02_IDEMPOTENT_STRESS_RERUN_AND_BOUNDED_NEO4J_20260527_CODEX` | latest=`2026-05-27T08:54:13.139098+00:00`
- `ARIADNE_DB_TO_AGENT_BOOT_CONTEXT_GENERATOR_PHASE1_20260527_handoff.zip` | run=`ARIADNE_DB_TO_AGENT_BOOT_CONTEXT_GENERATOR_PHASE1_20260527` | latest=`2026-05-27T08:50:05.199382+00:00`
- `ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION_handoff.zip` | run=`ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION` | latest=`2026-05-27T08:49:18.339788+00:00`
- `ARIADNE_SCHEMA_PACK_V0_REAL_FIXTURE_BATCH_TRIAL_EXTERNAL_3DM_20260527_handoff.zip` | run=`ARIADNE_SCHEMA_PACK_V0_REAL_FIXTURE_BATCH_TRIAL_EXTERNAL_3DM_20260527` | latest=`2026-05-27T08:40:49.772916+00:00`
- `CAD_IR_BBOX_V02_IDEMPOTENCY_AND_DIVERGENCE_REVIEW_20260527_CODEX_handoff.zip` | run=`CAD_IR_BBOX_V02_IDEMPOTENCY_AND_DIVERGENCE_REVIEW_20260527_CODEX` | latest=`2026-05-27T08:38:06.546556+00:00`
- `CAD_IR_BBOX_V02_CROSS_DOCUMENT_STRESS_20260527_CODEX_handoff.zip` | run=`CAD_IR_BBOX_V02_CROSS_DOCUMENT_STRESS_20260527_CODEX` | latest=`2026-05-27T08:20:55.254592+00:00`

## Latest Reports

- `harness/runs/CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_STAGE1_STAGE2_FULL_AUTORESEARCH_20260527_CODEX` | status=`PASS` | latest=`2026-05-27T09:24:25.076047+00:00`
- `harness/runs/ARIADNE_DOMAIN_SCHEMA_BOUNDARY_AND_EVOLUTION_REVIEW_V0_20260527/FINAL_REPORT.md` | run=`ARIADNE_DOMAIN_SCHEMA_BOUNDARY_AND_EVOLUTION_REVIEW_V0_20260527` | status=`UNKNOWN` | latest=`2026-05-27T09:16:05.402038+00:00`
- `harness/runs/ATLAS_P4_SCHEDULED_PUBLISH/FINAL_REPORT.md` | run=`ATLAS_P4_SCHEDULED_PUBLISH` | status=`PASS_WITH_NOTES` | latest=`2026-05-27T09:13:13.077810+00:00`
- `harness/runs/ATLAS_P4_SCHEDULED_PUBLISH/handoff/bundle/FINAL_REPORT.md` | run=`ATLAS_P4_SCHEDULED_PUBLISH` | status=`PASS_WITH_NOTES` | latest=`2026-05-27T09:13:13.077810+00:00`
- `harness/runs/ARIADNE_AGENT_WRAPPER_BOOT_CONTEXT_AUTOGENERATE_PHASE2_20260527/FINAL_REPORT.md` | run=`ARIADNE_AGENT_WRAPPER_BOOT_CONTEXT_AUTOGENERATE_PHASE2_20260527` | status=`PASS` | latest=`2026-05-27T09:10:26.970113+00:00`
- `harness/runs/CAD_IR_BBOX_V02_IDEMPOTENT_STRESS_RERUN_AND_BOUNDED_NEO4J_20260527_CODEX/FINAL_REPORT.md` | run=`CAD_IR_BBOX_V02_IDEMPOTENT_STRESS_RERUN_AND_BOUNDED_NEO4J_20260527_CODEX` | status=`PASS_STRONG` | latest=`2026-05-27T08:54:06.533819+00:00`
- `harness/runs/ARIADNE_DB_TO_AGENT_BOOT_CONTEXT_GENERATOR_PHASE1_20260527/FINAL_REPORT.md` | run=`ARIADNE_DB_TO_AGENT_BOOT_CONTEXT_GENERATOR_PHASE1_20260527` | status=`PASS` | latest=`2026-05-27T08:49:30.476065+00:00`
- `harness/runs/ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION/FINAL_REPORT.md` | run=`ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION` | status=`PASS_WITH_NOTES` | latest=`2026-05-27T08:49:17.903771+00:00`
- `harness/runs/ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION/handoff/bundle/FINAL_REPORT.md` | run=`ATLAS_P3E_POINTER_QUALITY_AND_DB_PROJECTION` | status=`PASS_WITH_NOTES` | latest=`2026-05-27T08:49:17.903771+00:00`
- `harness/runs/ARIADNE_SCHEMA_PACK_V0_REAL_FIXTURE_BATCH_TRIAL_EXTERNAL_3DM_20260527/FINAL_REPORT.md` | run=`ARIADNE_SCHEMA_PACK_V0_REAL_FIXTURE_BATCH_TRIAL_EXTERNAL_3DM_20260527` | status=`UNKNOWN` | latest=`2026-05-27T08:40:03.093604+00:00`

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
