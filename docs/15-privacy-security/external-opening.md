# External Program Execution & Sandbox Security

## Overview
When opening files in external applications, Flux Files follows security best practices to protect the user against malicious payloads.

## Security Practices
- **Executable Warnings**: Opening executable files (`.exe`, `.bat`, `.cmd`, `.vbs`, `.ps1`) triggers a safety confirmation prompt before launching.
- **Sanitized Paths**: Path arguments passed to Windows Shell `ShellExecute` are properly quoted and sanitized to prevent command-injection vulnerabilities.

## Related
- [Security Notes](./security-notes.md)
- [Windows Integration](../12-windows/windows-integration.md)
