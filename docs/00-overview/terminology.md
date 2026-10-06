# Terminology & Concepts

## Overview
This document defines standard technical terms used across the Flux Files interface, documentation, and error diagnostics.

## Terminology Reference
| Term | Definition | Context |
|---|---|---|
| **Virtual Home** | A synthetic root view displaying aggregated user hubs (Desktop, Downloads, Documents, Pictures, Music, Videos) and active drives. | Navigation & Sidebar |
| **This PC** | The system root displaying all detected storage partitions, mapped drives, and removable storage media. | Drive Hub |
| **Dual Pane** | A side-by-side workspace displaying two independent active explorer panes for high-speed file manipulation. | Workspaces |
| **Miller Columns** | A cascading multi-column hierarchical view showing parent, current, and child folders horizontally. | View Modes |
| **Universal Viewer** | In-app inspection engine capable of rendering documents, code, images, audio, video, 3D models, fonts, and databases. | Viewers |
| **Dirty State** | An indicator (visual dot / warning) denoting that an open editor file contains unsaved memory modifications. | Editors |
| **Everywhere Search** | Global filesystem search that queries both indexed metadata and live disk directories across all mounted partitions. | Search |
| **Safe Index Cap** | The architectural limit (50,000 files / 25 MB database size) enforced to prevent memory starvation and thread freezes. | Search Indexer |
| **Operation Center** | Unified queue and progress manager for asynchronous file copying, moving, deletion, and compression tasks. | File Operations |
| **Archive Studio** | Integrated engine for creating, inspecting, verifying, and extracting ZIP, 7Z, TAR, and GZ archives with AES-256 encryption. | Archives |
| **Storage Intelligence** | Interactive visual breakdown of directory disk usage with tier-based color gradients. | Power Tools |

## Related
- [Product Overview](./product-overview.md)
- [Interface Overview](./interface-overview.md)
- [Explorer Architecture](../03-explorer/explorer.md)
