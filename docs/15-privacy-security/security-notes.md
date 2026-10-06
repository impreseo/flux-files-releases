# Security Technical Notes

## Overview
Technical documentation regarding memory hygiene, cryptographic implementations, and sandboxing.

## Cryptographic Primitives
- SHA-256 and SHA-512 utilize native Node.js crypto hardware acceleration.
- Archive encryption utilizes standard PKCS#5 PBKDF2 key derivation paired with AES-256-CBC.
- Memory hygiene ensures sensitive password strings are garbage-collected and overwritten promptly.

## Related
- [Privacy Policy](./privacy.md)
- [Local-First Architecture](./local-first.md)
