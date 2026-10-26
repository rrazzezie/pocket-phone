# Julian's fictional iPhone simulator

A mobile-first static website designed for GitHub Pages. No build tools are required.

## Run it

Open `index.html` in a browser, or publish the contents of this folder to a GitHub repository and enable GitHub Pages.

## Passcode

`1406`

## Add your assets

The simulator deliberately leaves Julian's personal photos empty until you provide them. Add these files:

- `assets/photos/photo-1.jpg` through `photo-9.jpg` — the nine Photos gallery images.
- `assets/photos/instagram-1.jpg`, `instagram-2.jpg`, `instagram-3.jpg` — the three Instagram post photos.
- `assets/photos/x-numbers.jpg` — the supplied numbers image for `@ruleof_t1me`.

You can change the lock-screen/home-screen wallpaper from Settings during a session. The selected wallpaper is a temporary browser-session preview; refresh resets the simulator to the lock screen and default wallpaper.

## App icons

Brand icons use Simple Icons via CDN for recognizable app logos. System icons are local inline SVG artwork. Internet access is needed for the brand-logo images.

## Current behavior

- The passcode screen unlocks into the home screen.
- Refresh returns to the lock screen.
- Instagram has three post tiles and timeline captions, with intentionally empty photo slots until assets are added.
- LINE has the four supplied conversations. The chat composer allows local simulated replies.
- Notifications are simulated in-page. They do not send real device push notifications.
- YouTube opens the exact supplied URL in a new tab.
- Photos, Camera, Contacts, Calendar, Notes, Settings, X, Mail, Phone, Messages, and Safari have basic simulated screens.
- Music, Weather, Banking, and Maps icons are visible but cannot be opened.

All interactions are local to the page; messages and edits are not saved to a server.
