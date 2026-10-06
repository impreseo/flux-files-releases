# Search System Overview

## Overview
Flux Files features an engineered local search engine offering instantaneous in-folder filtering, structured syntax queries, and multi-drive global searches.

## Visual Interface
![Instant Search](./screenshots/instant-search.png)
*Figure 05.1: Instant search query highlighting matching files with execution metrics.*

## Search Architectures
1. **Instant In-Folder Filter**: Zero-latency filtering of active directory items as you type in the search bar.
2. **Everywhere Search**: Asynchronous background search querying indexed local drives and recursive directories.
3. **Advanced Syntax Engine**: Filter by extension (`ext:pdf`), format category (`type:image`), byte size (`size:>100MB`), or modification date (`modified:today`).

## Hardened Index Safety
Flux Files incorporates strict safety caps to guarantee zero UI freezes:
- **Maximum Index Items**: Capped at 50,000 files.
- **Maximum Database Size**: Capped at 25 MB.
- **Safety Fallback**: Automatically switches to live targeted crawling if index limits are reached, preventing catastrophic thread stalls.

## Related
- [Global Everywhere Search](./global-search.md)
- [Search Filters & Syntax](./filters.md)
- [Search Diagnostics](./search-diagnostics.md)
