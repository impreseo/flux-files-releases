# Flux Files — Feature Catalog & Architecture Guide
**COMPREHENSIVE DIRECTORY OF ALL IMPLEMENTED CAPABILITIES**

---

## Architecture Summary
Flux Files combines native Windows filesystem execution with an extensible Electron + React + TypeScript presentation layer.

---

## 1. Explorer & Workspaces
- **8 Layout Modes**: Details, List, Compact Grid, Medium Icons, Large Icons, Extra Large Icons, Gallery View, and Miller Columns. [View Modes Guide](../03-explorer/view-modes.md)
- **Virtual Home**: Unified dashboard of storage drives, user hubs, and recent activity. [Home Hub](../03-explorer/home.md)
- **This PC**: Physical drive volume monitor with storage meters. [This PC](../03-explorer/this-pc.md)
- **Multi-Tab Workspaces**: Reorderable tabs, pinned tabs, and persistent folder history. [Tabs Guide](../01-navigation/tabs.md)
- **Dual-Pane Mode**: Side-by-side independent navigation with fast cross-pane transfers. [Dual-Pane View](../11-workspaces/dual-pane.md)
- **Folder Memory**: Automatic preservation of view modes, sorting, and column widths per folder. [Folder Memory](../11-workspaces/folder-memory.md)

---

## 2. File Operations & Operation Center
- **Asynchronous Engine**: Non-blocking transfers running in dedicated background workers. [Operation Center](../04-file-operations/operation-center.md)
- **Collision Resolution**: Overwrite, skip, auto-rename ("Keep Both"), and batch resolution. [Conflicts Guide](../04-file-operations/conflicts.md)
- **Safe & Permanent Deletion**: Windows Recycle Bin integration and bypass modes. [Delete Guide](../04-file-operations/delete.md)
- **File Metadata & Attributes**: Comprehensive properties dialog with timestamps and hash computation. [Properties Guide](../04-file-operations/properties.md)

---

## 3. Search & Discovery Engine
- **In-Folder Filter**: Zero-latency item filtering. [Search Overview](../05-search/search-overview.md)
- **Everywhere Search**: Cross-partition global search. [Global Search](../05-search/global-search.md)
- **Syntax Engine**: Filter by `ext:`, `type:`, `size:`, `modified:`, and exact phrase. [Filters Guide](../05-search/filters.md)
- **Hardened Index Limits**: Safe budget capped at 50,000 files / 25 MB database size. [Indexing Architecture](../05-search/indexing.md)
- **Diagnostics Console**: Real-time crawler metrics and database telemetry. [Search Diagnostics](../05-search/search-diagnostics.md)

---

## 4. Universal Viewer Engine
- **Markdown & Documents**: Full GFM rendering with tables, task lists, and syntax blocks. [Markdown Viewer](../06-viewers/markdown.md)
- **PDF Viewer**: Multi-page viewer with search and thumbnail sidebar. [PDF Viewer](../06-viewers/pdf.md)
- **Data & Tables**: Collapsible JSON tree inspector and CSV data grid. [JSON Viewer](../06-viewers/json.md)
- **3D & CAD**: Real-time WebGL rendering of OBJ, STL, GLTF models and CAD wireframes. [3D Model Viewer](../06-viewers/3d.md)
- **Typography**: Specimen waterfall previews for TTF, OTF, WOFF. [Font Viewer](../06-viewers/fonts.md)
- **Binary / Hex**: Byte inspection with decoded scalar data types. [Binary Viewer](../06-viewers/binary.md)
- **Databases**: SQLite schema inspector and table viewer. [Data Formats](../16-supported-formats/data.md)

---

## 5. Built-In Editors
- **Text & Code Editor**: Lightweight syntax-highlighted editor with auto-indent. [Code Editor](../07-editors/code-editor.md)
- **Live Markdown Editor**: Split-pane synchronous editing with real-time preview. [Markdown Editor](../07-editors/markdown-editor.md)
- **JSON & CSV Editors**: Syntax linting and tabular spreadsheet cell editing. [JSON Editor](../07-editors/json-editor.md)
- **Atomic Save Pipeline**: Crash-proof writes via temporary staging files. [Save System](../07-editors/save-system.md)

---

## 6. Media & Audio-Visual
- **Image Inspection**: Continuous zoom, panning, rotation, and EXIF extraction. [Image Viewer](../08-media/image-viewer.md)
- **Video Player**: Hardware-accelerated playback with frame scrubbing. [Video Player](../08-media/video-player.md)
- **Audio Player**: Interactive waveform visualizer with ID3 tag parsing. [Audio Player](../08-media/audio-player.md)
- **Fullscreen Presentation**: Borderless fullscreen mode for media review. [Fullscreen Mode](../08-media/fullscreen.md)

---

## 7. Archive Studio
- **Package Creation**: Compress files into ZIP, 7Z, and TAR. [Create Archive](../09-archives/create-archive.md)
- **AES-256 Encryption**: Password encryption with 7Z header encryption. [Archive Security](../09-archives/archive-security.md)
- **Virtual Inspection**: Browse compressed archives like regular folders. [Inspect Archive](../09-archives/inspect-archive.md)
- **Verification**: CRC-32 and SHA-256 integrity validation. [Verification](../09-archives/verification.md)

---

## 8. Power Tools Suite
- **Batch Renamer**: Multi-file renaming with regex, numbering, and case conversions. [Batch Renamer](../10-power-tools/batch-renamer.md)
- **Duplicate Finder**: Multi-stage byte and SHA-256 deduplication. [Duplicate Finder](../10-power-tools/duplicate-finder.md)
- **Storage Breakdown**: Visual disk usage treemaps and largest consumer identification. [Storage Breakdown](../10-power-tools/storage-analyzer.md)
- **Hash Calculator**: Cryptographic checksum calculation (MD5, SHA-1, SHA-256, SHA-512). [Hash Calculator](../10-power-tools/hashing.md)
- **File Compare**: Visual diff comparator for source code and documents. [File Compare](../10-power-tools/comparison.md)

---

## 9. Windows Platform Integration
- Native drive enumeration and dynamic USB monitoring. [Windows Integration](../12-windows/windows-integration.md)
- Windows Recycle Bin shell API integration. [Recycle Bin](../12-windows/recycle-bin.md)
- Shell context menu integration and file association protocol (`flux://`). [Shell Integration](../12-windows/shell-integration.md)
- OLE drag-and-drop support. [Drag and Drop](../12-windows/drag-drop.md)

---

## 10. Privacy & Customization
- 100% local-first computation with zero telemetry. [Privacy Policy](../15-privacy-security/privacy.md)
- Five curated theme presets (Flux Dark, Flux Light, Slate, Graphite, System Sync). [Themes Guide](../13-settings/themes.md)
- Granular density modes and customizable keyboard shortcuts. [Settings Overview](../13-settings/settings-overview.md)
