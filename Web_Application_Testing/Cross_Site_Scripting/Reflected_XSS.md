

# Reflected Cross-Site Scripting (XSS)

## Overview
Reflected XSS occurs when an attacker injects scripts into URLs or request parameters, and the scripts are reflected and executed immediately.

## Example
Injecting a script into a URL parameter:
```html
http://example.com/search?q=<script>alert('Reflected XSS');</script>

