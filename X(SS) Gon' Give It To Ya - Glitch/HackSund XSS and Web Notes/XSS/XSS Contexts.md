# XSS Context
For XSS we need to identify:
1. Location within the response where attacker-controllable data appears
2. Input validation or processing

> Use the [XSS cheat sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet) to help test webapps and filters

## XSS between HTML Tags
When the XSS context is text between HTML tags, you need to introduce some new HTML tags designed to trigger execution of JavaScript.

Some useful ways of executing JavaScript are:

```
<script>alert(document.domain)</script>
<img src=1 onerror=alert(1)>
```


