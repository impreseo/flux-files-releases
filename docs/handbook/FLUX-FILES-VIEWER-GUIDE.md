# Flux Files — Universal Viewer Guide & Format Handbook

## Overview
Flux Files integrates the **Universal Viewer Engine**, providing instant inspection of over 50 file formats without launching third-party applications.

---

## Viewer Modalities
1. **Docked Preview Pane (`Ctrl+Shift+P`)**: Collapsible panel on the right side of the Explorer viewport.
2. **Modal Viewer (`Space` or `Enter`)**: Full-featured floating inspection dialog with format-specific toolbars and search.
3. **External Handler Fallback**: One-click button to open in the Windows default application.

---

## Format Coverage & Viewer Engines

### 1. Document & Text Engine
- **Markdown (`.md`)**: GitHub Flavored Markdown (GFM) rendering with headers, tables, task lists, and syntax blocks.
- **PDF Documents (`.pdf`)**: Embedded multi-page viewer with continuous scrolling, page jump, and text search.
- **Plain Text & Logs (`.txt`, `.log`, `.cfg`)**: High-speed text viewer with line numbers and encoding detection.
- **Office Inspection (`.docx`, `.xlsx`, `.pptx`)**: Non-destructive structural inspection and embedded asset extractor.

### 2. Tabular Data & Databases
- **JSON Inspector (`.json`)**: Collapsible interactive tree, key-value syntax coloring, and JSONPath copying.
- **CSV Data Grid (`.csv`, `.tsv`)**: Virtualized spreadsheet grid with sortable columns and search filtering.
- **SQLite Database (`.sqlite`, `.db`)**: Table schema browser, record pagination, and SQL query viewer.

### 3. Media & Audio-Visual
- **Image Viewer (`.png`, `.jpg`, `.webp`, `.gif`, `.svg`, `.bmp`, RAW)**: Smooth fractional zoom, panning, and EXIF extraction.
- **Video Player (`.mp4`, `.webm`, `.mkv`)**: Hardware-accelerated video playback with frame seeking.
- **Audio Player (`.mp3`, `.flac`, `.wav`, `.ogg`, `.m4a`)**: Waveform visualizer with ID3 tag parsing.

### 4. 3D & Technical Assets
- **3D Mesh Viewer (`.obj`, `.stl`, `.gltf`, `.glb`)**: Real-time WebGL orbit camera, shading modes, and polygon counts.
- **CAD Wireframe Inspector**: Vector geometry inspector.
- **Font Specimen Viewer (`.ttf`, `.otf`, `.woff`, `.woff2`)**: Typography specimen waterfall and glyph tables.
- **Binary / Hex Viewer (`.bin`, `.hex`, `.dat`, `.exe`)**: Dual hex/ASCII matrix with byte inspector.

---

## Viewer Controls Cheat Sheet
| Action | Shortcut |
|---|---|
| Toggle Quick Preview | `Space` |
| Toggle Docked Preview Pane | `Ctrl+Shift+P` |
| Zoom In / Out | Scroll Wheel or `+` / `-` |
| Reset Zoom to Fit | `Ctrl+0` |
| 100% Native Scale | `Ctrl+1` |
| Rotate Image 90° | `R` |
| Play / Pause Media | `Space` |
| Toggle Fullscreen | `F` or `F11` |
| Close Viewer Modal | `Escape` |

---
*For in-depth format specifications, consult [16-supported-formats/format-catalog.md](../16-supported-formats/format-catalog.md).*
