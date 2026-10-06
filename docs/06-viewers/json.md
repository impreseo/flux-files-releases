# JSON Viewer & Tree Inspector

## Overview
The JSON Viewer formats, validates, and renders structured JSON documents with collapsible tree nodes and data type badges.

## Visual Interface
![JSON Viewer](./screenshots/viewer-json.png)
*Figure 06.4: Interactive JSON Tree Inspector showing syntax coloring, key-value tiers, and copy actions.*

## Features
- **Interactive Tree Hierarchy**: Expand and collapse nested objects and arrays.
- **Type Badges**: Visual indicators for strings (green), numbers (blue), booleans (purple), and null values.
- **Path Copying**: Right-click any key to copy its exact JSONPath (e.g. `$.users[0].address.city`).
- **Raw / Formatted Toggle**: Switch between formatted indented JSON and collapsible interactive node view.

## Related
- [JSON Editor](../07-editors/json-editor.md)
- [CSV Viewer](./csv.md)
