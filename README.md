# Let's play fonts

## Getting started

* Clone: `git clone https://github.com/denar90/lets-play-fonts && cd lets-play-fonts`
* Run:
    * `npm start`

## Learning

* Environment 
    * Device:  Nexus 5 device emulation
    * Network: 1.6 Mbps network throttling

Demo

![default-foic](https://user-images.githubusercontent.com/6231516/28908153-86131944-782a-11e7-954c-3ce58cea4d08.gif)


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

### font-display

[Read more](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-display)

----

* font-display: auto;

Example:

![font-display-auto](https://user-images.githubusercontent.com/6231516/28987206-ffd48864-7972-11e7-8b6a-fb17d121bea4.gif)

Wanna try it?

`git checkout font-display-auto`

----

* font-display: block;

Example:

![font-display-block](https://user-images.githubusercontent.com/6231516/28987205-ffd3201e-7972-11e7-9a83-475b6176a07a.gif)

Wanna try it?

`git checkout font-display-block`

----

* font-display: swap;

Example:

![font-display-swap](https://user-images.githubusercontent.com/6231516/28987216-05cf23d2-7973-11e7-9ce8-b041c69377d5.gif)

Wanna try it?

`git checkout font-display-swap`

----

* font-display: fallback;

Example:

![font-display-fallback](https://user-images.githubusercontent.com/6231516/28987215-05b49f1c-7973-11e7-99db-2b736ea3fb08.gif)

Wanna try it?

`git checkout font-display-fallback`

----

* font-display: optional;

Example:

![font-display-optional](https://user-images.githubusercontent.com/6231516/28987214-05b43554-7973-11e7-9a6e-d7dd1227ed63.gif)

Wanna try it?

`git checkout font-display-optional`
