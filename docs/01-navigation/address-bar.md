# Address Bar & Path Controls

## Overview
The Flux Files Address Bar unifies path navigation, direct string path entry, and instant context search in a single responsive control.

## Visual Appearance
![Address Bar Breadcrumbs](./screenshots/address-bar-breadcrumbs.png)
*Figure 01.4: Path display showing segmented interactive breadcrumb pills.*

## Modes of Operation
1. **Interactive Breadcrumb Mode (Default)**:
   - Displays each directory segment as a clickable button.
   - Hovering highlights the segment.
   - Clicking jumps immediately to that folder.
   - Right-clicking a breadcrumb segment reveals contextual actions (e.g., Copy Path, Open in New Tab).
2. **Text Edit Mode**:
   - Activated by pressing `Ctrl+L`, `Alt+D`, or clicking the blank background area of the address bar.
   - Converts the breadcrumbs into a standard text box with the full absolute path highlighted.
   - Supports auto-completion suggestions, pasting paths, and direct typing.
   - Pressing `Enter` commits the navigation.
   - Pressing `Escape` cancels edit mode and restores breadcrumb display.

## Controls Table
| Control | Trigger | Action |
|---|---|---|
| Breadcrumb Segment | Left Click | Jump immediately to selected parent directory |
| Breadcrumb Segment | Right Click | Open context menu for parent folder |
| Blank Address Bar Area | Left Click | Toggle into raw text path editing mode |
| Path Text Input | `Enter` | Navigate to typed directory path |
| Path Text Input | `Escape` | Discard input and revert to breadcrumb mode |
| Copy Path Button | Click icon | Copy full normalized path to system clipboard |

## Related
- [Breadcrumbs Guide](./breadcrumbs.md)
- [Navigation Shortcuts](../14-keyboard/navigation-shortcuts.md)
