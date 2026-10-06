# File Operation Errors & Locked Files

## Overview
Resolving common Windows filesystem errors encountered during copy, move, rename, or deletion.

## Error Scenarios
### 1. "File in Use / Resource Locked"
- **Cause**: Another Windows process (e.g. Word, Visual Studio, Antivirus) holds an exclusive lock on the file.
- **Solution**: Close the locking application. Flux Files displays the locking process name where detectable.

### 2. "Access Denied / Permission Required"
- **Cause**: The current user account lacks write permissions for the directory (e.g. `C:\Program Files`).
- **Solution**: Run Flux Files with administrator privileges or adjust Windows directory security permissions.

### 3. "Path Too Long (MAX_PATH Exceeded)"
- **Cause**: Nested folder paths exceed the legacy 260-character Windows limit.
- **Solution**: Flux Files automatically utilizes Windows `\\?\\` extended-length path prefix syntax to access deep paths up to 32,767 characters.

## Related
- [File Operations Overview](../04-file-operations/copy.md)
- [Conflict Handling](../04-file-operations/conflicts.md)
