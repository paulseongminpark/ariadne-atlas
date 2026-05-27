# Ariadne Atlas Status

generated_at: 2026-05-27T23:10:17.3806820Z
stale_after: 2026-05-27T23:40:17.3806820Z
atlas_version: ATLAS_P4_SCHEDULED_PUBLISH
status: SCHEDULED_PUBLISH_READY

## Layers

- Window status: ok
- Window health: ok
- Local build: gated by atlas_scheduled_publish.ps1
- GDrive publish: gated by -Apply unless -SkipGDrive
- Public GitHub publish: gated by -Apply, clean-tree check, and public safety scan
- Scheduled task: AriadneAtlasScheduledPublish

## Raw Pointers

- latest_pointer: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/LATEST_POINTER.md
- current_state: https://raw.githubusercontent.com/paulseongminpark/ariadne-atlas/main/context/atlas/CURRENT_STATE.md
- schedule_status_json: ariadne:/operator/atlas/public/ATLAS_SCHEDULE_STATUS.json
