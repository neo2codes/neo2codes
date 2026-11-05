# Hi, I'm neo2codes 👋

I build **browser userscripts** — small tools that fix specific annoyances
in the sites I use every day. All of them run entirely in your browser:
no accounts, no servers, no telemetry.

---

## Projects

### 🎬 [SubSensei ｜ 字幕老師](https://github.com/neo2codes/subsensei)

[![version](https://img.shields.io/badge/version-1.0.3-green.svg)](https://github.com/neo2codes/subsensei/blob/main/CHANGELOG.md)
[![languages](https://img.shields.io/badge/languages-14-orange.svg)](https://github.com/neo2codes/subsensei#字幕語言)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/neo2codes/subsensei/blob/main/LICENSE)

The official browser userscript of the **Subtitle Instrumentality Project (SIP)** —
a subtitle library of **125,014 entries across 14 languages**, built by running
speech recognition and local GPU translation over hundreds of hours of audio.

Automatic subtitle loading for MissAV, Jable, fs1.app and AV01, with subtitle
styling, picture adjustment, hotkeys, and a draggable panel. Supports
Tampermonkey and Safari Userscripts across desktop, iOS and Android.

`JavaScript` · `userscript` · `PocketBase` · `subtitles` · `local-first`

**[➜ Install](https://raw.githubusercontent.com/neo2codes/subsensei/main/dist/subsensei.user.js)**

---

### 🖼️ [YouTube Mid-Frame Thumbnails](https://github.com/neo2codes/youtube-midframe)

[![version](https://img.shields.io/badge/version-1.2.0-green.svg)](https://github.com/neo2codes/youtube-midframe/blob/main/CHANGELOG.md)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/neo2codes/youtube-midframe/blob/main/LICENSE)

Replaces YouTube's clickbait thumbnails with the **actual frame from the middle
of the video**, using YouTube's own storyboard sprite sheets — the same image
data the player already uses for the scrub-bar preview tooltip. The still frame
steps aside on hover so YouTube's own preview is never covered.

`JavaScript` · `userscript` · `Tampermonkey` · `YouTube`

**[➜ Install](https://cdn.jsdelivr.net/gh/neo2codes/youtube-midframe@main/dist/yt-midframe-thumbnails.user.js)**

---

### 🎈 [Subtitle Ball](https://github.com/neo2codes/subtitle-ball)

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/neo2codes/subtitle-ball/blob/main/LICENSE)

A universal **floating-ball subtitle panel** userscript for any website with an
HTML5 video player. Load a local `.srt` file onto whatever video is on the page.
Includes subtitle styling (colour, size, position), picture adjustment
(brightness / contrast / saturation), and hotkeys.

Everything runs locally — **no account, no network calls, no telemetry.**

`JavaScript` · `userscript` · `Tampermonkey` · `Userscripts`

---

## What I care about

| Principle | How it shows up |
|---|---|
| **Local-first** | Every tool runs entirely in your browser; nothing is uploaded |
| **Minimal permissions** | `@grant none` where possible — no network beyond the site itself |
| **Graceful fallback** | If something fails, the original page is left untouched |
| **Honest limits** | Known limitations are documented in each README, not hidden |

---

## Tech I use

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tampermonkey](https://img.shields.io/badge/-Tampermonkey-444444?style=flat-square)
![PocketBase](https://img.shields.io/badge/-PocketBase-B8E986?style=flat-square)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## Support

If something here saved you some time, you can buy me a coffee — it goes
straight back into fixing things.

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-support-ffdd00?logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/neo2codes)

---

## Contact

Bug reports and feature requests are best filed on the relevant repository's
Issues page. For anything else, open an issue on whichever project fits best.
