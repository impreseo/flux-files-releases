# Dirty State & Unsaved Changes

## Overview
When a file is modified in any editor, Flux Files marks it as **Dirty** to protect against inadvertent data loss.

## Visual Interface
![Dirty State Unsaved](./screenshots/editor-dirty-state.png)
*Figure 07.3: Editor dirty state indicated by title bar accent dot and unsaved warning.*

## Safeguards
- **Visual Badge**: A dot (`•`) appears next to the filename in the tab header and title bar.
- **Exit Interception**: Closing a dirty tab or quitting the application triggers a confirmation prompt offering **Save**, **Don't Save**, or **Cancel**.

## Related
- [Save System](./save-system.md)
- [External Modification](./external-modification.md)
