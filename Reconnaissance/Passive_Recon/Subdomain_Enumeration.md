


# Subdomain Enumeration

## Overview
Subdomain enumeration is the process of finding subdomains associated with a target domain. This can reveal additional attack surfaces or hidden areas of a website.

## Techniques
- **Brute Force** - Using a list of common subdomains and brute-forcing them.
- **DNS Zone Transfers** - Attempting a DNS zone transfer to obtain a list of subdomains.
- **Publicly Available Data** - Using services like VirusTotal, crt.sh, or security-related search engines.

## Tools
- **Sublist3r** - A Python tool for enumerating subdomains.
- **Amass** - An open-source tool for subdomain discovery and mapping.

## Example
Using `Sublist3r` to find subdomains:
```bash
sublist3r -d example.com

