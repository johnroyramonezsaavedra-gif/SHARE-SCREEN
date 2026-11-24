# Screen Pair

Turn spare devices into extra screens. One device shares its screen and sound; others join by scanning a QR code.

## Publish on GitHub Pages (free)

1. Sign in at github.com, click **New repository**, name it `screen-pair`, keep it **Public**, click **Create repository**.
2. Click **uploading an existing file**, drag in ALL files from this folder (`index.html`, `sw.js`, `manifest.webmanifest`, and the three `icon-*.png`), then click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**, then **Save**.
4. After about a minute your app is live at `https://YOUR-USERNAME.github.io/screen-pair/`.

## Install it on each device

Open the link once while online, then:
- **Chromebook / Windows / Mac (Chrome or Edge):** tap **Install this app on the device** on the home page (or the install icon in the address bar).
- **Android (Chrome):** tap **Install this app on the device**, or menu → **Install app**.
- **iPhone/iPad (Safari):** Share → **Add to Home Screen**.

After the first online visit the app opens without internet.

## Note on connecting

The app opens offline, but pairing two devices uses PeerJS's free public service for the first handshake, so both devices need internet at that moment. Video and sound then go directly between the devices.
