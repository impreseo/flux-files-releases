# Edit Menu

## Overview
The **Edit** menu provides clipboard manipulation, file duplication, selection management, and undo/redo capabilities for file operations.

## Menu Items Table
| Item | Shortcut | When Available | Purpose & Behavior |
|---|---|---|---|
| **Undo** | `Ctrl+Z` | When undo stack exists | Reverts the last file operation (rename, move, trash). |
| **Redo** | `Ctrl+Y` | When redo stack exists | Re-applies the previously reverted operation. |
| **Cut** | `Ctrl+X` | When item selected | Stages selected items to clipboard for moving. Items appear translucent. |
| **Copy** | `Ctrl+C` | When item selected | Copies selected items or paths to clipboard. |
| **Paste** | `Ctrl+V` | When clipboard has files | Transfers staged items into the current directory. |
| **Paste Shortcut** | — | When clipboard has files | Creates Windows shell shortcut (.lnk) files in target. |
| **Duplicate** | `Ctrl+D` | When item selected | Instantly creates an in-place copy with " - Copy" suffix. |
| **Rename** | `F2` | Single item selected | Activates inline editing for the item name. |
| **Delete** | `Delete` | When item selected | Moves selected items to the Windows Recycle Bin. |
| **Delete Permanently**| `Shift+Delete` | When item selected | Irrevocably purges selected items bypassing the Recycle Bin. |
| **Select All** | `Ctrl+A` | Always | Selects all files and folders in the current view. |
| **Invert Selection** | — | Always | Inverts selection mask across current directory items. |
| **Clear Selection** | `Esc` | When items selected | Deselects all currently highlighted items. |

## Related
- [File Operations Section](../04-file-operations/copy.md)
- [Selection Techniques](../03-explorer/file-selection.md)
