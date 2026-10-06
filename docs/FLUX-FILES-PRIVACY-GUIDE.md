# Flux Files Privacy & Security Architecture
**Local-First Engineering & Zero-Telemetry Guarantee**  
*Quelravo Systems • Fast. Local. Private. Simple.*

---

In an era where modern software increasingly monitors user behavior, transmits path telemetry to remote servers, and requires cloud accounts, Flux Files was built with an uncompromising commitment: **Absolute Local Autonomy**.

---

## 1. Zero Cloud Dependencies

- **No User Accounts**: Flux Files requires no user account, email registration, API key, or authentication tokens.
- **Zero Remote Storage**: Flux Files never stores or synchronizes your directory structures, file metadata, or file contents on remote cloud servers.
- **100% Offline Capability**: Flux Files operates identically whether your PC is connected to high-speed internet or completely air-gapped from all networks.

---

## 2. Zero Telemetry & Analytics

- **No Usage Analytics**: Flux Files contains no analytics frameworks (no Google Analytics, no Mixpanel, no PostHog, no Segment).
- **No Path Snooping**: Your directory names, file names, file sizes, and browsing habits never leave your local machine.
- **No Crash Telemetry**: Application errors are logged exclusively to your local machine at `%APPDATA%\Flux Files\logs\error.log` for your personal inspection. No error reports are transmitted over the network.

---

## 3. Local SQLite Index Security

- Flux Files uses an embedded local SQLite database stored in your user profile to power instant Everywhere Search.
- The index database is stored locally at:  
  `%APPDATA%\Flux Files\search_index.db`
- Only file metadata (name, path, extension, size, modified date) is indexed. File contents are not stored in the search database.
- The search index can be completely cleared or deleted at any time with a single click in `Settings > Search > Rebuild Index`.

---

## 4. Transparent Network Policy

Flux Files initiates outbound network connections **only** under the following strict condition:
1. **Manual Update Check**: When you explicitly click "Check for Updates" in `Settings > Updates`. This query contacts the verified release repository to compare version tags.
2. Even update checks can be bypassed completely by downloading release installers manually from the repository releases page.

---

## 5. Security & Isolation

- **Read-Only Inspection**: Built-in viewers open files with read-only shared flags (`FILE_SHARE_READ`), ensuring they do not lock or modify files during preview.
- **Atomic File Saving**: Editors write modifications to a temporary staging file before issuing atomic replacement, preventing partial writes or corrupt states.
- **Safe Sandboxing**: Viewers rendering complex formats (such as 3D models and SVGs) execute inside isolated web workers without elevated shell permissions.
