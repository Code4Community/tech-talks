# Browser Caching

## Instructions

1. Start a Python http server in this directory: `python3 -m http.server` or `python -m http.server`
1. Load [http://localhost:8000](http://localhost:8000) in Google Chrome
1. Reload the page until script.js is consistently loaded from cache
    * You can verify this by opening the "Network" tab of Chrome Developer Tools
1. Change line 1 of script.js from `alert('Old alert message!')` to `alert('New alert message!')`
1. Reload the page
    * You should see the old error message
    * Since browser caching is non-deterministic, this step may not work

## Resources

MDN: [HTTP caching](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching)

Amir Boroumand: [A Web Developer's Guide to Browser Caching](https://www.codebyamir.com/blog/a-web-developers-guide-to-browser-caching)
