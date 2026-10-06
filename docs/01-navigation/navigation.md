# Navigation Architecture

## Overview
Navigation in Flux Files provides fluid directory transitions via keyboard shortcuts, interactive breadcrumbs, an extensible sidebar tree, historical travel queues, and multi-tab workspaces.

## Navigation Topology
![Address Bar Breadcrumbs](./screenshots/address-bar-breadcrumbs.png)
*Figure 01.1: Interactive navigation controls showing historical step buttons, folder breadcrumbs, and instant search entry.*

## Navigation Mechanisms
1. **Hierarchical Breadcrumbs**: Click any parent segment in the path to jump directly up the directory tree.
2. **Editable Address Bar**: Press `Ctrl+L` or `Alt+D` to focus and enter absolute Windows paths (e.g., `C:\Windows\System32`).
3. **Sidebar Tree**: Quick-click shortcuts for Virtual Home, This PC, pinned favorites, and storage partitions.
4. **Historical Navigation**: Standard Back (`Alt+Left`), Forward (`Alt+Right`), and Parent Directory (`Alt+Up` or `Backspace`).
5. **Keyboard Hotkeys**: Direct access to core locations such as Home (`Alt+Home`) or Command Palette (`Ctrl+P`).

## Keyboard Shortcuts
| Shortcut | Action | Scope |
|---|---|---|
| `Alt+Left` | Navigate Back in history | Global |
| `Alt+Right` | Navigate Forward in history | Global |
| `Alt+Up` | Navigate to Parent Directory | Active Pane |
| `Backspace` | Navigate to Parent Directory | Active Pane (when not editing text) |
| `Alt+Home` | Jump to Virtual Home | Global |
| `Ctrl+L` / `Alt+D` | Focus editable address bar | Global |
| `Ctrl+T` | Open new tab | Global |
| `Ctrl+W` | Close active tab | Global |
| `Ctrl+Tab` / `Ctrl+Shift+Tab` | Switch to next / previous tab | Global |

## Related
- [Sidebar Documentation](./sidebar.md)
- [Address Bar & Path Input](./address-bar.md)
- [Tabs & Workspaces](./tabs.md)
- [Back & Forward Navigation](./back-forward-navigation.md)
