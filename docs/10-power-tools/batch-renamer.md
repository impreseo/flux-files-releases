# Batch Renamer

## Overview
The **Batch Renamer** is a multi-file renaming utility capable of transforming hundreds of filenames in a single atomic batch.

## Visual Interface
![Batch Rename Modal](./screenshots/tool-batch-rename.png)
*Figure 10.1: Batch Renamer showing find-and-replace rules, regex mode, numbering, and real-time preview.*

## Available Transformation Rules
- **Find & Replace**: Simple string substitution with case-sensitivity options.
- **Regular Expressions**: Powerful regex pattern matching with capture group references (`$1`, `$2`).
- **Prefix & Suffix**: Prepend or append text strings to base names.
- **Number Sequencing**: Add incrementing counters (e.g. `001`, `002`) with customizable start indexes and padding.
- **Case Transformation**: Lowercase, UPPERCASE, Title Case, or Sentence case.
- **Change Extension**: Modify or standardize file extensions across the selection.

## Real-Time Live Preview
The dialog displays a dual-column preview comparing original names to resulting names before committing any changes on disk.

## Related
- [Renaming Files](../04-file-operations/rename.md)
- [Power Tools Overview](../02-menus/tools-menu.md)
