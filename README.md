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

## Changelog
- **1.9.4** - App icon: white R on an orange record
- **1.9.3** - BPM: fetch ISRC from track details, plain Deezer search fallback
- **1.9.2** - BPM diagnosis (tap the BPM display), retries failed lookups
- **1.9.1** - Terminal: full-width progress bar, BPM status and tap
- **1.9** - BPM numbers on every deck (Deezer + GetSongBPM), TAP tempo, pitch sliders on all DJ decks
- **1.8** - Terminal skins (single + DJ split) with commands, ASCII disc, code rain; lists follow what is playing
- **1.7** - DJ setups: twin turntables, CD decks and tape decks with mixer, next track from the queue, BPM and key
- **1.6** - DJ prep: GetSongBPM credit, Client ID built in
- **1.5** - Text, vinyl and cassette colours; orange/white play and stop buttons; orange and white finishes
- **1.4** - Album art on big screens (side, backdrop, framed)
- **1.3** - One-tap login, QR code to open on phone
- **1.2** - Classic deck with EQ window, disc wall, car night panel, dolphins
- **1.1** - Turntable, reel-to-reel, cassette, circle visualizer, mic mode
- **1.0** - First version: wheel, deck, hi-fi, car and more

## Credits
BPM & key data by [GetSongBPM](https://getsongbpm.com).
