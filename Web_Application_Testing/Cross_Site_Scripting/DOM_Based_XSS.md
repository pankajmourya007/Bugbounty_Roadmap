

# DOM-Based Cross-Site Scripting (XSS)

## Overview
DOM-Based XSS occurs when the malicious script is executed as a result of modifying the DOM (Document Object Model) in the browser.

## Example
Injecting a script into URL fragment identifiers:
```html
http://example.com/#<script>alert('DOM-Based XSS');</script>

