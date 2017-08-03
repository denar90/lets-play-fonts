# Let's play fonts

## Getting started

* Run:
    * npm start

## Terminology

FOIC - flash of invisible content.
FOUC - flash of unstyled content.

### Browsers strategy

FOIC - Chrome, Firefox, Safari, Opera

FOUC - Edge, IE

### css-font-timeout

Browser            | timeout      | fallback  | swap
------------------ | ------------ | --------- | --------
Chrome 35+         | 3 seconds    | yes       | yes
Firefox            | 3 seconds    | yes       | yes
Internet Explorer  | **0 seconds**| yes       | yes
Safari             | N/A          | N/A       | N/A


More - [css-font-timeout](https://github.com/igrigorik/css-font-timeout)