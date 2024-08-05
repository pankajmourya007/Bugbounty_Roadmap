
---

### 36. **Mobile_Application_Testing/iOS_Testing/Common_Vulnerabilities.md**

```markdown
# Common Vulnerabilities

## Overview
Common vulnerabilities in iOS applications include insecure data storage, improper use of cryptographic functions, and insufficient app-level security controls.

## Examples
- **Insecure Data Storage** - Sensitive data stored in unprotected places.
- **Improper Cryptography** - Using outdated or weak cryptographic methods.

## Example
Insecure data storage example:
```plaintext
Sensitive data stored in plain text in `NSUserDefaults`.

