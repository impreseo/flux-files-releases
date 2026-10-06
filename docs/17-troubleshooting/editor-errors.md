# Editor Errors & Recovery

## Overview
Resolving issues during file editing and saving.

## Common Scenarios
### 1. "External File Modification Detected"
- **Cause**: The file was modified by Git or another program on disk while open in Flux Files.
- **Solution**: Review the comparison prompt and choose **Reload from Disk** or **Keep Editor Version**.

### 2. "Atomic Save Write Failed"
- **Cause**: Target disk is full or directory is read-only.
- **Solution**: Use **Save As** (`Ctrl+Shift+S`) to save your work to another drive or directory.

## Related
- [Save System](../07-editors/save-system.md)
- [Dirty State](../07-editors/dirty-state.md)
