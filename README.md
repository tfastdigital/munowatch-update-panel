# Zed release feed

This repository hosts the Zed app files (APKs) and the update metadata that the
apps read. Direct links:

| File | What it is |
|---|---|
| `apks/ZedTV_v1.4.9.apk` · `apks/ZedTV_latest.apk` | **Zed TV** (Android TV / Google TV, v1.4.9, Android 8.0+) |
| `apks/ZedTV_v6.2.0.apk` | Zed TV older line (kept for existing installs) |
| `apks/ZedMovies_v6.2.7.apk` · `apks/ZedMovies_latest.apk` | **Zed Movies** (Android phones, v6.2.7) |
| `apks/ZedTV_v1.4.2.apk`, `apks/ZedMovies_v6.2.0.apk`, `apks/MovieBoxTv_*` | previous / other builds |
| `update.json`, `dialog/update.json` | version metadata read by the apps |
| `dialog/update-apps.json`, `dialog/tv.json` | per-app update config (source for the live update nodes) |

Direct links (always the newest build):

```
TV:    https://raw.githubusercontent.com/tfastdigital/munowatch-update-panel/main/apks/ZedTV_latest.apk
TV:    https://cdn.jsdelivr.net/gh/tfastdigital/munowatch-update-panel@main/apks/ZedTV_latest.apk
Phone: https://raw.githubusercontent.com/tfastdigital/munowatch-update-panel/main/apks/ZedMovies_latest.apk
Phone: https://cdn.jsdelivr.net/gh/tfastdigital/munowatch-update-panel@main/apks/ZedMovies_latest.apk
```

Friendly links: **zedmods.com/tv** (TV app) · **zedmods.com/app** (phone app) ·
**zedmods.com/tvhelp** (TV install guide, six methods) · **watch.zedmods.com** (web player).

## What's new

**Zed Movies v6.2.7** - fewer errors when opening a title. If a title fails once
(for example while the app refreshes your session) the app now quietly fixes it and
opens the title; you only see an error if it truly fails twice. Titles that are not
available now say so clearly instead of hanging, and recovery after watching a movie
is smoother.

**Zed TV v1.4.9** - the same protection on TV: a title that fails once now quietly
retries and continues, session recovery is better, and unavailable titles show a
clear message.

## MovieBox (English audio)

MovieBox now plays in **English by default**: when a title has an English audio track
it plays in English, otherwise it plays the original audio. Downloads use the English
audio too, and titles that support English show **[English]** instead of [Hindi].

Download: **zedmods.com/moviebox** (page with the download button and steps) — direct APK:
`https://github.com/tfastdigital/munowatch-update-panel/releases/download/moviebox-endub-20260930/MovieBox_Zed.apk`

How to use: install the APK (allow "Install unknown apps" if Android asks), open
MovieBox and enter your Zed PIN when asked, then browse and watch. Downloads are
saved in the Movies/MovieBox folder on your phone.

## Install (TV)

1. On the TV, install **Downloader** from the Play Store and open it.
2. Type `zedmods.com/tv` → Install → allow "unknown sources" for Downloader.
3. Open **Zed TV** and enter your PIN (or link the TV at `zedmods.com/activate`).
4. **Upgrading from an older Zed TV (v6.2.x or earlier)?** Uninstall the old app
   first, then install v1.4 — the two lines cannot replace each other.

Since v1.4.3 the app checks for updates itself: on start you get **Check for
Updates** and **Fix Account**; the activation screen has an **Updates & Account**
button. TVs running Android 8.0 and newer are supported. v1.4.9 keeps the clear
PIN handling from v1.4.4 and adds the quiet retry for titles that fail to load once.

## Install (phone)

`zedmods.com/app` — Zed Movies (Android 8.0+). v6.2.7 adds the quiet retry for
titles that fail to load once, a clear message for unavailable titles and smoother
recovery after watching. Old **Munowatch Pro** installs get a working update prompt
that installs Zed Movies for them. iPhone/iPad and PCs: use the web player at
`watch.zedmods.com` with the same PIN.

Support & activation: **@ZedMediaBot** · updates: **@tfasthub**

_All rights reserved. APKs are provided for licensed customers only._
