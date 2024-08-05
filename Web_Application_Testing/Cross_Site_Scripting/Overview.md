
---

### 19. **Web_Application_Testing/Cross_Site_Scripting/Overview.md**

```markdown
# Cross-Site Scripting (XSS) Overview

## Overview
Cross-Site Scripting (XSS) is a vulnerability that allows attackers to inject malicious scripts into web pages viewed by other users.

## Types
- **Stored XSS** - Injected scripts are stored on the server and executed when users access the affected page.
- **Reflected XSS** - Scripts are reflected off the web server and executed in the user's browser.

## Example
Basic XSS payload:
```html
<script>alert('XSS');</script>

