[READMENN.md](https://github.com/user-attachments/files/34847372/READMENN.md)[Uploading READ<div align="center">

# 👻 Ghost Media Player

**A fast, free, offline-first media player with a DJ deck, a car-radio, live TV, 37 themes and an instrument-swapping sound engine.**

Windows · Linux · Browser · Android (Capacitor)

`Free` · `No accounts` · `No ads` · `No telemetry` · `MIT licensed`
Screenshot_2026-11-12_14-19-03.png
Screenshot_2026-11-12_14-20-12.png
Screenshot_2026-11-12_14-21-01.png
Screenshot_2026-11-12_14-21-21.png
Screenshot_2026-11-12_14-21-31.png
Screenshot_2026-11-12_14-21-43.png
Screenshot_2026-11-12_14-21-55.png
Screenshot_2026-11-12_14-22-16.png
Screenshot_2026-11-12_14-49-21.png
Screenshot_2026-11-12_14-54-31.png
Screenshot_2026-11-12_14-59-09.png
Screenshot_2026-11-14_14-22-53.png
</div>

---

Ghost Media Player plays your videos, songs, images and GIFs, and then goes much further than a normal player. You can scratch records on a two-deck DJ mixer, swap the drums in any song for a tabla or a taiko, remove the vocals for karaoke, listen to internet radio on a car-stereo style head unit, watch IPTV channels, and completely change how the app looks, from colours all the way to the layout of the control bar.

Everything runs from one shared HTML/CSS/JavaScript core (`www/`). No cloud, no sign-up, no paid API.

<p align="center">
  <img src="docs/screenshots/themes.png" width="49%" alt="Themes panel with live previews" />
  <img src="docs/screenshots/dj-mode.png" width="49%" alt="DJ Mode with two decks and a crossfader" />
</p>

## Contents

Open the section you want, each one is a tab:

<details open>
<summary><b>⭐ 1. Why Ghost is different</b></summary>

<br>

| You get | What it means |
|---|---|
| **Sound Tone (instrument swap)** | Keep the singer, change the band. Every kick, snare and hi-hat in the song triggers a real instrument hit instead: Tabla & Harmonium, Dholak & Bhangra, Darbuka & Oud, Djembe & Kalimba, Taiko & Shamisen, Congas & Organ. Live DSP, not AI. |
| **Real DJ Mode** | Two decks, a crossfader, BPM analysis, loops, scratching **with true reverse audio**, backspin, vinyl brake, 16 beat pads and a step sequencer with Indian rhythms. |
| **37 themes + 14 control styles + 10 whole-app layouts + 6 3D looks** | You are not just changing colours. You can rearrange the entire player. |
| **Glyphwire theme** | A live black-and-white text-art background where the ghost is drawn with glitching characters. |
| **Vocal remover & Voice changer** | Karaoke mode, plus Chipmunk, Child, Deep Man, Monster, Demon, Robot, Alien, Telephone and Megaphone voices on any song or video. |
| **Bass Monster, Earthquake sub, MAX BEAT** | Heavy bass that is meant to be felt, plus a loudness maximizer. |
| **Car-radio head unit** | Worldwide internet radio with VOL and TUNE rotary knobs, a tuner scale and 6 preset keys. |
| **Live TV** | Load any IPTV `.m3u` playlist as a searchable channel list, played by a built-in HLS engine. |
| **Disc images** | Open `.iso` files directly and stream the media out of them (desktop app). |
| **Background Visuals** | Put your own image, GIF or looping video behind your music. |
| **100 % English UI, no tracking** | No account, no ads, no telemetry. |

</details>

<details>
<summary><b>🎬 2. Player features</b></summary>

<br>

**Opening media**
- Open files, **drag and drop** anywhere, or open a whole **folder**
- Video, audio, images and animated GIFs in one player
- **Stream** tab: paste a direct link to a video, audio file or internet radio stream (`.pls` / `.m3u` playlists are resolved for you)
- **TV** tab: IPTV playlists as channels
- **Disc ISO** support (desktop app)

**Playback controls**
- Play, pause, stop, previous, next, seek bar with buffered indicator
- Speeds: **0.25x, 0.5x, 0.75x, 1x, 1.25x, 1.5x, 2x, 3x**
- Loop: off, playlist, single item
- **Shuffle** (random order, no repeats until the whole list has played)
- Autoplay next item, default volume
- **Mini Player** and fullscreen
- **Volume boost 100 % to 400 %** through a limiter to reduce clipping
- **Sleep timer**: 15 / 30 / 45 / 60 / 90 minutes, the sound fades out softly and then playback pauses

**Library**
- Playlist with instant search
- "Recently opened" history (see the note about this in the *Honest limits* tab)

**Images**
- Image viewer with previous / next, counter and fullscreen
- Animated GIFs stay real GIFs

**Reliability**
- A corrupt or unsupported file shows a clear message and offers **Skip to next**. It never crashes the app.

**Keyboard shortcuts**

| Key | Action |
|---|---|
| `Space` | Play / pause |
| `←` `→` | Seek 5 seconds |
| `↑` `↓` | Volume |
| `M` | Mute |
| `N` / `P` | Next / previous |
| `L` | Loop |
| `F` | Fullscreen |
| `I` | Mini player |
| `O` | Orb navigation menu |
| `Alt` + `U` | Cycle through the UI designs |

</details>

<details>
<summary><b>🎨 3. Look and design (the big one)</b></summary>

<br>

<img src="docs/screenshots/settings.png" width="60%" alt="Settings panel" />

Ghost has **four separate layers of customisation**. They combine freely, so the number of possible looks is huge.

### 37 complete themes
Each theme sets colours, the backdrop of the playback area, the font and the corner shape.

| Group | Themes |
|---|---|
| **Classic** | Ghost, Obsidian, Monochrome |
| **Colour moods** | Neon City, Midnight, Cyber, Aurora, Ice, Crimson, Deep Space, Sunset, Ocean, Forest, Ember, Sakura |
| **Retro** | Retro (amber CRT), Terminal (green monospace), Luna Bay (retro blue desktop), Vaporgrid (sun over a neon grid), Blueprint (white lines on blue), Studio (docked player, amber keys) |
| **Combat / tactical** | Frontline Ops (tactical HUD), Iron Fist (heavy armour), Toxic Lab (hazard yellow on carbon) |
| **Text-art** | **Glyphwire** (live black-and-white text-art, glitching glyphs) |
| **Luxury** | Midas (black marble and gold), Royal Velvet, Rose Gold, Desert Dune |
| **Playful / glass** | Glass, Hologram, Lava Lamp, Comic Pop (halftone dots), Tokyo Rain |
| **Light** | Matcha Latte, Arctic Day, Paper |

Plus **custom accent and background colours** (colour pickers) on top of any theme. Theme previews are inline SVG, so they show correctly in the packaged desktop app too.

### 14 control styles ("framework" change)
This changes the top bar, control bar, buttons and sliders, not just colours.

Modern Classic · Glass · Cyberpunk · Minimalist · Classic Analog · Retro Desktop · Tactical · Glyph · Neon Grid · Modern Dock · Soft Touch · Neon Ring · Hi-Fi Receiver · Bubble Pop

While the style is set to *Match theme*, **every theme has its own play-button shape**, not only its own colour.

### 10 Advanced UI Designs (whole-app layouts)
These move the real controls: library side, control bar, volume and seek. Every button keeps working. Press **Alt + U** to cycle.

| Design | Idea |
|---|---|
| Normal | The classic Ghost layout |
| Mirror Deck | Library on the right, big play puck on a docked deck |
| Cockpit Rails | Keys on left and right rails, volume on top, seek along the bottom |
| Floating Island | Rounded floating cards and a centred glass capsule |
| Cinema Drawer | Full-bleed stage, library slides out, slim one-row bar |
| Broadcast Console | Console at the top with a tally LED and level meter |
| Pocket Dock | Four floating glass pills at the bottom, nothing else |
| Top Ribbon | One slim ribbon along the top, library on the left |
| Theater Right | Library slides in from the right, centred player capsule |
| Corner Capsule | A small player floating in the bottom-left corner |

### 3D look: 6 styles × 4 strengths
Depth is drawn with shadows and gradients only. **Nothing tilts, jumps or moves**, so clicking stays easy. A small light spot follows your pointer across a button.

- **Strength:** Smooth · Normal (buttons only) · Medium (buttons, bars, cards) · Deep (everything)
- **Style:** Classic Bevel · Glossy Jelly · Soft Clay · Arcade Block · Brushed Metal · Crystal Glass

### Orb navigation
A small glass orb under the logo. Hover it, click it or press `O` and the menu expands with a staggered animation. Prefer a plain list? Turn it off in Settings.

### Background Visuals
Add your own **image, animated GIF or video** and it fills the whole playback area behind your music.
- Starts empty. Nothing is bundled or downloaded.
- Videos are always muted, loop, and pause with the music.
- Files are copied into the app's own storage, so deleting the original changes nothing.
- Rename, preview, remove, opacity slider, reset.

</details>

<details>
<summary><b>🔊 4. Sound and Effects</b></summary>

<br>

<img src="docs/screenshots/effects.png" width="45%" alt="Effects panel" />

Effects are **off by default**, so normal playback stays untouched until you switch them on. They work on songs *and* videos.

### Quick presets
Normal · Deep Voice · High Voice · Bass Boost · Radio · Echo · DJ · Night Mode

### Fine controls
Bass · Treble · Pitch (±12 semitones, real pitch shifting without changing tempo) · Echo · Reverb · Distortion · Low-pass · High-pass · Stereo balance · Night mode (heavy compression: quiet parts lifted, loud parts tamed)

### Vocal remover (karaoke)
Remove the voice sitting in the middle of a stereo song, or switch to **Voice only**. Adjustable amount.

### Voice changer
Chipmunk · Child · Deep Man · Monster · Demon · Robot · Alien · Telephone · Megaphone, plus an extra pitch slider.

### 🥁 Sound Tone: swap the instruments
Keep the singer, change the band.

| Tone | Region |
|---|---|
| Tabla & Harmonium | India |
| Dholak & Bhangra | Punjab, India |
| Darbuka & Oud | Arabic world |
| Djembe & Kalimba | West Africa |
| Taiko & Shamisen | Japan |
| Congas & Organ | Latin America |

Kicks, snares and hats in the song are detected live and replaced by synthesised instrument hits. A harmonium or pad **drone** plays underneath, and you can pick its key (C to B). Sliders: new instrument level, quiet the original drums, drone level. It follows the beat it hears, so tempo changes are followed too.

### Bass Monster and Earthquake
- **Bass punch**: deep shelf plus harmonics, so even laptop speakers hit
- **Earthquake sub**: a heavy 30 to 80 Hz layer
- **MAX BEAT**: one button for the maximum. It is **extremely loud**, lower your system volume first.

### HD sound
- **HD clarity** adds air and detail
- Optional **96 kHz engine** (if your sound card allows it, restart to apply)

</details>

<details>
<summary><b>🎧 5. DJ Mode</b></summary>

<br>

**Two decks. One crossfader.** Load a local audio file per deck (Load button, drag and drop, or "Load from library").

**Per deck**
- Play / pause / stop, seek, **CUE** (hold to preview), waveform overview
- Manual loop IN / OUT and **beat loops**: ½, 1, 2, 4, 8, 16 beats
- **Tempo ±12 %** with key lock on / off, **TAP** tempo, **SYNC**, **ANALYZE** (BPM and beat grid)
- Channel volume, gain, bass, treble, filter (low-pass / high-pass), echo with delay time, reverb, distortion, level meters

**Turntable feel**
- **Drag the jog disc** forward or backward: the track is read at exactly that speed and direction, with **true reverse audio**
- Mouse-wheel scratch
- **BACKSPIN**, **REVERSE** (hold), **BRAKE** (vinyl stop), **SPIN-UP**, **SLOW-MO ½**

**Mixer**
- Equal-power crossfader, master volume with limiter
- Transitions A↔B: timed crossfade, beat-synced, or loop-based
- Live beat-offset readout between the decks

**Pro rack**
- Bass Monster, Earthquake sub, Loudness maximizer, **MAX BEAT**
- Voice changer, vocal remover / voice-only, HD clarity

**16 beat pads** (also playable from the keyboard)

| | | | |
|---|---|---|---|
| 808 KICK `Q` | DHOL `W` | TILLI `E` | SNARE `R` |
| CLAP `A` | HI-HAT `S` | OPEN HAT `D` | TOM `F` |
| AIR HORN `Z` | SIREN `X` | LASER `C` | BASS DROP `V` |
| RISER `T` | SUB BOOM `G` | SYNTH STAB `B` | REWIND `Y` |

All pad sounds are **synthesised live**, no sample files are bundled.

**16-step sequencer** with editable patterns: Wedding Baraat · Punjabi Bhangra · Dhamaal Max · EDM 4/4 · Trap 808 · Dembow · Empty

</details>

<details>
<summary><b>📻 6. Radio, 📺 Live TV and 🎤 Lyrics</b></summary>

<br>

### Radio (car-stereo head unit)
- Stations come from the public **Radio Browser** directory: no key, no account
- Browse by **country, region, language or genre**, or search by name
- **VOL** and **TUNE** rotary knobs: drag, mouse wheel or arrow keys
- Tuner scale and **6 favourite preset keys**
- Favourites ❤️ and recently played are saved locally
- No listening limits of any kind. Dropped streams reconnect automatically.
- Honest status: "ON AIR" appears only when audio is really playing
- Nothing is requested from the network until you open Radio for the first time

### Live TV (IPTV)
- Load any IPTV `.m3u` playlist (the public **iptv-org** list is the default) as a **searchable channel list**
- Built-in **HLS engine** (`js/ghosthls.js`, no external library): live and VOD playlists, MPEG-TS and fMP4, AES-128 encryption, automatic quality choice
- **Desktop app:** channels that the browser engine cannot play are converted on the fly with **ffmpeg** (bundled through `ffmpeg-static`, or your system `ffmpeg`)

### Lyrics
Shows lyrics for the song that is playing. Real data only, **nothing is invented and nothing is downloaded**.

Sources, in order:
1. Lyrics you loaded manually before (remembered)
2. A `.lrc` / `.txt` with the same name as the song (select or drop them together)
3. Desktop app: a same-named file next to the song
4. Lyrics embedded in the file's tags (MP3 USLT, FLAC LYRICS)

Timestamped **LRC** lyrics follow the real playback position: active line, auto-scroll, click a line to seek, ±0.5 s sync nudge, `[offset:]` support. Plain text is shown and clearly labelled "not synchronized".

</details>

<details>
<summary><b>📦 7. Install and build</b></summary>

<br>

### Quick try (no install)
Open `www/index.html` in any modern browser. Desktop-only features (disc ISO, ffmpeg conversion, same-folder lyrics, native Background Visual store) need the desktop app.

### Run the desktop app
Requires **Node.js 18+**.

```bash
git clone https://github.com/<your-username>/ghost-media-player.git
cd ghost-media-player
npm install
npm start
```

`npm install` also downloads a matching **ffmpeg** (package `ffmpeg-static`) for live TV conversion. If that download is blocked, the app uses the `ffmpeg` already installed on your computer (`sudo apt install ffmpeg`).

### Build installers

```bash
npm run dist:win      # Windows: installer (NSIS) + portable .exe
npm run dist:linux    # Linux: AppImage + .deb
npm run dist:all      # both (Windows build on Linux needs Wine)
```

Output goes to `release/`.

### Linux notes
- AppImage / .deb start with `--no-sandbox` (the usual fix for an app that will not open or shows a blank window)
- Software video decoding is the default for stability. Advanced users can enable VA-API hardware decoding with `GHOST_HWDEC=1 ghost-media-player`

### Android (Capacitor)
The Capacitor config is included, the native `android/` project is generated on your machine:

```bash
npm run cap:add:android    # one time
npm run cap:sync           # after any change in www/
npm run cap:build:debug    # debug APK
```

Needs a JDK (17 recommended) and the Android command-line SDK. The 3.x features were built and tested for desktop and browser first. On Android, plain-HTTP radio streams are blocked by the secure WebView, so "HTTPS only" is on by default there.

### Run the tests

```bash
node tests/make-fixtures.js /tmp/fx
GHOST_FX=/tmp/fx python3 tests/test_dj.py
GHOST_FX=/tmp/fx python3 tests/test_lyrics.py
GHOST_FX=/tmp/fx python3 tests/test_responsive.py
node tests/analysis.test.js
```

(Python + Playwright + Chromium.)

</details>

<details>
<summary><b>🔒 8. Privacy</b></summary>

<br>

- **No account, no sign-up, no ads, no telemetry, no analytics**
- Your files are never uploaded anywhere
- Settings, favourites and themes are stored locally on your device
- The app only touches the network when **you** use a network feature: opening **Radio** (talks to the Radio Browser directory and the station), loading a **Stream** link, or loading **TV** playlists and channels
- No external fonts or images are loaded. The interface is fully self-contained and starts instantly, even offline.

</details>

<details>
<summary><b>⚠️ 9. Honest limits</b></summary>

<br>

We would rather tell you what does not work than let you find out.

- **Formats** depend on the Chromium engine inside the app (H.264/AAC MP4, WebM, Ogg, MP3, AAC, WAV, FLAC and more). Not everything plays.
- **Not supported:** DVD-Video (VOB / MPEG-2) and menus, copy-protected discs, audio-CD ripping, DRM / SAMPLE-AES channels, plain web-page links.
- **Live TV:** many public IPTV channels are offline or geo-blocked. HEVC and unusual codecs rely on the desktop app's ffmpeg conversion.
- **Vocal remover** is centre-channel cancellation, not AI stem separation. Reverb and doubled vocals remain a little.
- **Sound Tone** is live filtering and synthesis, not AI. Original drums are turned down, not erased. It works best on songs with a clear beat.
- **HD clarity** cannot invent quality that a low-bitrate file never had.
- **DJ BPM** assumes one constant tempo. Tracks over about 12 minutes are not analysed (use TAP). Beat alignment is approximate (a few ms with key lock off, about ±20 ms with key lock on). Loops use media-element seeking, not sample-exact.
- **Bass / table shake** depends on your speakers or subwoofer. **MAX BEAT is very loud.**
- **Library and "Recently opened":** browsers cannot keep a file handle across restarts, so the playlist lives for the session and "Recent" remembers only name, size, type and date. Open the file again to play it.
- The UI is **English only** by design (the page is marked no-translate and the desktop app forces the English locale).

</details>

<details>
<summary><b>🗂️ 10. Project structure</b></summary>

<br>

```
ghost-media-player/
├── www/                     # The actual app, shared by every platform
│   ├── index.html
│   ├── css/                 # style, themes, 3D look, advanced layouts, DJ, radio, lyrics
│   └── js/
│       ├── app.js           # UI wiring, settings, shortcuts
│       ├── player.js        # Unified video / audio engine
│       ├── themes.js        # 37 themes + control styles + custom colours
│       ├── uidesign.js      # 10 whole-app layouts
│       ├── look3d.js        # 3D look (6 styles × 4 strengths)
│       ├── glyph.js         # Glyphwire text-art stage
│       ├── audiofx.js       # Boost + effects presets
│       ├── dsp.js           # Vocal remover, voices, Sound Tone, bass, HD
│       ├── dj.js, dj-pro.js, djanalysis.js   # DJ Mode
│       ├── radio.js         # Radio head unit
│       ├── streams.js, ghosthls.js           # Folder / Stream / TV / ISO + HLS engine
│       ├── lyrics.js, tags.js                # Lyrics engine + tag reader
│       ├── visuals.js       # Background Visuals
│       ├── nav.js, screens.js, library.js, version.js
├── electron/                # Desktop shell: window, stream proxy, ffmpeg, ISO reader
├── build/                   # App icons
├── tests/                   # DJ, lyrics, responsive and analysis tests
├── scripts/check-ffmpeg.js
├── capacitor.config.json    # Android (Capacitor)
└── package.json
```

</details>

---

## Credits and license

**Made by J Studio** · Developed by **Jasmeet**

Released under the **MIT License**. Use it, change it, share it.

If Ghost Media Player is useful to you, a ⭐ on the repo is the best thank-you.
MENN.md…]()
