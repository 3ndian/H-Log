# Health Log

A private, offline health tracker. One page, no network requests, data encrypted on your device.

## Put it on GitHub Pages
1. On github.com create a new repository with a non-obvious name (free accounts need it public for Pages; the repo holds only this app, never your data).
2. Upload everything in this folder: index.html, sw.js, manifest.webmanifest, the three icon PNGs, README.md.
3. Settings -> Pages -> Deploy from a branch -> main / root. Wait a minute, then open the URL it shows.

## iPhone
Open the URL in Safari -> Share -> Add to Home Screen. Use it from the Home Screen icon (this also protects storage from being cleared).

## Mac / Linux
Open the same URL in any browser. Create the vault there with the same or a different passphrase.

## Moving data between devices
Settings -> Back up -> encrypted file or "HL1:" text. Send it by AirDrop, Files/iCloud Drive, email to yourself, Universal Clipboard, Syncthing, LocalSend or KDE Connect. On the other device use Import: records merge by ID, newest edit wins, and original notes stay locked.

## Passkey
Passkeys (Face ID / Touch ID) need https and are tied to the web address. If the address changes you lose the passkey, never the data: the passphrase always works. Keep a backup file.

## Wipe
Settings -> Wipe everything (two steps plus a hold) deletes the vault, caches and service worker for this site.

Not medical advice. Reference ranges are general.
