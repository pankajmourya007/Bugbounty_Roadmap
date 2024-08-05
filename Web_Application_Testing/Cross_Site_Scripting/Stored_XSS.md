

# Stored Cross-Site Scripting (XSS)

## Overview
Stored XSS involves injecting malicious scripts that are stored on the server and executed in the user's browser when they access the affected page.

## Example
Injecting a script into a comment field that gets displayed on a page:
```html
<script>alert('Stored XSS');</script>

