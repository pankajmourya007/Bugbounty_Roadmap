
---

### 44. **Cloud_Security_Testing/Common_Vulnerabilities.md**

```markdown
# Common Cloud Security Vulnerabilities

## Overview
Common cloud security vulnerabilities involve misconfigurations and insufficient protection of cloud resources, potentially leading to data breaches and unauthorized access.

## Examples
- **Misconfigured Security Groups** - Security groups allowing overly permissive access.
- **Unencrypted Data** - Storing sensitive data without encryption.
- **Exposed APIs** - APIs that are accessible without proper authentication or authorization.

## Example
Misconfigured security group allowing all inbound traffic:
```plaintext
Inbound rule: 
Type: All traffic
Protocol: All
Port range: All
Source: 0.0.0.0/0

