# FLUX FILES — MASTER USER HANDBOOK
**QUELRAVO • "FAST. LOCAL. PRIVATE. SIMPLE."**
*Comprehensive Operating Manual & Knowledge Base*

---

## Table of Contents
1. [Welcome to Flux Files](#1-welcome-to-flux-files)
2. [Understanding the Interface](#2-understanding-the-interface)
3. [Navigation Architecture](#3-navigation-architecture)
4. [Managing Files & Directories](#4-managing-files--directories)
5. [Working With Folders](#5-working-with-folders)
6. [Search & Discovery Engine](#6-search--discovery-engine)
7. [View Modes & Presentation](#7-view-modes--presentation)
8. [Tabs, Panes & Workspaces](#8-tabs-panes--workspaces)
9. [Universal Previews & Viewers](#9-universal-previews--viewers)
10. [Built-In Editors & Live Modification](#10-built-in-editors--live-modification)
11. [Media & Photography Hub](#11-media--photography-hub)
12. [Archive Studio & Compression](#12-archive-studio--compression)
13. [Power Tools Suite](#13-power-tools-suite)
14. [Native Windows Integration](#14-native-windows-integration)
15. [Settings & Customization](#15-settings--customization)
16. [Master Keyboard Shortcuts](#16-master-keyboard-shortcuts)
17. [Universal Supported Formats](#17-universal-supported-formats)
18. [Local-First Privacy & Integrity](#18-local-first-privacy--integrity)
19. [Troubleshooting & Recovery](#19-troubleshooting--recovery)
20. [Advanced Professional Workflows](#20-advanced-professional-workflows)

---

## 1. Welcome to Flux Files
Flux Files is an engineered desktop file manager for Windows designed for speed, local autonomy, privacy, and direct responsiveness. Unlike traditional file managers that slow down when browsing massive directories or require multiple third-party utilities to view files, Flux Files integrates browsing, viewing, editing, archiving, and power tools into a unified desktop environment.

Flux Files operates with a strict **Local-First** model:
- **Zero Cloud Dependencies**: No remote servers or sign-ins.
- **Zero Telemetry**: Your file names, contents, paths, and habits never leave your local PC.
- **Instant Responsiveness**: Virtualized list rendering, asynchronous background file operations, and SQLite-backed search indexing.

---

## 2. Understanding the Interface
![Interface Overview](../00-overview/screenshots/explorer-interface.png)
*Figure H.1: Flux Files primary workspace zones.*

The interface is divided into seven ergonomic zones:
1. **Title Bar & Tab Strip**: Houses draggable tabs, pinned favorites, and window controls.
2. **Menu Bar**: Native desktop menu providing File, Edit, View, Go, Tools, and Help commands.
3. **Toolbar**: Historical travel buttons (`Back`, `Forward`, `Up`), breadcrumb path bar, instant search input, and view mode selectors.
4. **Navigation Sidebar**: Tree showing Virtual Home, This PC, storage volumes, user libraries, and pinned directories.
5. **Explorer Viewport**: Central virtualized work surface supporting 8 distinct viewing layouts.
6. **Docked Preview / Details Pane**: Right-hand collapsible panel providing live document/media inspection and technical metadata.
7. **Status Bar**: Real-time counter displaying item counts, selection metrics, byte sizes, and active zoom level.

---

## 3. Navigation Architecture
Flux Files offers multiple fluid ways to traverse your storage:
- **Interactive Breadcrumbs**: Every folder in the current path is a clickable button. Click any ancestor segment to ascend instantly. Click the arrow delimiter to choose sibling directories.
- **Direct Path Entry (`Ctrl+L` / `Alt+D`)**: Press `Ctrl+L` to switch breadcrumbs into an editable text box. Type or paste absolute Windows paths (e.g. `C:\Users\Developer\Projects`) and press `Enter`.
- **Directional Traversal**:
  - `Alt+Left` / Back Mouse Button: Go back in history.
  - `Alt+Right` / Forward Mouse Button: Go forward in history.
  - `Alt+Up` / `Backspace`: Jump to parent folder on disk.
  - `Alt+Home`: Return to Virtual Home.

---

## 4. Managing Files & Directories
Everyday file management in Flux Files is engineered for rapid, non-blocking execution:
- **Creating**: Press `Ctrl+Shift+N` for New Folder or `Ctrl+Alt+N` for New File. Names are validated in real time against Windows reserved characters.
- **Renaming**: Press `F2` to inline rename. The file name is highlighted while preserving the extension.
- **Copying & Cutting**: `Ctrl+C` copies; `Ctrl+X` cuts (staged items appear translucent). `Ctrl+V` pastes into the active folder.
- **Duplicating**: Press `Ctrl+D` to duplicate selected items in-place instantly.
- **Safe & Permanent Deletion**: Press `Delete` to move items to the Windows Recycle Bin. Press `Shift+Delete` to permanently remove files after confirmation.
- **Operation Center**: All file transfers run asynchronously with pause/resume, transfer speed telemetry (MB/s), and collision resolution.

---

## 5. Working With Folders
- **Folder Memory**: Flux Files automatically remembers your preferred view mode, sorting axis, and column configuration independently for every folder.
- **Pinning**: Right-click any folder and select **Pin to Sidebar** to create a persistent shortcut.
- **Terminal Integration**: Right-click whitespace or any folder and choose **Open Terminal Here** or **Open PowerShell Here**.

---

## 6. Search & Discovery Engine
![Search Everywhere](../05-search/screenshots/search-everywhere.png)
*Figure H.2: Global Everywhere search results across multiple drives.*

Flux Files features an integrated search system:
1. **In-Folder Filter (`Ctrl+F`)**: Type to filter matching items in the active folder with zero latency.
2. **Everywhere Search (`Ctrl+Shift+F`)**: Scans all connected storage drives and user libraries.
3. **Advanced Filter Syntax**:
   - `ext:pdf,docx` — Matches specific file extensions.
   - `type:image`, `type:code`, `type:archive` — Matches format categories.
   - `size:>100MB` — Finds large files.
   - `modified:today` — Finds recently modified files.
4. **Hardened Index Safety**: Capped at 50,000 items and 25 MB database size to guarantee zero UI freezes.

---

## 7. View Modes & Presentation
![Details View](../03-explorer/screenshots/details-view.png)
*Figure H.3: Details View with sortable columns and metadata.*

Switch layouts via the toolbar or dedicated accelerators:
- **Details (`Ctrl+Shift+6`)**: Tabular rows with customizable columns (Name, Date, Type, Size).
- **List (`Ctrl+Shift+5`)**: Compact multi-column list maximizing visible items.
- **Compact Grid (`Ctrl+Shift+4`)**: Dense icon layout for fast visual scanning.
- **Medium Icons (`Ctrl+Shift+3`)**: Balanced 48px icons with visible labels.
- **Large Icons (`Ctrl+Shift+2`)**: 96px icons with image and video thumbnails.
- **Extra Large (`Ctrl+Shift+1`)**: 256px showcase thumbnails for photography review.
- **Gallery (`Ctrl+Shift+7`)**: Media showcase with scrolling thumbnail filmstrip below.
- **Column View (`Ctrl+Shift+8`)**: Miller Columns cascading multi-tier directory browser.

---

## 8. Tabs, Panes & Workspaces
![Dual Pane Split](../11-workspaces/screenshots/dual-pane-split.png)
*Figure H.4: Dual-pane layout enabling side-by-side exploration and file transfers.*

- **Multi-Tab Workspaces**: Press `Ctrl+T` to open a new tab; `Ctrl+W` to close. Drag tabs to reorder.
- **Pinned Tabs**: Right-click a tab and select **Pin Tab** to lock it compactly to the left edge.
- **Dual-Pane Mode**: Select **View → Dual Pane** to split the window into two active explorer panes. Press `F5` to copy selected items directly from the active pane to the target pane.

---

## 9. Universal Previews & Viewers
![Markdown Viewer](../06-viewers/screenshots/viewer-markdown.png)
*Figure H.5: Universal Viewer rendering rich Markdown document.*

Select any file and press `Space` to open the **Universal In-App Viewer**:
- **Markdown & Documents**: Full GFM rendering with tables, task lists, and syntax-highlighted code.
- **PDF Documents**: Native multi-page PDF viewing with page jumping and text search.
- **JSON & Data**: Interactive collapsible JSON tree inspector and CSV tabular grid.
- **3D Meshes & CAD**: Real-time WebGL rendering of OBJ, STL, GLTF models with orbit/pan camera.
- **Typography Fonts**: Interactive specimen waterfall previews for TTF, OTF, WOFF.
- **Databases**: SQLite schema inspector and table viewer.
- **Binary / Hex**: Byte offset inspection with ASCII translation.

---

## 10. Built-In Editors & Live Modification
![Live Markdown Editor](../07-editors/screenshots/editor-markdown-live.png)
*Figure H.6: Live split-view Markdown editor with synchronous preview scrolling.*

Flux Files includes lightweight in-app editors:
- **Text & Code Editor**: Edit configuration files, scripts, and source code with syntax highlighting.
- **Markdown Editor**: Dual-pane split editor with real-time rendered preview.
- **JSON & CSV Editors**: Schema validation for JSON and tabular cell editing for CSVs.
- **Save Safety**: Atomic saving via temporary staging files prevents corrupted writes on system crash.
- **Dirty State Tracking**: Tab headers display dot indicators (`•`) for unsaved edits.

---

## 11. Media & Photography Hub
![Image Viewer](../08-media/screenshots/media-image-zoom.png)
*Figure H.7: High-resolution image zoom and inspection.*

- **Images**: Continuous smooth zoom centered on mouse cursor, panning, 90° rotation (`R`), and 100% scale view (`Ctrl+1`).
- **Video Player**: Hardware-accelerated MP4, WebM, and MKV playback with scrubbing bar.
- **Audio Player**: Interactive audio waveform visualization with ID3 metadata tags.
- **Fullscreen Presentation**: Press `F` or `F11` for borderless fullscreen presentation.

---

## 12. Archive Studio & Compression
![Archive Create Dialog](../09-archives/screenshots/archive-create-dialog.png)
*Figure H.8: Archive Studio creation modal.*

- **Creating Archives**: Compress files into ZIP, 7Z, or TAR with selectable compression levels.
- **AES-256 Encryption**: Password-protect archives with optional header encryption (7Z).
- **Virtual Inspection**: Double-click an archive to explore its internal contents without extracting.
- **Selective Extraction**: Drag individual files out of archives or extract entire packages with collision handling.

---

## 13. Power Tools Suite
![Batch Renamer](../10-power-tools/screenshots/tool-batch-rename.png)
*Figure H.9: Batch Renamer power tool.*

Access built-in power utilities via the **Tools** menu:
- **Batch Renamer**: Apply find-and-replace, regular expressions, numbering, and case changes with live dual-column preview.
- **Duplicate Finder**: Identify identical files using size filtering and SHA-256 cryptographic verification.
- **Storage Breakdown**: Visualize folder disk space usage with interactive hierarchical size trees.
- **Hash Calculator**: Compute and verify MD5, SHA-1, SHA-256, and SHA-512 checksums.
- **File Compare**: Side-by-side visual diffing for code and text files.

---

## 14. Native Windows Integration
Flux Files integrates seamlessly with the Windows operating system:
- Real-time detection and capacity monitoring of fixed drives and removable USB devices.
- Direct integration with the Windows Shell Recycle Bin.
- Native "Open With" dialog and Shell context menu registration.
- Drag-and-drop file interchange between desktop, external apps, and Flux Files.

---

## 15. Settings & Customization
![Settings Modal](../13-settings/screenshots/settings-general.png)
*Figure H.10: Settings preferences modal.*

Open **Settings (`Ctrl+,`)** to customize:
- **Appearance**: Switch between Flux Dark, Flux Light, Slate, Graphite, and System Sync themes.
- **Density**: Choose Compact, Default, or Comfortable spacing.
- **Files & Folders**: Toggle hidden items, system files, and file extensions.
- **Search**: Set crawler boundaries and configure excluded directories.
- **Keyboard**: Remap any keyboard shortcut with conflict detection.

---

## 16. Master Keyboard Shortcuts
Key daily accelerators:
- `Ctrl+P` — Command Palette
- `Ctrl+,` — Settings
- `Ctrl+T` / `Ctrl+W` — New Tab / Close Tab
- `Alt+Left` / `Alt+Right` / `Alt+Up` — History Back / Forward / Parent Folder
- `Ctrl+L` — Focus Address Bar
- `Ctrl+F` — Search Current Folder
- `Ctrl+Shift+F` — Search Everywhere
- `Ctrl+Shift+1` to `8` — Switch View Modes
- `Space` — Universal Quick Preview
- `F2` — Inline Rename
- `Delete` / `Shift+Delete` — Recycle Bin / Permanent Delete
- `Ctrl+S` — Save in Editor

---

## 17. Universal Supported Formats
Flux Files natively handles over 50 formats:
- **Documents**: `.md`, `.pdf`, `.txt`, `.rtf`, `.docx`, `.xlsx`, `.pptx`
- **Images**: `.png`, `.jpg`, `.webp`, `.gif`, `.svg`, `.bmp`, `.ico`, `.tiff`, RAW
- **Media**: `.mp4`, `.webm`, `.mkv`, `.mp3`, `.flac`, `.wav`, `.ogg`, `.m4a`
- **3D & CAD**: `.obj`, `.stl`, `.gltf`, `.glb`, CAD wireframes
- **Code & Data**: `.ts`, `.js`, `.py`, `.rs`, `.go`, `.json`, `.csv`, `.sqlite`
- **Archives**: `.zip`, `.7z`, `.tar`, `.gz`

---

## 18. Local-First Privacy & Integrity
QUELRAVO commits to:
- 100% on-device local computation.
- No network analytics or telemetry.
- Atomic file writes preventing corrupted files on sudden power loss.
- Memory hygiene erasing passwords and sensitive encryption keys immediately after use.

---

## 19. Troubleshooting & Recovery
- **Zero Search Results**: Verify search scope is set to "Everywhere" (`Ctrl+Shift+F`) if the file resides outside the current folder.
- **Locked File Errors**: Close any external application (Word, IDE, Antivirus) that holds an open lock on the file.
- **Search Diagnostics**: Access **Help → Search Diagnostics** to inspect database health and memory usage.

---

## 20. Advanced Professional Workflows
- **Dual-Pane File Sorting**: Use Dual Pane to review two directories side-by-side, using `F5` and `F6` for rapid cross-directory transfers.
- **Mass Photography Organization**: Use Gallery View (`Ctrl+Shift+7`), fullscreen inspection (`F`), and keyboard selection to curate photo sessions.
- **Command Palette Efficiency**: Press `Ctrl+P` to access any application command without touching the mouse.

---
*Flux Files Handbook • QUELRAVO • All Rights Reserved*
