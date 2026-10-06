# Flux Files — Troubleshooting & Error Recovery Guide

## Overview
Verified diagnostic and recovery procedures for operational edge cases, permission denials, locked files, and database recovery.

---

## 1. Search Issues & Solutions
### Scenario: "Search returns zero results for known files"
- **Cause**: Search scope is currently restricted to "Current Folder" while the file resides in another directory or drive.
- **Recovery**: Press `Ctrl+Shift+F` to toggle **Everywhere Search** scope.

### Scenario: "Search Index is Outdated"
- **Cause**: Files were created externally before the crawler indexed them.
- **Recovery**: Go to **Settings → Search** and click **Rebuild Index Now**, or open **Help → Search Diagnostics**.

### Scenario: "Crawler Paused / Budget Cap Reached"
- **Cause**: Host filesystem exceeded the 50,000 file or 25 MB database safety cap.
- **Recovery**: Open **Settings → Search → Excluded Directories** and exclude large build directories like `node_modules` or `target`.

---

## 2. File Operation Errors
### Scenario: "Resource Locked / File in Use"
- **Cause**: Another Windows process (e.g. Word, Visual Studio, Antivirus) holds an exclusive read/write lock.
- **Recovery**: Close the application holding the lock. Flux Files displays the locking process name where detectable.

### Scenario: "Access Denied / Administrator Privileges Required"
- **Cause**: Current user account lacks write permissions for protected system directories (e.g. `C:\Program Files`).
- **Recovery**: Launch Flux Files as Administrator or adjust folder security permissions in Windows.

### Scenario: "Path Too Long (MAX_PATH Exceeded)"
- **Cause**: Nested folder paths exceed the 260-character legacy limit.
- **Recovery**: Flux Files handles paths up to 32,767 characters using Windows `\\?\\` extended syntax automatically.

---

## 3. Viewer & Media Errors
### Scenario: "File Exceeds Maximum Preview Budget"
- **Cause**: File exceeds the configured preview size threshold (default 50 MB) to prevent RAM exhaustion.
- **Recovery**: Increase preview limit in **Settings → Viewers**, or click **Open Externally**.

### Scenario: "Corrupted Media / Unsupported Codec"
- **Cause**: Video or audio file utilizes an unsupported proprietary codec.
- **Recovery**: Right-click file and choose **Open With...** to launch in an external player like VLC.

---

## 4. Built-In Editor Errors
### Scenario: "External Modification Detected"
- **Cause**: File was altered on disk by another program while open in the Flux Files editor.
- **Recovery**: Choose **Reload from Disk** to load new changes, or **Keep Editor Changes** to overwrite.

### Scenario: "Atomic Save Failed"
- **Cause**: Target disk is out of storage or directory is read-only.
- **Recovery**: Use `Ctrl+Shift+S` (Save As) to save the file to another directory or storage volume.

---

## 5. Removable Media (USB) Issues
### Scenario: "USB Drive Not Detected"
- **Cause**: USB drive has no assigned drive letter in Windows Disk Management.
- **Recovery**: Open Windows Disk Management (`diskmgmt.msc`) and assign a drive letter, or replug the device.

### Scenario: "Drive Cannot Be Safely Ejected"
- **Cause**: Files on the drive are currently open in Flux Files tabs or viewers.
- **Recovery**: Close tabs pointing to the USB drive and click **Eject** again.

---

## 6. Factory Reset & Diagnostic Recovery
If preferences become corrupted:
1. Open **Settings (`Ctrl+,`) → Reset**.
2. Select **Reset All Preferences to Factory Defaults**.
3. Flux Files restores default themes, view modes, and keybindings without modifying any user files on disk.

---
*For further assistance, consult the [Master User Handbook](./FLUX-FILES-USER-HANDBOOK.md).*
