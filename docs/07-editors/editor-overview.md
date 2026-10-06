# Built-In Editors Overview

## Overview
Flux Files includes lightweight, high-performance in-app editors designed for quick modifications without opening heavyweight external IDEs.

## Visual Interface
![Quick Text Editor](./screenshots/editor-text.png)
*Figure 07.1: Quick Text Editor with clean layout and status bar encoding controls.*

## Core Editor Capabilities
- **Multi-Format Support**: Plain Text, Source Code, Markdown, JSON, CSV, and HTML.
- **Save Safety**: Atomic write operations with transactional temporary files.
- **Dirty State Tracking**: Visual status indicators and exit prompts to prevent accidental data loss.
- **External Modification Detection**: Warns if a file was modified externally on disk while open in the editor.

## Related
- [Text Editor](./text-editor.md)
- [Markdown Live Editor](./markdown-editor.md)
- [Save System](./save-system.md)
