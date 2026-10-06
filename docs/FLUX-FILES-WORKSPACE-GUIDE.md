# Flux Files Workspace & Multitasking Guide
**Multi-Tab Organization, Split Panes & Session Restoration**  
*Quelravo Systems • Fast. Local. Private. Simple.*

---

Flux Files is engineered for users who juggle multiple project folders and complex multi-directory file operations. It replaces chaotic multi-window clutter with a streamlined workspace management architecture.

---

## 1. Multi-Tab Browsing Architecture

![Tab Navigation](images/navigation/navigation-tabs.png)

### Managing Browsing Tabs
- **Open New Tab (`Ctrl+T`)**: Spawns a new tab adjacent to your active tab. Defaults to your configured home path.
- **Close Active Tab (`Ctrl+W`)**: Closes the current tab. Pressing `Ctrl+Shift+T` restores the most recently closed tab.
- **Switch Active Tab (`Ctrl+Tab` / `Ctrl+Shift+Tab`)**: Cycles forward and backward through open tabs. You can also press `Ctrl+1` through `Ctrl+9` to jump directly to tabs 1 through 9.
- **Duplicate Tab**: Right-click any tab header and choose **Duplicate Tab** to open an identical browsing context in a new tab.

### Pinned Tabs
![Pinned Tabs](images/workspaces/workspace-main.png)
- Right-click any tab and select **Pin Tab**.
- Pinned tabs are reduced to compact icon badges anchored to the left of the tab strip.
- Pinned tabs cannot be closed via `Ctrl+W` or accidental clicks.
- Ideal for persistent root workspaces like your active source repository, downloads folder, or network project share.

---

## 2. Dual-Pane Split View

![Dual Pane Workspace](images/workspaces/workspace-management.png)

### Activating Split View
- Press **`Ctrl+Alt+2`** or click the Split View icon in the toolbar.
- The explorer viewport divides into two equal, independent browsing panes:
  - **Primary Pane (Left)**
  - **Secondary Pane (Right)**

### Synchronized File Operations
- **Keyboard Focus**: Press `F6` or click inside a pane to transfer active keyboard focus between left and right panes. The active pane is outlined with a subtle accent border.
- **Drag & Drop Transfers**: Select files in the left pane and drag them into the right pane. By default, items dragged to another volume are copied; items dragged on the same volume are moved. Hold `Ctrl` while dragging to force Copy; hold `Shift` to force Move.
- **Direct Path Sync**: Click **Sync Path** in the split controls to open the current left pane path in the right pane simultaneously.

### Exiting Split View
- Press **`Ctrl+Alt+1`** or click the Single Pane icon in the toolbar. The secondary pane closes, returning full width to the primary pane.

---

## 3. Session Memory & Workspace Restoration

Flux Files features automatic workspace session persistence:
- Every open tab, its navigation history stack, active directory path, and split-pane configuration are saved locally to application state on exit.
- When you relaunch Flux Files with *Restore Previous Session* enabled in Settings, your exact workspace is reconstructed instantly without loss of context.
