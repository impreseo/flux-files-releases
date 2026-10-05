# Flux Files

**FAST. LOCAL. PRIVATE. SIMPLE.**

Flux Files 1.0.0 is the official stable Windows desktop file manager developed by **QUELRAVO**. Engineered for pure speed, local privacy, and daily-driver reliability.

---

![Flux Files Explorer](./assets/screenshots/explorer.png)

---

## Downloads (v1.0.0 Stable)

| Distribution | Download | Details |
|---|---|---|
| **Windows Installer** | [**Flux-Files-1.0.0-Setup.exe**](https://github.com/impreseo/flux-files-releases/releases/download/v1.0.0/Flux-Files-1.0.0-Setup.exe) | Standard NSIS installer, Start Menu & Desktop shortcuts, clean uninstall (~99 MB) |
| **Standalone Portable** | [**Flux-Files-1.0.0-Portable.exe**](https://github.com/impreseo/flux-files-releases/releases/download/v1.0.0/Flux-Files-1.0.0-Portable.exe) | Zero installation required. Run directly from internal storage or USB flash drives (~99 MB) |
| **Integrity Checksums** | [**SHA256SUMS.txt**](./SHA256SUMS.txt) | Cryptographic SHA-256 verification hashes for all distribution binaries |

---

## Why Flux Files?

Traditional file explorers are often bogged down by cloud synchronizers, background telemetry, sluggish context menus, and missing preview decoders. Flux Files is built on an uncompromising local-first architecture:

- ⚡ **Blazing Performance**: 60 FPS virtualized scrolling, instant sorting, and sub-millisecond directory caching.
- 🔒 **100% Local & Private**: Zero analytics, zero cloud accounts, and zero telemetry pings. Runs completely offline.
- 🗂️ **8 Explorer View Modes**: Details, List, Compact Grid, Medium, Large, Extra Large, Gallery Carousel, and Miller Columns.
- 📑 **Tabs & Dual Pane**: Browser-grade tab strip, pinned tabs, and side-by-side Dual-Pane browsing with one-key cross-pane transfers.
- 👁️ **Universal Viewer Engine**: Native instant previewing for 50+ formats—Markdown, PDF, JSON, CSV, 3D meshes (OBJ/STL/GLTF), Fonts, Audio waveforms, Video, and Hex.
- ✏️ **Built-In Atomic Editors**: Edit text, code, live split Markdown, JSON, and CSV safely with crash-proof atomic writes.
- 📦 **Archive Studio**: Create, inspect virtually, extract, and password-protect ZIP, 7Z, and TAR archives with AES-256 encryption.
- 🔍 **Incident-Resistant Local Search**: Parallel per-drive search engine with bounded memory safety budgets (50k items / 25 MB cap) to eliminate UI freezes.
- 🛠️ **Integrated Power Tools**: Multi-regex Batch Renamer, SHA-256 Duplicate Finder, Storage Breakdown treemaps, and Cryptographic Hash Calculator.
- 🪟 **Deep Windows Subsystem**: Real-time fixed drive and dynamic USB detection, Windows Recycle Bin COM integration, extended MAX_PATH support, and OLE drag-and-drop.

---

## Visual Tour

### Fast Everywhere Search
Search across all mounted drives simultaneously with instant filtering, extension matching (`ext:pdf`), format categorization (`type:image`), and size thresholds (`size:>100MB`).

![Everywhere Search](./assets/screenshots/search.png)

---

### Universal In-App Inspection & Previews
Preview Markdown, multi-page PDFs, JSON trees, CSV data grids, typography font waterfalls, 3D CAD meshes, and binary hex dumps directly inside the application by pressing `Space`.

![Universal Viewer](./assets/screenshots/viewer.png)

---

### Live Split-View Markdown & Code Editor
Edit configuration files, source code, and Markdown documents with synchronized live preview and atomic crash-proof disk saving.

![Live Markdown Editor](./assets/screenshots/editor.png)

---

### Dual-Pane & Multi-Tab Workspaces
Browse two directories side-by-side with independent view modes, folder memory, and fast cross-pane transfers (`F5` copy, `F6` move).

![Dual Pane Workspace](./assets/screenshots/workspace.png)

---

### Deep Customization & Privacy Controls
Choose between 5 engineered theme presets (Flux Dark Slate, Flux Light, Slate, Graphite, System Sync), 3 ergonomic density modes, and rebind any keyboard shortcut.

![Settings Panel](./assets/screenshots/settings.png)

---

## Cryptographic Verification

Verify your downloaded binary using PowerShell:

```powershell
Get-FileHash Flux-Files-1.0.0-Setup.exe -Algorithm SHA256
Get-FileHash Flux-Files-1.0.0-Portable.exe -Algorithm SHA256
```

Official SHA-256 Checksums:
```text
7694f82d2857767e366ebf91cc6169f1066d2e73a58dd9b75ff9e20ac190a220  Flux-Files-1.0.0-Portable.exe
d28c85bcc5a7a12802d8872eb61c6d6e507e1e668e3ea2940692088df712b292  Flux-Files-1.0.0-Setup.exe
```

---

## Documentation & Help
- [Quick Start Guide](./docs/QUICK-START.md) — Get up and running in 60 seconds.
- [Privacy Policy](./docs/PRIVACY.md) — Our local-first privacy commitments.
- [Changelog](./CHANGELOG.md) — Version history and release notes.

---

## System Requirements
- **OS**: Windows 10 (64-bit) or Windows 11 (64-bit)
- **CPU**: Intel Core i3 / AMD Ryzen 3 or higher
- **RAM**: 4 GB minimum (8 GB recommended for 3D/4K media workflows)
- **Disk**: 250 MB free space

---

## Attribution & Copyright

Flux Files is proprietary software developed by **QUELRAVO**.  
*Copyright © 2026 QUELRAVO. All rights reserved.*  
*Fast. Local. Private. Simple.*
