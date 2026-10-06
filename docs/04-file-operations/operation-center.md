# Operation Center

## Overview
The Operation Center is the central visual queue managing all concurrent asynchronous background file tasks (copies, moves, deletions, hash checks, and compression).

## Features
- **Real-Time Telemetry**: Current file name, transfer rate (MB/s), percentage complete, and estimated remaining time.
- **Pause & Resume**: Temporarily suspend large multi-gigabyte transfers to prioritize system disk I/O.
- **Cancel Button**: Safely terminates transfers and cleans up partial target files.
- **Error Handling**: Displays itemized error lists for locked files or access-denied paths without aborting the entire batch.

## Related
- [Copying Files](./copy.md)
- [Conflict Handling](./conflicts.md)
