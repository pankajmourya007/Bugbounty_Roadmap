

# Network Scanning

## Overview
Network scanning involves discovering active devices on a network and identifying open ports and services. This helps in mapping the network and identifying potential vulnerabilities.

## Techniques
- **Ping Sweep** - Identifying live hosts on the network.
- **Port Scanning** - Determining which ports are open on a host.

## Tools
- **Nmap** - A widely-used network scanning tool.
- **Masscan** - A fast network scanner.

## Example
Using `Nmap` for network scanning:
```bash
nmap -sn 192.168.1.0/24

