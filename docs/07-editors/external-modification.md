# External Modification Handling

## Overview
If a file currently open in an editor is modified on disk by an external program (e.g. Git, another editor, or build script), Flux Files detects the change via filesystem watch events.

## Resolution Prompt
- **Reload from Disk**: Discards local editor changes and loads the updated disk content.
- **Keep Editor Changes**: Overwrites the external disk modification on next save.

## Related
- [Save System](./save-system.md)
- [Dirty State](./dirty-state.md)
