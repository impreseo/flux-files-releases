# Back and Forward History

## Overview
Flux Files maintains an in-memory chronological history queue for each tab. Users can move backward and forward through previous locations without losing scroll position or folder selection.

## Visual Interface
![History Navigation](./screenshots/history-navigation.png)
*Figure 01.6: Navigation history buttons on the left of the toolbar.*

## Behavior & Logic
- **Back (`Alt+Left` / Back Mouse Button)**: Steps to the immediately preceding directory. Disabled when at the beginning of the tab history.
- **Forward (`Alt+Right` / Forward Mouse Button)**: Steps to the next directory in the history queue if a back operation was previously executed. Disabled when at the latest head.
- **Up (`Alt+Up` / `Backspace`)**: Steps directly to the parent folder on disk, regardless of historical navigation sequence.
- **History Dropdown**: Long-pressing or right-clicking the Back or Forward buttons reveals a recent history menu listing the last 10 visited folders.

## Related
- [Navigation Overview](./navigation.md)
- [Keyboard Shortcuts Reference](../14-keyboard/shortcut-reference.md)
