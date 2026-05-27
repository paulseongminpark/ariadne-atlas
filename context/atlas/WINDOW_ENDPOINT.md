# Ariadne Window Endpoint

generated_at: 2026-05-27T08:46:37.1571127Z
atlas_version: ATLAS_P3E_PUBLIC_POINTER_QUALITY_2026-05-27

## Stable Endpoint

- base: https://ariadne-window.paulseongminpark.workers.dev
- status: https://ariadne-window.paulseongminpark.workers.dev/status
- health: https://ariadne-window.paulseongminpark.workers.dev/health
- current_state: https://ariadne-window.paulseongminpark.workers.dev/state/current
- mcp: https://ariadne-window.paulseongminpark.workers.dev/mcp

## Live Status Snapshot

- status: ok
- health: ok
- service: ariadne-window-workers-dev
- workers_dev_entrypoint: True
- remote_mcp_protocol_versions: 2025-03-26, 2025-06-18

## Public Use

Read /status, /health, and /state/current first. Use /mcp only through clients that understand the Ariadne Window request-only safety model.

## Safety Snapshot

- raw_command: absent
- raw_sql: absent
- direct_file_mutation: absent
- approval_endpoint: blocked
- write_surface: request-only
