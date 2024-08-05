
---

### 24. **Web_Application_Testing/File_Inclusion/LFI.md**

```markdown
# Local File Inclusion (LFI)

## Overview
Local File Inclusion (LFI) allows attackers to include files from the local server, potentially exposing sensitive information.

## Techniques
- **Path Traversal** - Exploiting path traversal to access sensitive files.

## Example
LFI payload:
```plaintext
?page=../../../../etc/passwd

