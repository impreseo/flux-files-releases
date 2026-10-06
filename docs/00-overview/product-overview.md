# Product Overview — Flux Files

## Overview
Flux Files is an engineered desktop file manager for Windows built around a strict core philosophy: **Fast. Local. Private. Simple.** It merges the raw performance and direct responsiveness of native Windows shell operations with a modern desktop interface, tabbed navigation, dual-pane splitting, universal format previews, built-in editors, and local search.

Flux Files operates with a 100% local-first architecture. It contains zero cloud dependencies, zero external telemetry, zero network telemetry pings, and executes all indexing, hash calculations, archive extraction, and media rendering on the host device.

## Core Philosophy & Design Pillars
1. **Local-First & Private**: All file operations, searches, and previews remain strictly on local storage.
2. **Deterministic Performance**: UI interactions are unblocked, searches utilize an in-memory transactional database with bounded memory budgets, and background tasks run in dedicated worker threads.
3. **Universal Inspection**: Over 50 file formats are rendered natively in preview or full-screen viewer modes without requiring external third-party software.
4. **Power with Simplicity**: Advanced capabilities—such as batch renaming, duplicate detection, drive storage analysis, archive encryption, and dual-pane directory comparison—are integrated into a cohesive, keyboard-navigable desktop experience.

## Interface
![Startup Interface](./screenshots/startup-overview.png)
*Figure 00.1: Flux Files startup state showing navigation sidebar, tabbed workspace, and drive access.*

## Key Architectural Highlights
- **Electron + React + TypeScript**: Native desktop execution with strict type safety.
- **Transactional Search Engine**: SQLite-backed search powered by sql.js with strict safety limits (capped at 50,000 items and 25 MB max export threshold) to guarantee zero UI stutter.
- **Universal Format Engine**: Native decoders and inspectors for text, markdown, JSON, CSV, PDF, audio, video, images, 3D meshes (OBJ, STL, GLTF), fonts (TTF, OTF, WOFF), databases, and CAD wireframes.
- **Power Tools Suite**: Built-in multi-regex batch renamer, SHA/MD5 hash calculator, byte-level file comparator, and storage breakdown.

## Available Workspace Environments
- **Virtual Home**: Quick access hubs, pinned directories, active storage drives, and recent activity.
- **This PC / Storage Hub**: High-level drive capacity meters, filesystem format indicators, and volume management.
- **Explorer Pane**: High-speed folder navigation supporting 8 distinct view layouts.
- **Dual-Pane Split**: Side-by-side independent navigation for rapid inter-directory transfers.

## Related
- [Interface Overview](./interface-overview.md)
- [Terminology Reference](./terminology.md)
- [Quick Start Guide](../handbook/FLUX-FILES-QUICK-START.md)
- [Master User Handbook](../handbook/FLUX-FILES-USER-HANDBOOK.md)
