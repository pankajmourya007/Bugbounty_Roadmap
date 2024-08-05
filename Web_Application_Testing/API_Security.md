--- 
### 28. **Web_Application_Testing/API_Security.md**

```markdown
# API Security

## Overview
API Security involves protecting APIs from various threats and vulnerabilities. Secure APIs prevent unauthorized access, data breaches, and other attacks.

## Techniques
- **Authentication** - Ensuring that only authorized users can access the API.
- **Authorization** - Restricting access to specific actions or data based on user roles.
- **Input Validation** - Checking that API inputs are valid and safe.

## Example
Ensuring that an API requires authentication:
```http
GET /api/user/profile
Authorization: Bearer <token>

