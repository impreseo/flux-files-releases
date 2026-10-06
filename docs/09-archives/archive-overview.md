# Archive Studio Overview

## Overview
**Archive Studio** is Flux Files' native engine for creating, inspecting, verifying, and extracting compressed archives without requiring third-party tools like WinRAR or 7-Zip.

## Visual Interface
![Archive Create Dialog](./screenshots/archive-create-dialog.png)
*Figure 09.1: Archive creation modal with format selection, compression levels, and encryption options.*

## Supported Archive Formats
- **ZIP**: Standard universal format with Deflate and AES-256 encryption.
- **7Z**: High-compression LZMA/LZMA2 format with header encryption.
- **TAR / GZ / TGZ**: Standard Unix archive formats for developer workflows.

## Key Capabilities
1. **In-App Creation**: Compress files and folders with selectable compression levels (Store, Fast, Normal, Maximum, Ultra).
2. **Virtual Inspection**: Browse archive contents virtually like a regular folder before extracting.
3. **AES-256 Encryption**: Protect sensitive archives with password-based AES-256 encryption.
4. **Collision Handling**: Interactive prompts to resolve destination filename collisions during extraction.

## Related
- [Creating Archives](./create-archive.md)
- [Extracting Archives](./extract.md)
- [Archive Security](./archive-security.md)
