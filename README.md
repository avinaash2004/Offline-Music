# Offline Music

A fully offline Android music player. It scans the songs on your phone automatically, has no ads, and the app has **no internet permission**.

## Features
- Auto-scan of all music (internal storage and SD card); updates by itself when you add or delete songs
- Songs, Albums, Artists, Folders tabs, search, sort
- Background playback with lock-screen and notification controls, headphone buttons, gapless
- Queue (play next, add to queue, remove, jump), shuffle, repeat, playback speed
- Playlists and favorites, "Recently added"
- Sleep timer (15/30/45/60 min or end of song)
- System equalizer shortcut, resumes where you left off
- Option to hide short clips (voice notes, ringtones)

## Get the APK

### Option A: GitHub (no installs)
1. Create a new GitHub repository and upload everything in this folder (keep the `.github` folder).
2. Open the **Actions** tab, choose **Build APK**, and click **Run workflow**.
3. When it finishes (about 5 minutes), download **OfflineMusic-apk** from the run page and unzip it.

### Option B: Android Studio
1. Open this folder in Android Studio and let it sync.
2. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
3. The APK is at `app/build/outputs/apk/`.

## Install
Copy the APK to your phone, open it, and allow "Install unknown apps" for your file manager when asked.
