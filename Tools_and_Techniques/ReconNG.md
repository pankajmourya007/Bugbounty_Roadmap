

# ReconNG

## Overview
ReconNG is a web reconnaissance framework for gathering information about targets.

## Features
- **Modular Framework** - Extensible with various modules for different reconnaissance tasks.
- **Data Collection** - Collects information from multiple sources.

## Example
Running a ReconNG module to gather domain information:
```bash
recon-ng
[recon-ng] > use recon/domains-hosts/google_site
[recon-ng] > set SOURCE example.com
[recon-ng] > run

