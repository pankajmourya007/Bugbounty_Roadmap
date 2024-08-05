
---

### 18. **Web_Application_Testing/SQL_Injection/Blind_SQLi.md**

```markdown
# Blind SQL Injection

## Overview
Blind SQL Injection occurs when an application does not show errors, but the attacker can infer information based on the application's behavior.

## Techniques
- **Boolean-Based Blind SQLi** - Using true/false queries to infer information.
- **Time-Based Blind SQLi** - Using time delays to infer information.

## Example
Boolean-Based payload:
```sql
' AND 1=1--

