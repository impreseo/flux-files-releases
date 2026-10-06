# Flux Files — Settings & Configuration Guide

## Overview
Comprehensive documentation of all user preferences available in **Settings (`Ctrl+,`)**.

---

## 1. General Settings
- **Startup Location**: Choose between Virtual Home, This PC, Last Visited Folder, or Custom Path.
- **Restore Windows & Tabs on Startup**: Automatically restores your previous tabs upon launching.
- **Confirm File Deletions**: Prompts before sending items to the Recycle Bin.
- **Confirm Permanent Deletions**: Prompts before executing `Shift+Delete`.

---

## 2. Appearance Settings
- **Theme Preset**:
  - *Flux Dark (Default)*: Deep engineered slate (`#090B0D`) with technical blue accent (`#1683C7`).
  - *Flux Light*: High-contrast daylight neutral surfaces.
  - *Slate*: Industrial blue-gray palette.
  - *Graphite*: Pure monochrome platinum palette.
  - *System Sync*: Automatically mirrors Windows light/dark mode.
- **Density Mode**:
  - *Compact*: 28px row height; maximizes visible files.
  - *Default*: 36px row height; standard desktop ergonomics.
  - *Comfortable*: 44px row height; enlarged hit targets.
- **UI Animations**: Enable or disable smooth transition animations across panels.
- **High Contrast Borders**: Increases border delineation for accessibility.

---

## 3. Files & Folders Settings
- **Show Hidden Files**: Displays Windows hidden files and folders.
- **Show System Files**: Displays OS-protected system files.
- **Show File Extensions**: Displays file extensions (`.txt`, `.pdf`) in filenames.
- **Default Collision Action**: Ask User, Overwrite, Skip, or Keep Both.

---

## 4. Explorer Settings
- **Default View Mode**: Details, List, Compact Grid, Medium Icons, Large Icons, Gallery, Column.
- **Open Item Action**: Double-Click (Standard) or Single-Click.
- **Remember Folder Views**: Automatically preserves per-folder view modes and column widths.

---

## 5. Viewers & Previews Settings
- **Enable In-App Previews**: Toggles native Universal Viewer vs external application launch.
- **Auto-Preview on Selection**: Automatically renders highlighted file in docked Preview pane.
- **Maximum Preview Size**: Configurable buffer limit (default 50 MB) to prevent RAM exhaustion.

---

## 6. Search & Indexing Settings
- **Search Provider**: Local In-Memory SQLite (sql.js).
- **Max Indexed Files**: Hard capped at 50,000 items to prevent UI stutter.
- **Max Database Size**: Hard capped at 25 MB export budget.
- **Rebuild Index Now**: Triggers fresh scan of indexed roots.
- **Excluded Directories**: Configurable list of paths to ignore during indexing.

---

## 7. Keyboard Settings
- Search and rebind any keyboard shortcut.
- Automatic conflict detection alerts if key combinations overlap.
- One-click reset to factory default shortcuts.

---

## 8. Updates & Diagnostics
- **Auto-Check for Updates**: Toggle background update checks.
- **Update Channel**: Stable (Production) or Beta (Pre-Release).
- **Reset Preferences**: Granular reset per category or full factory restore.

---
*For category details, visit [13-settings/settings-overview.md](../13-settings/settings-overview.md).*
