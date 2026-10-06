# Binary & Hex Viewer

## Overview
The Binary & Hex Viewer provides raw byte-level inspection for compiled binaries, firmware files, and unknown file formats.

## Visual Interface
![Binary Hex Viewer](./screenshots/viewer-binary-hex.png)
*Figure 06.12: Dual-column hex view with offset addresses, byte hex pairs, and ASCII decoding.*

## Features
- **Three-Column Layout**: Byte Offset (Hex), Hex Byte Matrix (16 bytes per row), and ASCII/Unicode translation.
- **Byte Inspector**: Highlights selected byte and decodes it as 8-bit, 16-bit, 32-bit (signed/unsigned), and float.
- **Virtual Scrolling**: Seamless navigation across large binary files without loading the entire file into memory.

## Related
- [PE Binary Inspector](../16-supported-formats/windows.md)
- [Universal Viewer Overview](./viewer-overview.md)
