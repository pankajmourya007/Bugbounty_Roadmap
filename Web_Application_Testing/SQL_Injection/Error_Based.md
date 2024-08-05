
---

### 17. **Web_Application_Testing/SQL_Injection/Error_Based.md**

```markdown
# Error-Based SQL Injection

## Overview
Error-Based SQL Injection involves manipulating SQL queries to produce error messages that reveal information about the database.

## Techniques
- **Generating Errors** - Crafting payloads that cause SQL errors.

## Example
Basic Error-Based payload:
```sql
' AND 1=CONVERT(int, CHAR(1))--

