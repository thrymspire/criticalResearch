# Unified Critical Path — source-audited standalone build

## Public deployment
`index.html` is a small first-party GitHub Pages loader. It fetches eight same-origin payload chunks, reconstructs the canonical public artifact in-browser, verifies SHA-256 `271a0e0b1ef29c1c72b01fd825bc47920a56c4919e0c39abe39052be863cef8e`, and only then executes it. This transport exists because the connected repository writer is optimized for bounded text writes; it is not an application dependency.

The reconstructed workstation remains zero-runtime-dependency: no framework, package manager, CDN, analytics service, or external asset request is required after load.

## Local build
The complete local-only standalone copy remains a single HTML file and is distributed separately rather than committed here. It opens directly in a modern browser with no server or package install.

## Performance repairs
The original script had a fatal duplicate `appState` declaration and several undefined runtime elements/functions. The recovered build repairs those, replaces independent unbounded canvas loops with visibility-aware scheduling, replaces the full-screen animated plasma canvas with a pointer-responsive CSS material field, defers offscreen sections with `content-visibility`, and keeps the glowing purple-glass visual system.

## 2026-09-29 primary-source audit
Nine supplied source documents were checked directly. Unsupported thresholds, incorrect sample sizes/statistics, wrong author lists, and source-attribution errors were corrected or explicitly reclassified as derived/illustrative rather than silently deleted. The previous Sussman ERP material is preserved as a **legacy synthetic visualization**, not misrepresented as data from the supplied behavioral study.

See `SOURCE_VERIFICATION.md` for the audit ledger.

## Public corpus handling
The public artifact preserves the same 143-record research index, categories, metrics, and filtering, but withholds all 143 extracted publisher/source excerpts and removes the private Windows source path. The supplied PDFs are not redistributed.

## Privacy boundary
No personal walking/mobility telemetry, trajectory/location traces, Wi-Fi positioning matrices, GPS/geolocation datasets, or derived movement/OD matrices are included.

## Remaining source gate
The Linehan/DBT TIPP section is preserved, but its numerical heart-rate/HRV/cortisol/BOLD/timing values are explicitly synthetic until the exact primary DBT source is audited.

## Rights and provenance
© 2026 Thrymspire for original synthesis/interface composition and original generated visualization/audio work, subject to underlying rights in cited scholarship. Public static delivery cannot technically prevent copying of client-delivered assets. Provenance marking, rights notices, export metadata, and source separation are used instead of fake DRM.

See `ASSET_RIGHTS.md`, `THIRD_PARTY_NOTICES.md`, and `integrity-manifest.json`.
