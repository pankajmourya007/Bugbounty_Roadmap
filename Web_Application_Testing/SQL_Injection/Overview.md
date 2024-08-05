

# SQL Injection

## Overview
SQL Injection is a type of attack that allows an attacker to interfere with the queries an application makes to its database. It can result in unauthorized access to data.

## Types
- **Union-Based SQLi** - Using UNION SQL operator to combine results.
- **Error-Based SQLi** - Using error messages to gain information.

## Example
Basic SQL Injection payload:
```sql
' OR '1'='1

