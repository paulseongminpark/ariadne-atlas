# Atlas — Current State

> Generated snapshot by atlas-indexer/1.0.0 (P0) at 2026-05-27T05:41:01.952546+00:00.
> **Ariadne Window is the live control surface. Ariadne Atlas is the external knowledge map and evidence index.**
> Atlas is **not** the source of truth and **not** a backup of D:\dev.

## Evidence counts

- indexed files: **4404**
- runs: **264**  |  handoffs: **156**  |  reports: **195**  |  contracts: **496**
- by tier: `{"TIER_2_SELECTED": 462, "TIER_1_MIRROR": 3942}`

## Top kinds

- `run_artifact`: 2611
- `contract_doc`: 486
- `source_meta`: 288
- `handoff_zip`: 156
- `run_files_changed`: 156
- `run_final_report`: 151
- `log_doc`: 148
- `window_doc`: 141
- `run_packet`: 73
- `run_next_recommendation`: 56
- `log_report`: 44
- `contract_other`: 15

## Window safety facts (read from live state)

- raw_command_endpoint: `False`
- raw_sql_endpoint: `False`
- web_ai_direct_file_mutation: `False`
- postgres_role: `control_plane`
- write_surface: `request_only`
- secret_content_reads: `blocked_by_policy`

## Latest

- latest run: `ATLAS_P0_CONTRACT_AND_LOCAL_INDEXER` (2026-05-27T05:41:01.051692+00:00)
- latest handoff: `ARIADNE_SCHEMA_PACK_V0_DOMAIN_CORE_REVIEW_AND_ISOLATED_DRYRUN_20260526_handoff.zip`
- latest report: `harness/runs/ATLAS_P0_CONTRACT_AND_LOCAL_INDEXER/FINAL_REPORT.md` status=`PASS`
