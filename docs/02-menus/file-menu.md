# File Menu

## Overview
The **File** menu manages top-level application instances, tab lifecycles, item creation, saving open editors, and inspecting filesystem properties.

## Menu Items Table
| Item | Shortcut | When Available | Purpose & Behavior |
|---|---|---|---|
| **New Window** | `Ctrl+Shift+N` | Always | Opens an independent Flux Files desktop window. |
| **New Tab** | `Ctrl+T` | Always | Opens a new tab in the active window at Virtual Home. |
| **New Folder** | `Ctrl+Shift+N` | In writable folders | Opens the New Folder dialog to create a directory. |
| **New File** | `Ctrl+Alt+N` | In writable folders | Opens the New File dialog to create a blank document. |
| **Open** | `Enter` | When item selected | Opens folder in active pane, or launches file in default viewer/app. |
| **Open in New Tab** | `Ctrl+Enter` | When folder selected | Opens the highlighted folder in a background tab. |
| **Open With...** | — | When file selected | Displays the Windows application picker dialog. |
| **Save** | `Ctrl+S` | In editor mode | Commits active editor modifications to disk. |
| **Save As...** | `Ctrl+Shift+S` | In editor mode | Saves editor contents under a new filename/path. |
| **Close Tab** | `Ctrl+W` | Always | Closes the current active tab. |
| **Close Window** | `Alt+F4` | Always | Exits the current Flux Files window. |
| **Properties** | `Alt+Enter` | When item selected | Opens the detailed metadata and attributes dialog. |
| **Exit** | — | Always | Terminates the application instance. |

## Dialog Screenshots
![Properties Dialog](./screenshots/properties-dialog.png)
*Figure 02.1: File Properties dialog showing detailed attributes, size on disk, and timestamps.*

![Open With Dialog](./screenshots/open-with-dialog.png)
*Figure 02.2: Open With system dialog for choosing external handler applications.*

## Related
- [Edit Menu](./edit-menu.md)
- [File Operations](../04-file-operations/create.md)
- [Properties Documentation](../04-file-operations/properties.md)
