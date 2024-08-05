
---

### 23. **Web_Application_Testing/Remote_Code_Execution.md**

```markdown
# Remote Code Execution (RCE)

## Overview
Remote Code Execution (RCE) vulnerabilities allow attackers to execute arbitrary code on a server or client machine.

## Types
- **Command Injection** - Executing commands on the server.
- **Code Injection** - Injecting code that the server executes.

## Example
Command injection payload:
```bash
; ls -la

