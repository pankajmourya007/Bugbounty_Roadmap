--- 
### **12. Web_Application_Testing/OWASP_Top_10/XML_External_Entities.md**

```markdown

# XML External Entities (XXE)

## Overview
XXE vulnerabilities occur when XML parsers process external entities, which can lead to unauthorized access or disclosure of data.

## Types
- **External Entity Injection** - Injecting malicious XML entities.

## Example
An XXE payload that may read files from the server:
```xml
<!DOCTYPE foo [
  <!ENTITY xxe SYSTEM "file:///etc/passwd">
]>
<foo>&xxe;</foo>

