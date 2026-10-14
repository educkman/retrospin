# RetroSpin

Retro player skins for Spotify: Deck, Wheel, Recorder, Jukebox, 1-Bit, Hi-Fi, Car stereo, Disc wall, Vertical turntable, Reel-to-reel, Cassette.

## Put it online (GitHub Pages)
1. On github.com: **New repository** → name `retrospin` → **Public** → Create.
2. **Add file → Upload files** → drop in `index.html` (and this README) → **Commit**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → **Save**.
4. After ~1 minute the app is live at `https://<your-username>.github.io/retrospin/`.

## Connect Spotify (once)
1. Open the app → follow the 3 steps on screen (create an app at developer.spotify.com, add the shown Redirect URI, copy the Client ID).
2. **Optional, recommended:** open `index.html`, find `const CLIENT_ID='';` near the top of the script and paste your Client ID between the quotes, then upload again. From then on the start screen is just **“Log in with Spotify”** on every device.
3. Friends (max 5): add their Spotify email under *User Management* in the Spotify dashboard.

## Open on your phone
On a computer the login screen shows a QR code, and Settings → *Open on another device* shows one inside the app. Scan it with the phone camera.
