# criticalResearch

Public front page for the **Unified Critical Path: Epistemic, Narrative, Causal & Empirical Meta-Synthesis**.

## Deployment model

The canonical public artifact is a zero-runtime-dependency standalone HTML workstation. GitHub Pages uses a tiny first-party loader plus `payload.b64` because the connected repository writer is optimized for bounded text writes. The payload is gzip+base64 of the canonical HTML; the loader decompresses it in the browser, verifies SHA-256 `88d29ace69363c11677fe329f9b6f3f72379c3251b5bb4d95099b8f499212956`, and only then executes the reconstructed document. No third-party JavaScript, CSS, package, CDN, or analytics service is used.

The fully standalone local copy remains a single HTML file and does not depend on this transport packaging.

## Source audit

Nine supplied primary/source papers were directly audited on 2026-09-29. Source-dependent corrections are recorded in `SOURCE_VERIFICATION.md`. The supplied publisher/JSTOR PDFs are **not redistributed** by this public repository.

## Privacy boundary

No personal walking/mobility telemetry, trajectory/location traces, Wi-Fi positioning matrices, GPS/geolocation datasets, or derived movement/OD matrices are included.

## Rights

© 2026 Thrymspire for original synthesis/interface composition and original generated visualization/audio work, subject to underlying rights in cited scholarship. Public static delivery cannot technically prevent copying of client-delivered assets; provenance marking and controlled source publication are used instead of fake DRM.
