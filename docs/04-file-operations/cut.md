# Cutting Files & Folders

## Overview
Cutting stages items for a filesystem move operation. Items staged with Cut remain in place but appear visually translucent until committed via Paste.

## Workflow
1. Select items to move.
2. Press `Ctrl+X` or choose **Edit → Cut**. Staged item icons dim to 50% opacity.
3. Navigate to target destination.
4. Press `Ctrl+V` or choose **Edit → Paste**.
5. The items are relocated to the destination. If pasting within the same volume, the move completes instantly via filesystem pointer updates.

## Canceling Cut
Pressing `Escape` clears the cut staging without modifying any files on disk.

## Related
- [Copying](./copy.md)
- [Pasting](./paste.md)
- [Moving](./move.md)
