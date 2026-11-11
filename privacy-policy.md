# Nook Tab privacy policy

_Last updated: 11 November 2026_

Nook Tab replaces your browser's new tab page. It has no accounts, no analytics, no advertising and no server of its own. The developer never receives any of your data.

## What stays on your device

Everything you set up is saved in your browser's local storage for this extension and nowhere else: your theme and appearance choices, layout, shortcuts, to-do list, the name shown in the greeting, an uploaded background image, and the city used for the live sky. Removing the extension deletes it.

## What is sent to other services

The page asks a few public services for things it displays. Each request contains only what is listed here.

| When | Sent | To |
|---|---|---|
| Shortcuts are shown with "Themed" icons (the default) | A guess at the brand name of each shortcut's site, such as `github` | jsDelivr (cdn.jsdelivr.net), which hosts the Simple Icons set |
| A site is not in that icon set, or "Original site icons" is chosen | The address of each shortcut's site, such as `https://github.com` (never the full link) | Google's favicon service (t3.gstatic.com) |
| The "Material 3" theme is active | A request for the Google Sans Flex font | Google Fonts (fonts.googleapis.com, fonts.gstatic.com) |
| The "Live sky" background is on and you typed a city | The city name, once, to find its coordinates | Open-Meteo (geocoding-api.open-meteo.com) |
| The "Live sky" background is on and a place is set | That place's coordinates, rounded to two decimals (about 1 km), every 20 minutes | Open-Meteo (api.open-meteo.com) |
| You set a background image by web address | A request for that image | The site hosting the image |

As with any web request, these services also see your IP address. Choosing "Letters" for shortcut icons, a theme other than Material 3, and a background other than Live sky means the page makes none of these requests.

## Searches

Text typed in the search box goes to the search engine you picked. "Default" hands the search to your browser, which uses the engine set in your browser settings. The extension does not record or send your searches anywhere else.

## Location

"Use my location" asks the browser for your position only when you click it. The coordinates are rounded to two decimals, saved on your device, and used only for the Open-Meteo requests above.

## Sharing a setup

"Export" writes a file to your device containing your appearance, layout, shortcuts and background. It leaves out your name, to-dos and city. Nothing is uploaded; you decide who gets the file.

## Contact

Questions about this policy: _add your contact email or a link to your issue tracker here before publishing._
