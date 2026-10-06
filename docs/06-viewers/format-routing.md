# Format Routing Engine

## Overview
Flux Files routes files to their optimal viewer or editor using the **Universal Format Registry** (`UniversalFormatRegistry.ts`).

## Routing Architecture
1. **Extension & Magic Byte Inspection**: Identifies format by extension and verifies file header signatures.
2. **Viewer Dispatch**: Routes to specialized viewers (e.g. `MarkdownViewer`, `Model3DViewer`, `FontViewer`).
3. **Graceful Fallback**: If a format lacks a specialized renderer, it falls back cleanly to:
   - Text Viewer (if detected as valid UTF-8/ASCII text)
   - Hex Viewer (if binary)
   - System Open With dialog (if external application is preferred)

## Related
- [Universal Viewer Overview](./viewer-overview.md)
- [Supported Formats Catalog](../16-supported-formats/format-catalog.md)
