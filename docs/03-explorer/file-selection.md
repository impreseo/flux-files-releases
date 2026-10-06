# File Selection Techniques

## Overview
Flux Files provides keyboard and mouse selection models adhering to Windows desktop standards.

## Selection Controls
| Method | Action | Result |
|---|---|---|
| **Single Click** | Click item row/card | Selects item exclusively, clearing previous selection. |
| **Ctrl + Click** | Hold `Ctrl` and click item | Toggles selection state of clicked item without altering others. |
| **Shift + Click** | Hold `Shift` and click item | Extends selection range from anchor to clicked item. |
| **Marquee Drag** | Click and drag in whitespace | Draws rectangular selection lasso over multiple items. |
| **Select All** | `Ctrl+A` | Highlights all items in the current active folder. |
| **Invert Selection** | Edit menu → Invert Selection | Inverts current selection mask. |
| **Deselect All** | `Escape` or click empty space | Clears all active selections. |

## Selection Metadata
When multiple files are selected, the bottom **Status Bar** dynamically updates to display the total count of selected items and their cumulative byte size (e.g., `14 items selected (482.4 MB)`).

## Related
- [Keyboard Shortcuts](../14-keyboard/file-operation-shortcuts.md)
- [File Operations](../04-file-operations/copy.md)
