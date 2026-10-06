# Deleting Files & Folders

## Overview
Flux Files supports both safe deletion (transferring items to the Windows Recycle Bin) and permanent immediate deletion.

## Deletion Methods
1. **Recycle Bin Deletion (`Delete` key)**:
   - Selected items are safely moved to the Windows Recycle Bin.
   - Files remain recoverable until the Recycle Bin is emptied.
   - Undoable via `Ctrl+Z`.
2. **Permanent Deletion (`Shift+Delete`)**:
   - Items are immediately unlinked from the filesystem.
   - Bypasses the Recycle Bin for maximum privacy and immediate space reclamation.
   - Prompts for explicit user confirmation before proceeding.

## Related
- [Recycle Bin Management](./recycle-bin.md)
- [Restoring Files](./restore.md)
