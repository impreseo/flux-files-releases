# Changelog

## Flux Files v1.0.1 (October 2026)

### Media & Video Playback Reliability
- **Direct Local Media Streaming**: Integrated loopback streaming server with full RFC 7233 range-request (`206 Partial Content`) compliance for immediate seek response.
- **Low-Memory Zero-Copy Streaming**: Replaced base64/blob URL allocations with 64 KB chunked streams, reducing memory usage by >90% on large video files.
- **Transmuxing Fallback**: Added graceful fallback transcoding/remuxing pipeline for containers that fail native Chromium playback (MKV, AVI, etc.).
- **Verified Codecs**: Native playback verified for H.264/AVC, VP8, VP9, AV1, AAC, MP3, Opus, FLAC, and WAV.

### Viewer Hardening & Resource Disposal
- **File Type Sniffing**: Multi-tier MIME and extension sniffing with magic-byte verification.
- **Extensionless & Binary Fallback**: Extensionless and unrecognized files cleanly route to Hex or bounded Text preview without freeze.
- **Explicit Lifecycle Cleanup**: Robust component unmount handlers ensure audio/video elements, media streams, and worker threads are destroyed immediately.

### Windows System Theme Synchronization
- **Live Theme Switching**: Real-time synchronization when Windows toggles between Light and Dark modes without restarting the app.
- **Registry Inspection**: Reads `AppsUseLightTheme` directly from Windows Registry for dependable detection across custom theme configurations.

### Product Branding
- Cleaned and standardized application branding: Product Name is strictly `Flux Files`; Publisher is `QUELRAVO`.
- Corrected Add/Remove Programs / Installed Apps display name to `Flux Files`.

---

# Flux Files v1.0.0

## Initial Stable Release

Flux Files v1.0.0 is the official initial stable release of the engineered Windows desktop file manager by **QUELRAVO**, built under the core philosophy: **"FAST. LOCAL. PRIVATE. SIMPLE."**

---

### Highlights
- **100% Local-First & Private**: Operates without cloud services, remote telemetry, network trackers, or mandatory user accounts. Full air-gapped compatibility.
- **8 Explorer View Modes**: Details view with sortable columns, List view, Compact Grid, Medium Icons, Large Icons, Extra Large Icons, Gallery View (carousel with filmstrip), and Miller Column View (cascading multi-tier traversal).
- **Universal In-App Viewer Engine**: Native previewing for over 50 formats including Markdown (GFM), PDF, JSON trees, CSV data grids, 3D meshes (OBJ, STL, GLTF), typography fonts (TTF, OTF, WOFF), syntax-highlighted code, audio waveforms, video, and binary hex.
- **Built-In Editors**: Lightweight editors for plain text, code, live split-pane Markdown, JSON, and CSV with atomic temporary-file writing and dirty state tracking.
- **Archive Studio**: Create, inspect, verify, and extract ZIP, 7Z, and TAR archives with AES-256 password protection and header encryption.
- **Incident-Resistant Local Search Engine**: In-folder zero-latency filtering, multi-drive Everywhere search, advanced query syntax (`ext:`, `type:`, `size:`, `modified:`), and bounded safety caps (50k items / 25 MB database budget) to eliminate UI freezes.
- **Multi-Tab & Dual-Pane Workspaces**: Independent tab strip with pinned tabs, tab reordering, and side-by-side Dual-Pane browsing with one-key cross-pane transfers.
- **Integrated Power Tools**: Batch Renamer with regular expressions, Duplicate Finder with SHA-256 verification, Storage Breakdown disk usage treemaps, and Cryptographic Hash Calculator (MD5, SHA-1, SHA-256, SHA-512).
- **Native Windows Shell Integration**: Real-time fixed and removable USB drive monitoring, Windows Recycle Bin COM integration, safe ejection, extended MAX_PATH (`\\?\`) support, and OLE drag-and-drop.
- **Curated Desktop Aesthetics**: 5 theme presets (Flux Dark Slate, Flux Light, Slate, Graphite, System Sync) and 3 ergonomic density modes (Compact, Default, Comfortable).

---

### Distribution Artifacts
- **NSIS Installer**: `Flux-Files-1.0.0-Setup.exe`
- **Portable Standalone**: `Flux-Files-1.0.0-Portable.exe`
- **Integrity Verification**: `SHA256SUMS.txt`
