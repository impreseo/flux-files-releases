# Large File Media Handling

## Overview
Flux Files handles large media assets (e.g. 4K/8K video files, multi-gigabyte RAW archives) through streamed buffer reading rather than loading full files into memory.

## Architectural Safeguards
- **Streaming Pipeline**: Media data is streamed from disk on demand.
- **Memory Conservation**: Keeps RAM usage minimal during extended media playback.

## Related
- [Performance Troubleshooting](../17-troubleshooting/performance.md)
- [Video Player](./video-player.md)
