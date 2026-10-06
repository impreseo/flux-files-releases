# Flux Files — Complete Menu System Reference

## Overview
Comprehensive documentation of every item in the native desktop menu bar.

---

## 1. File Menu
| Menu Item | Accelerator | When Active | Function |
|---|---|---|---|
| **New Window** | `Ctrl+Shift+N` | Always | Spawns an independent Flux Files window |
| **New Tab** | `Ctrl+T` | Always | Creates a new tab at Virtual Home |
| **New Folder** | `Ctrl+Shift+N` | In writable folders | Prompts to create a new subfolder |
| **New File** | `Ctrl+Alt+N` | In writable folders | Prompts to create a blank document |
| **Open** | `Enter` | Selection active | Navigates into folder or opens file in viewer |
| **Open in New Tab** | `Ctrl+Enter` | Folder selected | Opens directory in a background tab |
| **Open With...** | — | File selected | Displays Windows app picker dialog |
| **Save** | `Ctrl+S` | In editor mode | Commits editor modifications atomically to disk |
| **Save As...** | `Ctrl+Shift+S` | In editor mode | Saves editor content to a new filename |
| **Close Tab** | `Ctrl+W` | Always | Closes the active tab |
| **Close Window** | `Alt+F4` | Always | Exits the active window |
| **Properties** | `Alt+Enter` | Selection active | Opens file attributes and metadata modal |
| **Exit** | — | Always | Terminates the application |

---

## 2. Edit Menu
| Menu Item | Accelerator | When Active | Function |
|---|---|---|---|
| **Undo** | `Ctrl+Z` | History present | Reverts the last file operation |
| **Redo** | `Ctrl+Y` | Redo stack present | Re-applies the last reverted operation |
| **Cut** | `Ctrl+X` | Selection active | Stages items for relocation (translucent) |
| **Copy** | `Ctrl+C` | Selection active | Copies items or paths to clipboard |
| **Paste** | `Ctrl+V` | Clipboard has files | Transfers staged items to current folder |
| **Paste Shortcut** | — | Clipboard has files | Creates `.lnk` shortcut files in target |
| **Duplicate** | `Ctrl+D` | Selection active | Creates immediate in-place copy |
| **Rename** | `F2` | Single item selected | Activates inline text box renaming |
| **Delete** | `Delete` | Selection active | Moves items to Windows Recycle Bin |
| **Delete Permanently**| `Shift+Delete`| Selection active | Irrevocably purges items bypassing Recycle Bin |
| **Select All** | `Ctrl+A` | Always | Highlights all items in current view |
| **Invert Selection** | — | Always | Inverts selection mask |
| **Clear Selection** | `Esc` | Selection active | Deselects all highlighted items |

---

## 3. View Menu
- **View Modes**: Details (`Ctrl+Shift+6`), List (`Ctrl+Shift+5`), Compact Grid (`Ctrl+Shift+4`), Medium Icons (`Ctrl+Shift+3`), Large Icons (`Ctrl+Shift+2`), Extra Large (`Ctrl+Shift+1`), Gallery (`Ctrl+Shift+7`), Column (`Ctrl+Shift+8`).
- **Sort By**: Name, Date Modified, Type, Size, Ascending / Descending.
- **Group By**: None, Type, Date Modified, Size, Alphabetical.
- **Panes**: Navigation Pane, Preview Pane (`Ctrl+Shift+P`), Details Pane (`Ctrl+Shift+D`), Dual Pane.
- **Zoom**: Zoom In (`Ctrl+=`), Zoom Out (`Ctrl+-`), Reset Zoom (`Ctrl+0`).

---

## 4. Go Menu
| Menu Item | Accelerator | Target Destination |
|---|---|---|
| **Back** | `Alt+Left` | Preceding folder in tab history |
| **Forward** | `Alt+Right` | Next folder in tab history |
| **Enclosing Folder (Up)**| `Alt+Up` / `Backspace` | Parent directory on disk |
| **Home** | `Alt+Home` | Virtual Home dashboard |
| **This PC** | — | Storage drives root |
| **Desktop / Downloads / Documents** | — | Respective user library folders |
| **Recycle Bin** | — | Windows Recycle Bin |
| **Go to Location...** | `Ctrl+L` / `Alt+D` | Focuses Address Bar for direct path typing |

---

## 5. Tools Menu
| Menu Item | Accelerator | Tool Purpose |
|---|---|---|
| **Hash Calculator** | — | Computes MD5, SHA-1, SHA-256, SHA-512 hashes |
| **Batch Rename** | — | Multi-file renaming with regex and numbering |
| **Duplicate Finder** | — | Scans folder for identical duplicate files |
| **File Compare** | — | Side-by-side visual diff comparator |
| **Storage Breakdown** | — | Interactive disk space allocation treemap |
| **Open in Terminal** | — | Launches Windows Terminal in active folder |
| **Open in PowerShell**| — | Launches PowerShell in active folder |
| **Settings** | `Ctrl+,` | Opens comprehensive preferences modal |

---

## 6. Help Menu
| Menu Item | Accelerator | Purpose |
|---|---|---|
| **Keyboard Shortcuts**| `F1` | Displays keyboard shortcut reference overlay |
| **Command Palette** | `Ctrl+P` | Invokes searchable command launcher |
| **Documentation** | — | Opens the Flux Files Product Handbook |
| **Search Diagnostics**| — | Displays search database health and crawler status |
| **Check for Updates** | — | Checks update server for new builds |
| **About Flux Files** | — | Displays version, build date, and credits |

---
*For detailed menu documentation, visit [02-menus/menu-index.md](../02-menus/menu-index.md).*
