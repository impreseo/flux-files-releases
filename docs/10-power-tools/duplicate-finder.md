# Duplicate File Finder

## Overview
The Duplicate Finder scans target folders to identify redundant files occupying disk space, utilizing a multi-stage hash comparison pipeline.

## Detection Pipeline
1. **Size Filtering**: Groups files by exact byte size. Files with unique sizes are eliminated instantly.
2. **Partial Hash Check**: Computes fast hash of the first 4 KB of candidate files.
3. **Full SHA-256 Hash**: Performs cryptographic SHA-256 comparison on candidate matches to guarantee 100% byte-for-byte identity.

## Cleanup Actions
- Keep newest / keep oldest.
- Select all duplicates except original.
- Move duplicates to Recycle Bin or dedicated review folder.

## Related
- [Storage Breakdown](./storage-analyzer.md)
- [Hash Calculator](./hashing.md)
