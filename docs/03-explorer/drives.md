# Drives & Removable Media

## Overview
Flux Files maintains continuous hardware monitoring of Windows drive mount events via native APIs. When external USB drives, SD cards, or virtual ISO mounts are attached, Flux Files automatically detects them.

## Supported Drive Types
- **Fixed Hard Drives & NVMe SSDs**: Primary Windows operating system and secondary storage drives.
- **Removable Media**: USB flash drives, external SSDs, SD card readers.
- **Optical Drives**: CD/DVD/Blu-Ray drives and mounted ISO image files.
- **Network Drives**: SMB/CIFS mapped network shares mapped to Windows drive letters.

## Removable Media Management
- **Safe Ejection**: Right-click any removable drive in the sidebar or This PC and choose **Eject Drive**. Flux Files flushes pending write caches before unmounting.
- **Capacity Warnings**: Visual badges alert users when drive free space drops below critical thresholds (10% or 5 GB).

## Related
- [This PC Overview](./this-pc.md)
- [USB Workflow](../18-workflows/usb-workflow.md)
