
---

### 6. **Reconnaissance/Active_Recon/Service_Enumeration.md**

```markdown
# Service Enumeration

## Overview
Service enumeration involves identifying the services running on open ports. This helps in understanding the type and version of the services, which can aid in identifying potential vulnerabilities.

## Techniques
- **Banner Grabbing** - Connecting to a service and retrieving its banner to identify the service and version.
- **Service Version Detection** - Using tools to detect service versions.

## Tools
- **Nmap** - For service version detection.
- **Netcat** - For banner grabbing.

## Example
Using `Nmap` for service version detection:
```bash
nmap -sV example.com

