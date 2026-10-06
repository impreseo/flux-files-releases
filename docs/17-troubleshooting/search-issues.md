# Search Troubleshooting & Recovery

## Overview
Resolving search anomalies such as zero results or stalled indexing.

## Common Scenarios & Fixes
### 1. "Search returns zero results for known files"
- **Cause**: Search scope may be set to "Current Folder" while the file is in a subfolder or another drive.
- **Solution**: Switch scope to **Everywhere** or press `Ctrl+Shift+F`.

### 2. "Index is Outdated"
- **Cause**: Files were created outside Flux Files before the crawler scanned the directory.
- **Solution**: Open **Settings → Search** and click **Rebuild Index Now**.

### 3. "Search Crawler Paused"
- **Cause**: Index crawler reached the safe budget cap (50,000 files or 25 MB).
- **Solution**: Check **Help → Search Diagnostics**. Add unnecessary folders (e.g. `node_modules`) to Excluded Directories in Search Settings.

## Related
- [Search Overview](../05-search/search-overview.md)
- [Search Diagnostics](../05-search/search-diagnostics.md)
