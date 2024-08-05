
# Port Scanning

## Overview
Port scanning involves identifying open ports and services on a target system. This helps in understanding the attack surface and potential vulnerabilities.

## Techniques
- **TCP Connect Scan** - Establishing a full TCP connection to determine open ports.
- **SYN Scan** - Sending SYN packets to identify open ports without completing the handshake.

## Tools
- **Nmap** - A popular network scanning tool with various scanning techniques.

## Example
Performing a TCP connect scan with `Nmap`:
```bash
nmap -sT example.com

