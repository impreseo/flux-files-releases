# Windows OS Integration Overview

## Overview
Flux Files integrates deeply with native Windows subsystem APIs while maintaining full local-first sandboxing.

## Visual Interface
![Windows Drives](./screenshots/windows-drives.png)
*Figure 12.1: Native Windows drive volumes and filesystem monitoring.*

## Core Windows Integrations
- **Native Drive Volumes**: Enumerates fixed, removable, and mapped network drives.
- **Recycle Bin**: Uses Windows Shell COM interfaces for safe trashing and restoration.
- **Shell Context Menu**: Optional Windows Explorer context menu entry ("Open in Flux Files").
- **File Associations**: Register Flux Files as default handler for folders or specific formats.
- **System Drag & Drop**: OLE drag-and-drop between Flux Files, desktop, and other Windows apps.

## Related
- [Drives Integration](./drives.md)
- [Native Dialogs](./native-dialogs.md)
- [Drag and Drop](./drag-drop.md)
