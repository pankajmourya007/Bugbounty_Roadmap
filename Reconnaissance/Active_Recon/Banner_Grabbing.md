
---

### 7. **Reconnaissance/Active_Recon/Banner_Grabbing.md**

```markdown
# Banner Grabbing

## Overview
Banner grabbing is the process of obtaining information about a service running on a port by retrieving the banner that the service presents.

## Techniques
- **Telnet** - Connecting to a service port and reading the banner.
- **Netcat** - A utility for reading and writing data across network connections.

## Tools
- **Netcat** - For simple banner grabbing.

## Example
Using `Netcat` to grab a banner:
```bash
nc example.com 80

