# Search & Indexing Settings

## Overview
Manage search crawler bounds, database caching budgets, and excluded paths.

## Key Settings
- **Search Provider**: Local In-Memory SQLite (sql.js).
- **Max Indexed Files**: Hard capped at 50,000 items to guarantee zero UI stalls.
- **Max Database Size**: Hard capped at 25 MB export budget.
- **Rebuild Index Now**: Triggers fresh scan of indexed roots.
- **Excluded Directories**: Configurable list of paths to ignore during indexing.

## Related
- [Search Overview](../05-search/search-overview.md)
- [Indexing Architecture](../05-search/indexing.md)
