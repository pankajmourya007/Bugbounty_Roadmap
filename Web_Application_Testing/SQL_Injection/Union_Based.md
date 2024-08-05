
---

### 16. **Web_Application_Testing/SQL_Injection/Union_Based.md**

```markdown
# Union-Based SQL Injection

## Overview
Union-Based SQL Injection involves using the UNION SQL operator to combine results from multiple queries into a single result.

## Techniques
- **Finding the Number of Columns** - Identifying the number of columns in the query.
- **Extracting Data** - Using UNION to extract data from other tables.

## Example
Basic Union-Based payload:
```sql
' UNION SELECT null, username, password FROM users--

