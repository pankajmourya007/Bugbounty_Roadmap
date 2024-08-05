
---

### 51. **Tools_and_Techniques/Gobuster.md**

```markdown
# Gobuster

## Overview
Gobuster is a tool for directory and file brute-forcing on web servers.

## Features
- **Directory Brute-Forcing** - Identifies hidden directories and files.
- **DNS Subdomain Brute-Forcing** - Enumerates subdomains.

## Example
Brute-forcing directories with Gobuster:
```bash
gobuster dir -u http://example.com -w /path/to/wordlist.txt

