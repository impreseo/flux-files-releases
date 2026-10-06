# File Security & Integrity Safeguards

## Overview
Safeguards implemented to prevent unintentional data loss or file corruption.

## Safeguards Summary
- **Atomic Saving**: Staging files prevent corrupted writes on power loss.
- **Recycle Bin Interception**: Default deletion routes to Windows Recycle Bin rather than permanent destruction.
- **System Directory Protection**: Prompts warnings when attempting to modify Windows system files.
- **Permanent Delete Safeguard**: `Shift+Delete` requires explicit dialog confirmation before unlinking.

## Related
- [Atomic Save System](../07-editors/save-system.md)
- [Archive Security](./archive-security.md)
