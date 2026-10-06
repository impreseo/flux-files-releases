# Character Encoding & Detection

## Overview
Flux Files detects and preserves file character encodings to prevent text garbling (mojibake).

## Supported Encodings
- **UTF-8 (Default)**: Standard Unicode encoding without BOM.
- **UTF-8 with BOM**: Preserves byte order mark for legacy Windows software.
- **UTF-16 LE / BE**: Windows Unicode standard.
- **ASCII / Windows-1252**: Legacy Western European single-byte encoding.

## Related
- [Line Endings](./line-endings.md)
- [Text Editor](./text-editor.md)
