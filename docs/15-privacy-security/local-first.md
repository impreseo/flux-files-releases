# Local-First Architecture

## Overview
Local-First software ensures that the user owns their data entirely and all computations occur directly on the host machine.

## Implementation Details
- **Local Index Database**: Search indexes are saved directly to the local application data directory in SQLite format.
- **Local Thumbnails**: Image and video thumbnails are cached locally and never uploaded.
- **Local Execution**: All power tools (Batch Rename, Duplicate Finder, Hash Calculator) operate directly against the native Windows filesystem APIs.

## Related
- [Privacy Overview](./privacy.md)
- [Security Notes](./security-notes.md)
