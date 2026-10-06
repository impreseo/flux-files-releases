# Save System & Atomic File Writing

## Overview
Flux Files implements **Atomic File Writing** to guarantee that power failures, system crashes, or application termination never corrupt target files.

## How Atomic Writing Operates
1. Modifications are staged into a temporary file in the same directory (`target.tmp`).
2. Data is written and flushed via `fsync`.
3. The temporary file is atomically renamed to the target file, replacing the previous version in a single filesystem operation.

## Related
- [Dirty State](./dirty-state.md)
- [External Modification](./external-modification.md)
