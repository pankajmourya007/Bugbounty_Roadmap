
---

### 8. **Reconnaissance/Active_Recon/Directory_Bruteforcing.md**

```markdown
# Directory Bruteforcing

## Overview
Directory bruteforcing is used to discover hidden directories and files on a web server by brute-forcing common directory names.

## Techniques
- **Brute-Force Lists** - Using lists of common directories and files to brute-force access.

## Tools
- **Gobuster** - A tool for directory and file brute-forcing.
- **DirBuster** - A GUI tool for directory and file brute-forcing.

## Example
Using `Gobuster` to brute-force directories:
```bash
gobuster dir -u http://example.com -w /path/to/wordlist.txt

