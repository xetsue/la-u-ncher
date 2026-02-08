# Fork - La/u/ncher `4.2.5`
<img width="660" height="365" alt="1000471715" src="https://github.com/user-attachments/assets/2320d05a-b363-4774-820f-ffa1586e844a" />

## Use In Browser https://xetsue.github.io/la-u-ncher/

> Original code forked from [Nilesr](https://github.com/nilesr/)

## Website Changelog 
Patches done to `index.html` include,
- ​New Default Theme: Set Empire as the primary theme fallback for first-time loads.
- ​Theme Logic Fix: Resolved an issue where the homepage would appear empty if no theme was manually customized in the app settings.
- QoL Update: Added Pong to the main page with bots autoplay and user controls when interacted.
- ><img width="1080" height="1241" alt="1000471754" src="https://github.com/user-attachments/assets/fe3b2538-907d-4c4e-8ce9-a0f6cd4dbd8b" />

  
- ​Code Structure: Added secondary validation to the theme variable to ensure assets are retrieved even if the property service returns a null or empty string.

## Legacy App Release
<img width="188" height="102" alt="1000471629" src="https://github.com/user-attachments/assets/28e8ce7f-bba0-4ff1-929f-ab307962f4af" />

Can be found in [United4/releases](https://github.com/nilesr/United4/releases/tag/4.2.5)

F-Droid App Page: [La/u/ncher](https://f-droid.org/packages/com.angryburg.uapp/)

Play Store: `[ Outaded ]` ~~[Unavailable](https://play.google.com/store/apps/details?id=com.angryburg.uapp)~~


# Legacy Records
### Known Recorded bugs

- ~~Changing the bar color won't take full effect until all UserscriptActivity instances are destroyed (i.e. rotating the screen or restarting the app)~~ Fixed in 4.1.5
- Creating a new thread, then going to the thread watcher and unwatching it, then replying to the thread with "Watch thread on reply disabled" will watch the thread again because ?watch is still in the URL
- ~~Creating a new thread sometimes leads to negative "new post" values in the thread watcher~~ Should be fixed in 4.2.2, never could quite reproduce this accurately
- Reportedly cannot be uninstalled on a zenfone max first series
- Reportedly infinite scroll is broken

### Recorded todo list

- control+f
- allow user to specify their own hex code for toolbar_color
- actual toggles that don't require recreating the whole list for settings, little > arrows on the right for more menus
- supposedly userscript is not drawing bar if opening thread via thread watcher
- display board in thread watcher
- supposedly scrolls all the way up when unwatching a thread

### Past Wishlist

- Use API + native view rather than webview - the api lacks a lot of stuff only available through the site
- Better app fonts, specifically the patch notes button font; title bar font? https://www.dafont.com/cyberpunkwaifus.font?
- Add inner padding for patch notes button
- Fix infinite scrolling
- Bigger page numbers (accidental click on the footer)

# License

La/u/ncher is released under the GPLv3
