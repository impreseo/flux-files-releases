# Explorer Architecture & Viewport

## Overview
The Explorer viewport is the central work surface of Flux Files. It renders local directories, virtual aggregated locations, search result sets, and archive contents with virtualized scrolling, instant sorting, and multi-format iconography.

## Visual Interface
![Details View](./screenshots/details-view.png)
*Figure 03.1: Standard Explorer viewport rendering files in Details mode with technical metadata columns.*

## Key Capabilities
- **8 Layout Engines**: Details, List, Compact Grid, Medium Icons, Large Icons, Extra Large Icons, Gallery Carousel, and Miller Column View.
- **Virtualized Rendering**: Large directories containing tens of thousands of items render at consistent 60 FPS without frame drops.
- **Direct Interaction**: Inline rename (`F2`), drag-and-drop staging, marquee box selection, and rich context menus.
- **Real-Time Filesystem Watching**: Native Windows filesystem events automatically update item listings without requiring manual refreshes.

## Related
- [View Modes Reference](./view-modes.md)
- [Home Hub](./home.md)
- [This PC & Drives](./this-pc.md)
- [File Selection Techniques](./file-selection.md)
