# Breadcrumbs Navigation

## Overview
Breadcrumbs provide real-time spatial context of where the current directory resides in the filesystem hierarchy. Each segment is an actionable target that eliminates repetitive back navigation.

## Functional Behavior
- **Path Parsing**: Flux Files decomposes absolute Windows paths into distinct nodes:
  `This PC > C: > Users > Developer > Projects > Flux Files`
- **Instant Traversal**: Clicking any segment in the trail navigates immediately to that node, flushing subsequent child history for that branch.
- **Segment Dropdown Menus**: Clicking the arrow delimiter between breadcrumbs displays sibling directories located within that parent folder.
- **Copy Path Shortcut**: Right-clicking any breadcrumb segment provides:
  - Copy Full Path
  - Copy Folder Name
  - Open in New Tab
  - Open in New Window
  - Open in Terminal

## Related
- [Address Bar Guide](./address-bar.md)
- [Navigation Overview](./navigation.md)
