# Ariadne Atlas — Public Pointer Layer

**Ariadne Window is the live control surface. Ariadne Atlas is the external knowledge map and evidence index.**

This repository is the **public, pointer/index-only** layer of Ariadne Atlas. It exists so that
web-based AI clients can read small, stable, AI-readable context and index files over plain
`raw.githubusercontent.com` URLs **without authentication**.

## What this repo is

- A tiny set of Markdown pointers and JSON-Lines indexes describing Ariadne's runs, handoffs,
  reports, contracts, and Window state.
- Updated by the Ariadne Atlas publisher (`atlas_publish_github`).

## What this repo is NOT

This repository **does not** contain, and must never contain:

- secrets, tokens, credentials, or `.env` files;
- handoff zips or any archives (`*.zip`, `*.tar.gz`, `*.7z`);
- live database files (`*.db`, `*.sqlite`, `*.duckdb`);
- binaries (`*.exe`, `*.dll`) or CAD/BIM source (`*.3dm`, `*.dwg`, `*.dxf`, `*.gh`);
- bulk run folders, wholesale logs, or copies of the private orchestration repo.

## Main entry

➡️ **[`context/atlas/LATEST_POINTER.md`](context/atlas/LATEST_POINTER.md)** — start here.

## The three layers

| Layer | Role | Location |
|-------|------|----------|
| **Window** | live control surface | `https://ariadne-window.paulseongminpark.workers.dev/state/current` |
| **Atlas (GitHub)** | small stable pointer layer (this repo) | `context/atlas/` |
| **Atlas (Google Drive)** | bulk evidence archive | Google Drive → `Ariadne Atlas` |

## Recommended AI read order

1. **Ariadne Window** live state — `https://ariadne-window.paulseongminpark.workers.dev/state/current`
2. **Public Atlas** — `context/atlas/LATEST_POINTER.md`
3. **Public Atlas** — `context/atlas/CURRENT_STATE.md`
4. **GDrive Atlas** archive — bulk evidence references (see `context/atlas/*_INDEX.jsonl`)

## Contents of `context/atlas/`

- `LATEST_POINTER.md`, `CURRENT_STATE.md`, `WINDOW_ENDPOINT.md`, `NEXT_ACTIONS.md`, `ATLAS_STATUS.md`
- `RUN_INDEX.jsonl`, `HANDOFF_INDEX.jsonl`, `REPORT_INDEX.jsonl`, `CONTRACT_INDEX.jsonl`, `WINDOW_INDEX.jsonl`
- `GITHUB_POINTER_MANIFEST.jsonl`, `README.md`

Bulk evidence lives in the Google Drive **Ariadne Atlas** folder; this repo only points at it.
