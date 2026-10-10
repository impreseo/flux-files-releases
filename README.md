# Flux Files

**FAST. LOCAL. PRIVATE. SIMPLE.**

---

## Flux Files v1.2.0
*Official Stable Windows Release by **QUELRAVO**.*

Flux Files is a high-performance desktop file manager engineered from the ground up for Windows 10 and Windows 11. Designed for users who demand instant responsiveness, complete local privacy, and built-in professional utilities, Flux Files eliminates the sluggishness, cloud bloat, and telemetry of traditional file explorers.

![Flux Files Workspace](assets/screenshots/explorer.png)

---

## Download Flux Files v1.2.0

### Windows Setup Installer (Recommended)
Complete Windows installer with Start Menu shortcuts, uninstaller, and shell integration.
- 📦 **[Download Flux-Files-1.2.0-Setup.exe](https://github.com/impreseo/flux-files-releases/releases/download/v1.2.0/Flux-Files-1.2.0-Setup.exe)** *(116.53 MB)*

### Portable Standalone
Zero-installation standalone executable. Run immediately from local storage or USB drives.
- 🚀 **[Download Flux-Files-1.2.0-Portable.exe](https://github.com/impreseo/flux-files-releases/releases/download/v1.2.0/Flux-Files-1.2.0-Portable.exe)** *(116.23 MB)*

### Cryptographic Checksums (SHA-256)
Verify download integrity against the official checksums:
- 🛡️ **[SHA256SUMS.txt](https://github.com/impreseo/flux-files-releases/releases/download/v1.2.0/SHA256SUMS.txt)**

```text
64b387e78f61b0bfc4e4e18ec349ecf0e43595ab5168343258470d3a425cf691  Flux-Files-1.2.0-Portable.exe
c2d99f1e542ffd5dbcf1d129c97394c22339c1138603357ab211d33a5c5b4335  Flux-Files-1.2.0-Setup.exe
```

PowerShell verification command:
```powershell
Get-FileHash -Algorithm SHA256 .\Flux-Files-1.2.0-Setup.exe
```

---

## What's New in v1.2.0

### 1. Enterprise Multi-Format Archive Engine
- **Universal Format Support**: Full support for ZIP, 7Z (LZMA2 multi-threaded), TAR, TAR.GZ, TAR.BZ2, TAR.XZ, GZ, BZ2, XZ, plus honest read-only support for RAR/RAR5 and ISO containers.
- **Zero-Payload Hierarchical Browsing**: Instant central directory tree parsing without extracting multi-gigabyte file payloads to disk.
- **Sandboxed Extraction**: Complete path traversal sanitization with destination jail containment. Supports Extract Here, Extract to New Folder, Extract to Selected, and selective subset extraction with conflict resolution policies (`replace`, `skip`, `keepBoth`, `cancel`).
- **Cryptographic Archive & Folder Comparison Engine**: Zero-disk streaming comparison comparing Archive vs Archive, Archive vs Folder, and Folder vs Folder. Files with matching sizes are verified using streaming SHA-256 hashes without writing uncompressed data to disk.
- **Security Hardening**: Elimination of Windows reserved DOS device hazards (`CON`, `PRN`, `AUX`, `NUL`), null-byte poisoning mitigation, and multi-tier decompression bomb heuristics.

### 2. Universal File Viewers & Media Reliability
- **Smooth Video Playback**: Fully verified continuous hardware-accelerated video playback with fluid progression beyond the initial frame on MP4, MKV, and WebM containers.
- **High-Performance Audio Player**: Responsive audio visualization and playback with format inspection.
- **Mozilla PDF.js Engine**: Background web worker PDF rendering directly to HTML5 canvas with dynamic zoom, multi-page jump, rotation, and inline password decryption.
- **Zero-Lag Image & Code Viewers**: Sub-25ms image rendering and streaming syntax viewing for large source files.

### 3. Whole-Application Performance & Scalability
- **50,000-File Directory Navigation**: Verified 60 FPS virtualized rendering with bounded DOM node counts (~40–60 elements) across dense folder collections.
- **Sub-Millisecond Search Cancellation**: Instant 0.25ms cancellation latency halting asynchronous worker pools immediately upon user request.
- **High-Speed Thumbnails**: 0.19ms cold generation and 0.02ms warm cache hit retrieval per item.
- **Memory Stability**: Zero unbounded heap growth across extended browsing and search sessions.

---

## Core Capabilities

### ⚡ Blazing Fast Explorer
- **8 Layout Engines**: Details, List, Compact Grid, Medium Icons, Large Icons, Extra Large Icons, Gallery View (media carousel with filmstrip), and Miller Column View.
- **Virtualized Rendering**: Handles directories containing tens of thousands of items at a silky 60 FPS.
- **Interactive Breadcrumbs**: Clickable directory tokens with sibling dropdown menus, plus instant `Ctrl+L` direct path entry.

### 🔍 Incident-Resistant Search Engine
![Everywhere Search](assets/screenshots/search.png)
- **Instant In-Folder Filter**: Type in the search box (`Ctrl+F`) for instantaneous memory filtering.
- **Everywhere Global Search**: Multi-drive SQLite-backed indexed search (`Ctrl+Shift+F`) across all mounted volumes.
- **Syntax Operators**: Precise filtering with `ext:pdf`, `type:image`, `size:>100MB`, and wildcard expressions.

### 👁️ Universal In-App File Viewers
![Markdown Viewer](assets/screenshots/viewer.png)
Inspect over 50 formats immediately with **Spacebar** without launching heavy third-party software:
- **Documents & Code**: GitHub Flavored Markdown, syntax-highlighted code (TS, JS, Python, Rust, Go, C/C++), line numbers, and PDF multi-page viewing.
- **Data & Tables**: Collapsible JSON tree explorer and virtualized CSV/TSV spreadsheet data grid.
- **3D & Vector CAD**: Interactive WebGL mesh orbit/pan/zoom (OBJ, STL, GLTF, GLB) and 2D DXF CAD wireframes.
- **Typography & Forensic**: Waterfall font specimen preview (TTF, OTF, WOFF) and 16-byte aligned binary Hexadecimal viewer.

### ✍️ Integrated Atomic Editors
![Live Markdown Editor](assets/screenshots/editor.png)
- In-place text and source code editing with find and replace (`Ctrl+F`).
- Live split-pane Markdown editor with synchronized HTML preview.
- **Atomic Safe Writes**: Writes to temporary staging files before replacing on disk, preventing file corruption during power failures.

### 📦 Virtual Archive Studio
- Browse inside ZIP, 7Z, TAR, and GZ archives as virtual folders without unpacking.
- Multi-threaded archive extraction with collision handling (Prompt, Overwrite, Skip, Auto-Rename).
- Create compressed archives with selectable compression levels (Store, Fast, Normal, Maximum).

### 🪟 Multitasking Workspaces & Dual Pane
![Dual Pane Workspace](assets/screenshots/workspace.png)
- Multi-tab navigation with pinned tabs and session restoration.
- Side-by-side **Dual-Pane Split View** (`Ctrl+Alt+2`) for seamless drag-and-drop transfers between directories.

### 🛠️ Built-In Power Tools
![Power Tools](assets/screenshots/tools.png)
- **Batch Renamer**: Mass renaming tool with find/replace, prefixes, suffixes, case conversion, and numbering.
- **Storage Analyzer**: Visual volume capacity breakdown to identify disk hogs.
- **Duplicate Finder**: Multi-stage byte and SHA-256 duplicate identification.
- **Cryptographic Hashes**: On-demand calculation of MD5, SHA-1, SHA-256, and SHA-512 checksums with match verification.

### 🛡️ 100% Local-First Privacy Guarantee
- **Zero Cloud Dependencies**: No user accounts, no subscriptions, no cloud syncing.
- **Zero Telemetry**: No analytics beacons, no path snooping, no diagnostic tracking.
- **Air-Gapped Ready**: Runs identically with or without an active internet connection.

---

## Release History

- **v1.2.0 (Current Stable Release)**: Unified multi-format archive engine (ZIP, 7Z LZMA2, TAR, RAR, ISO), zero-disk streaming archive comparison, verified whole-application performance (50K directory sorting in 11ms, 0.25ms search cancellation, 60 FPS virtualization), video playback freeze elimination, and evidence-backed native engine integration roadmap.
- **v1.0.2**: Embedded Mozilla PDF.js viewer overhaul, system dark/light mode synchronization as default, archive creation error diagnostics, and flex layout truncation hardening.
- **v1.0.1**: Portable executable packaging, updater stabilization, enhanced drive hotplug detection, and documentation suite expansion.
- **v1.0.0**: Initial official stable release. Foundational high-density explorer, 8 layout engines, multi-tab and dual-pane split workspace, Everywhere search, in-app file viewers, batch renamer, and local-first architecture.

---

## System Requirements

- **Operating System**: Windows 10 or Windows 11 (64-bit `x64`)
- **Processor**: 64-bit Intel, AMD, or compatible processor
- **Memory**: 4 GB RAM minimum (8 GB recommended)
- **Storage**: 250 MB available disk space

---

## Publisher & Support

Published by **QUELRAVO**.  
*Official Release Repository*: [https://github.com/impreseo/flux-files-releases](https://github.com/impreseo/flux-files-releases)  
*Source Code Repository*: [https://github.com/impreseo/flux-files](https://github.com/impreseo/flux-files)  
Copyright © 2026 **QUELRAVO**. All rights reserved.
