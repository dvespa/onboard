# All Aboard V12

Files:
- index.html — main menu
- live_trains.html — V9 Friday timetable tracker
- stations.html — Hurstbridge station list (hidden from the V10 home menu for now)
- chat.html — local chat prototype
- settings.html — optional profile/chat/notification settings
- assets/all-aboard-melbourne.png — Melbourne/MCG home image

Upload all files/folders to the same GitHub Pages repository root.

Settings are optional and currently saved only in the browser using localStorage.
No login or backend is required for this V10 prototype.


## V11 changes
- Stations remains hidden from the main menu.
- Chat now opens with a train confirmation screen.
- Prototype service: 9:57 Hurstbridge to City.
- User taps "Join Train Chat" before entering the conversation.
- "Choose a different train" returns the user to the live trains screen.


## V12 location-gated chat
- Train chat access is restricted to a matched service.
- The user's phone GPS is compared with the timetable-estimated position of active Friday Hurstbridge services.
- Base chat radius: 300 metres.
- GPS accuracy is tolerated up to an additional 150 metres for the prototype.
- Successful verification grants a 5-minute local grace period.
- If verification expires, chat is blocked until the user verifies again.
- Location is not displayed to other travellers.
- This is timetable-based service matching, not live train GPS.


## Compact home-screen update
- Home is redesigned to fit on a single iPhone screen.
- Hero image is cropped to remove the menu graphics embedded in the original artwork.
- Live Trains, Chat and Settings use compact horizontal cards.
- No scrolling should be required on typical modern iPhones.
