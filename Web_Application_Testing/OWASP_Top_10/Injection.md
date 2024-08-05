

# Injection

## Overview
Injection vulnerabilities occur when untrusted data is sent to an interpreter as part of a command or query. This can lead to unauthorized access or data manipulation.

## Types
- **SQL Injection** - Attacking SQL queries.
- **Command Injection** - Executing arbitrary commands on the server.

## Example
A SQL Injection example:
```sql
SELECT * FROM users WHERE username = 'admin' AND password = '';

