## Stored XSS Xplained

Stored XSS (2nd order / persistent) arises when an application recieves data from an untrusted source and included that data in its HTTP responses in an unsafe way. Meaning that the recieved data is stored and provided to other users. 

## Impact 

The attacker can control the script which is executed on every victim's browser who visits the webpage where the Stored XSS lies. This allows him to carry out all the actions that are applicable to the impact of reflected XSS vulnerabilities. 

In stored XSS, the attacks are self-contained within the application itself. Users dpn't need to be induced into the vulnerability, rather, the exploit stays on the website itself. 

## Contexts

Depending on if and where the web app does validation/filtering, the payloads often vary. Meaning, if the web app has a filter on the client side, the payload would be different than if the filter is present on the server side.
