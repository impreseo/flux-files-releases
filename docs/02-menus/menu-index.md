# Menu Bar Documentation Index

## Overview
This section provides complete documentation for every menu item present in the native Flux Files desktop menu bar and context menus.

## Section Contents
- [File Menu](./file-menu.md)
- [Edit Menu](./edit-menu.md)
- [View Menu](./view-menu.md)
- [Go Menu](./go-menu.md)
- [Tools Menu](./tools-menu.md)
- [Help Menu](./help-menu.md)
- [Context Menus](./context-menus.md)

## Authentic Menu Architecture
The menu system is defined in `MenuBar.tsx` and integrates directly with the global `CommandRegistry`. Every menu item contains keyboard accelerator bindings and reflects real-time contextual availability (e.g., selection-dependent actions are disabled when no item is selected).

## Related
- [Menu Reference](../01-navigation/menu-reference.md)
- [Keyboard Shortcut Reference](../14-keyboard/shortcut-reference.md)
