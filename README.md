# Zed release feed

This repository hosts the Zed app files (APKs) and the update metadata that the
apps read. Direct links:

| File | What it is |
|---|---|
| `apks/ZedTV_v1.4.3.apk` · `apks/ZedTV_latest.apk` | **Zed TV** (Android TV / Google TV, v1.4.3, Android 8.0+) |
| `apks/ZedTV_v6.2.0.apk` | Zed TV older line (kept for existing installs) |
| `apks/ZedMovies_v6.2.0.apk` · `apks/ZedMovies_latest.apk` | **Zed Movies** (Android phones) |
| `apks/ZedTV_v1.4.2.apk`, `apks/MovieBoxTv_*` | previous / other builds |
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

## Install (TV)

1. On the TV, install **Downloader** from the Play Store and open it.
2. Type `zedmods.com/tv` → Install → allow "unknown sources" for Downloader.
3. Open **Zed TV** and enter your PIN (or link the TV at `zedmods.com/activate`).
4. **Upgrading from an older Zed TV (v6.2.x or earlier)?** Uninstall the old app
   first, then install v1.4.3 — the two lines cannot replace each other.

Since v1.4.3 the app checks for updates itself: on start you get **Check for
Updates** and **Fix Account**; the activation screen has an **Updates & Account**
button. TVs running Android 8.0 and newer are supported.

## Install (phone)

`zedmods.com/app` — Zed Movies (Android 8.0+). Old **Munowatch Pro** installs get
a working update prompt that installs Zed Movies for them. iPhone/iPad and PCs:
use the web player at `watch.zedmods.com` with the same PIN.

Support & activation: **@ZedMediaBot** · updates: **@tfasthub**

_All rights reserved. APKs are provided for licensed customers only._