# Engagement E-Invite: QR -> real 3D bike ride to the hall

Static site (HTML/CSS/JS only) - works on GitHub Pages. No API keys.

## Files
- `config.js`  -> names, date, venue, **exact hall lat/lng**, bike colours, ride length
- `index.html` -> the experience (don't need to edit)

## 1. Set the exact hall location (do this first!)
After deploying, open  `https://YOUR-USER.github.io/REPO/?setup`
Tap the hall on the map or drag the pin (or paste "lat, lng" from Google Maps).
Then either:
- copy the values into `config.js`, or
- use the "Copy link" button: that link already carries the location (`?lat=..&lng=..`). Make the QR from it.

## 2. Test from anywhere
`?from=12.95,80.14` fakes the visitor's start point, e.g. `.../?from=12.95,80.14`

## 3. Deploy (free)
GitHub repo -> upload all files -> Settings -> Pages -> main / root.

## 4. QR
Put your final link in any QR generator, print on the invitation.

## Phone location notes
- Location popup shows only after the visitor taps "Location allow panni start" (phone Chrome blocks auto-popups).
- Works only on https (GitHub Pages is https). `http://192.168.x.x` from a phone will NOT ask for location.
- If the QR opens inside an in-app viewer, tap "Open in Chrome".
