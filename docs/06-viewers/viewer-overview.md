# Universal Viewer Architecture

## Overview
Flux Files integrates a high-performance **Universal Viewer Engine** capable of rendering documents, code, images, audio, video, 3D meshes, typography fonts, and databases directly inside the application.

## Core Viewer Modes
1. **Docked Preview Pane (`Ctrl+Shift+P`)**: Live contextual sidebar panel updating immediately as items are selected.
2. **Modal In-App Viewer (`Space` or `Enter`)**: Distraction-free floating inspection viewport with zoom, search, and format-specific controls.
3. **External Handler Fallback**: One-click option to open the file in the Windows default application or custom program.

## Screenshots Showcase
![Markdown Viewer](./screenshots/viewer-markdown.png)
*Figure 06.1: Markdown Viewer rendering typography, code blocks, and markdown tables.*

![Code Viewer](./screenshots/viewer-code.png)
*Figure 06.2: Code & Text Viewer displaying syntax highlighting and line numbers.*

## Supported Formats Summary
- **Documents**: Markdown (`.md`), PDF (`.pdf`), Plain Text (`.txt`), Rich Text (`.rtf`).
- **Data & Tables**: JSON (`.json`), CSV / TSV (`.csv`, `.tsv`), SQLite Database (`.sqlite`, `.db`).
- **Media**: Raster & Vector Images, MP4/WebM/MKV Video, MP3/FLAC/WAV Audio.
- **3D & CAD**: OBJ, STL, GLTF/GLB meshes, CAD wireframes.
- **Developer Assets**: Font specimens (TTF, OTF, WOFF), AI/ML Tensors (ONNX, Safetensors), Binary Hex dumps.

## Related
- [Format Routing](./format-routing.md)
- [Editors Overview](../07-editors/editor-overview.md)
- [Supported Formats Catalog](../16-supported-formats/format-catalog.md)
