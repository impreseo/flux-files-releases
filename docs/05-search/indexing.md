# Indexing Architecture & Safety Controls

## Overview
Flux Files maintains an embedded SQLite database (via sql.js) to store file metadata for instant search retrieval.

## Hardened Safety Architecture
Following deep forensic validation, the indexing crawler is governed by strict bounds:
- **Maximum Index Items**: 50,000 entries max.
- **Maximum Database Size**: 25 MB max export threshold.
- **Background Crawler**: Runs at idle priority with throttled I/O to ensure host CPU remains cool and responsive.
- **Excluded Paths**: System directories (`C:\Windows`, `node_modules`, `.git`, `$Recycle.Bin`, `AppData\Local\Temp`) are excluded by default.

## Re-indexing
Users can trigger a full index rebuild via **Settings → Search → Rebuild Index** or through the Search Diagnostics modal.

## Related
- [Search Diagnostics](./search-diagnostics.md)
- [Search Settings](../13-settings/search-settings.md)
