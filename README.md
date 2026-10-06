# Flux Files

**Fast. Local. Private. Simple.**

An official release distribution by **QUELRAVO**.  
High-performance, local-first Windows desktop file manager.

---

## Flux Files 1.0.0

Flux Files is engineered from the ground up for Windows 10 and Windows 11. Designed for users who demand instant responsiveness, airtight privacy, and built-in professional utilities, Flux Files eliminates the sluggishness, cloud bloat, and telemetry of traditional file explorers.

![Flux Files Workspace](screenshots/explorer.png)

---

## Official Downloads (v1.0.0)

| Package | Filename | Size | SHA-256 Checksum | Download |
|---|---|---|---|---|
| **Windows Installer** | `Flux-Files-1.0.0-Setup.exe` | 99.74 MB | `0059ca4772552f8fd554e56dab40b810bcb786607145ea52b85d78fb9cca0582` | [Download Installer](https://github.com/impreseo/flux-files-releases/releases/download/v1.0.0/Flux-Files-1.0.0-Setup.exe) |
| **Standalone Portable** | `Flux-Files-1.0.0-Portable.exe` | 99.44 MB | `4cd9c174947f8ae264e7cd7c94575fcce9390812273f69f80043cdcca3e88be5` | [Download Portable](https://github.com/impreseo/flux-files-releases/releases/download/v1.0.0/Flux-Files-1.0.0-Portable.exe) |
| **Integrity Checksums** | `SHA256SUMS.txt` | 189 B | `140b5776cbddce2e98e64c58560af137bf43878cf96e9098c3962ea59a7c0925` | [Download Hashes](https://github.com/impreseo/flux-files-releases/releases/download/v1.0.0/SHA256SUMS.txt) |

> Direct Release Page: **[GitHub Release v1.0.0](https://github.com/impreseo/flux-files-releases/releases/tag/v1.0.0)**

---

## Verification & Integrity Check

You can verify the cryptographic integrity of your download in PowerShell:

```powershell
# Verify Setup Installer
Get-FileHash -Algorithm SHA256 .\Flux-Files-1.0.0-Setup.exe

# Verify Portable Executable
Get-FileHash -Algorithm SHA256 .\Flux-Files-1.0.0-Portable.exe
```

Expected Hashes:
```text
0059ca4772552f8fd554e56dab40b810bcb786607145ea52b85d78fb9cca0582  Flux-Files-1.0.0-Setup.exe
4cd9c174947f8ae264e7cd7c94575fcce9390812273f69f80043cdcca3e88be5  Flux-Files-1.0.0-Portable.exe
```

---

## Core Capabilities

### ⚡ Blazing Fast Explorer
- **8 Layout Engines**: Details, List, Compact Grid, Medium Icons, Large Icons, Extra Large Icons, Gallery View (media carousel with filmstrip), and Miller Column View.
- **Virtualized Rendering**: Navigates folders containing tens of thousands of items at 60 FPS.
- **Interactive Breadcrumbs**: Clickable directory tokens with sibling dropdown menus, plus instant `Ctrl+L` direct path entry.

### 🔍 Incident-Resistant Search Engine
![Everywhere Search](screenshots/search.png)
- **Instant In-Folder Filter**: Type in the search box (`Ctrl+F`) for instantaneous memory filtering.
- **Everywhere Global Search**: Multi-drive SQLite-backed indexed search (`Ctrl+Shift+F`) across all mounted volumes.
- **Syntax Operators**: Precise filtering with `ext:pdf`, `type:image`, `size:>100MB`, and wildcard expressions.

### 👁️ Universal In-App File Viewers
![Markdown Viewer](screenshots/viewer.png)
Inspect over 50 formats immediately with **Spacebar** without launching heavy third-party software:
- **Documents & Code**: GitHub Flavored Markdown, syntax-highlighted code (TS, JS, Python, Rust, Go, C/C++), line numbers, and PDF multi-page viewing.
- **Data & Tables**: Collapsible JSON tree explorer and virtualized CSV/TSV spreadsheet data grid.
- **3D & Vector CAD**: Interactive WebGL mesh orbit/pan/zoom (OBJ, STL, GLTF, GLB) and 2D DXF CAD wireframes.
- **Typography & Forensic**: Waterfall font specimen preview (TTF, OTF, WOFF) and 16-byte aligned binary Hexadecimal viewer.

### ✍️ Integrated Atomic Editors
![Live Markdown Editor](screenshots/editor.png)
- In-place text and source code editing with find and replace (`Ctrl+F`).
- Live split-pane Markdown editor with synchronized HTML preview.
- **Atomic Safe Writes**: Writes to temporary staging files before replacing on disk, preventing file corruption during power failures.

### 📦 Virtual Archive Studio
- Browse inside ZIP, 7Z, TAR, and GZ archives as virtual folders without unpacking.
- Multi-threaded archive extraction with collision handling (Prompt, Overwrite, Skip).
- Create compressed archives with selectable compression levels (Store, Fast, Normal, Maximum).

### 🪟 Multitasking Workspaces & Dual Pane
![Dual Pane Workspace](screenshots/workspace.png)
- Multi-tab navigation with pinned tabs and session restoration.
- Side-by-side **Dual-Pane Split View** (`Ctrl+Alt+2`) for seamless drag-and-drop transfers between directories.

### 🛠️ Built-In Power Tools
![Power Tools](screenshots/tools.png)
- **Batch Renamer**: Mass renaming tool with find/replace, prefixes, suffixes, case conversion, and numbering.
- **Storage Analyzer**: Visual volume capacity breakdown to identify disk hogs.
- **Duplicate Finder**: Multi-stage byte and SHA-256 duplicate identification.
- **Cryptographic Hashes**: On-demand calculation of MD5, SHA-1, and SHA-256 checksums with match verification.

### 🛡️ 100% Local-First Privacy Guarantee
- **Zero Cloud Dependencies**: No user accounts, no subscriptions, no cloud syncing.
- **Zero Telemetry**: No analytics beacons, no path snooping, no diagnostic tracking.
- **Air-Gapped Ready**: Runs identically with or without an active internet connection.

---

## Documentation

- 🚀 [**Quick Start Guide**](docs/QUICK-START.md) — 10-step onboarding visual guide.
- 📖 [**Full User Handbook**](docs/FLUX-FILES-USER-HANDBOOK.md) — Comprehensive 20-chapter manual.
- ⌨️ [**Keyboard Shortcuts**](docs/SHORTCUTS.md) — Master accelerator cheat-sheet.
- 🛡️ [**Privacy & Security Architecture**](docs/PRIVACY.md) — Local-first verification details.
- 📋 [**Release Changelog**](CHANGELOG.md) — Version release notes.

---

## System Requirements

- **Operating System**: Windows 10 or Windows 11 (64-bit)
- **Architecture**: x64
- **Memory**: 4 GB RAM minimum (8 GB recommended)
- **Storage**: 250 MB available disk space

---

## Publisher & Support

Published by **QUELRAVO**.  
*Official Public Distribution Repository*: [https://github.com/impreseo/flux-files-releases](https://github.com/impreseo/flux-files-releases)  
Copyright © 2026 **QUELRAVO**. All rights reserved.
