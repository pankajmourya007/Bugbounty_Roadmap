

# Insecure Direct Object References (IDOR)

## Overview
IDOR vulnerabilities occur when an attacker can access objects or resources by modifying input parameters.

## Techniques
- **Parameter Tampering** - Changing parameters to access unauthorized resources.

## Example
Accessing another user’s account by changing the user ID in the URL:
```plaintext
http://example.com/profile?id=2

