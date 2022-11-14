# MaterialFox-Plus
***A Material Design-inspired userChrome.css theme for Firefox***

![Preview](https://typeling1578.github.io/MaterialFox-Plus/MaterialFox-Plus.png)
This theme is powered by blood, sweat, and coffee. If you like it, please consider helping out to support its continued development.

[![Buy fork source a coffee](https://typeling1578.github.io/MaterialFox-Plus/68747470733a2f2f73766773686172652e636f6d2f692f3859642e737667.svg)](https://www.buymeacoffee.com/n4ho5QX2l)

## What this does
Inspired by Google's Material Design and their latest Google Chrome UI, this theme turns your Firefox into a Material-styled web browser. The aim was to style the browser as closely as possible to Google Chrome, where practical.

This is a userChrome.css theme, which means you must manually add it to your Firefox profile. The theme overrides certain browser styles. Currently, only the main UI is affected (settings pages, etc. are not). More elements of the UI may be styled in the future but a broader scope becomes harder to maintain as Mozilla updates their browser code so some UI styles may be culled or redone if they become unmaintainable.

## What version do I use?
It works with the latest version or 102ESR of Firefox.

## Installation
1. [about:config] Set ```toolkit.legacyUserProfileCustomizations.stylesheets``` to ```true``` (default is ```false```).
2. [about:config] Set ```svg.context-properties.content.enabled``` to ```true``` (default is ```false```).
3. Copy the chrome folder into your Firefox profile directory. To find your profile directory, go to about:support or about:profiles.
4. See [Recommended instructions](#recommended-instructions) if you'd prefer a more Chrome-like experience.
5. Restart Firefox.

### Recommended instructions
Replicate Chrome behaviour for clipped tabs:
* [about:config] Set ```browser.tabs.tabClipWidth``` to ```83``` (default is ```140```).

Replicate Chrome's "Not Secure" text on HTTP:
* [about:config] Set ```security.insecure_connection_text.enabled``` to ```true```.

## Please note
* Windows 7 is no longer supported.
* Linux is no longer officially supported but you can give it a try – if you'd like to work on it feel free to make a PR.
* Some customisation settings may no longer work (such as compact/touch density).
* Some custom themes may clash with the address bar.
* Some themes using transparency might not work.
