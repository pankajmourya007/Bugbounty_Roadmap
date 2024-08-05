---
### 14. **Web_Application_Testing/OWASP_Top_10/Cross_Site_Scripting.md**

```markdown
 # Cross-Site Scripting (XSS)

## Overview
XSS vulnerabilities allow attackers to inject malicious scripts into web pages viewed by other users.

## Types
- **Stored XSS** - Malicious scripts stored on the server.
- **Reflected XSS** - Malicious scripts reflected off the server.

## Example
A reflected XSS payload:
```html
<script>alert('XSS');</script>

