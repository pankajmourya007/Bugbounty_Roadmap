# Google Dorking

## Overview
Google Dorking involves using advanced search queries on Google to uncover information that may not be readily available through conventional searches. This technique helps in finding sensitive data, hidden pages, and other useful information.

## Techniques
- **`site:`** - Searches within a specific site. Example: `site:example.com`
- **`filetype:`** - Finds files of a specific type. Example: `filetype:pdf`
- **`intitle:`** - Searches for specific text in the title. Example: `intitle:"index of"`

## Tools
- **Google Hacking Database (GHDB)** - A collection of search queries used for Google Dorking.
- **Dorking Tools** - Tools like `googlesearch.py` for automated dorking.

## Example
To find login pages on a specific site:
```plaintext
site:example.com inurl:login

