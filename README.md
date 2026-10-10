# Knockturn Alley – Android app

A full-screen Android browser app that opens https://theknockturnalley.com/

Features: in-app browsing, back button navigation, fullscreen video (rotates to landscape),
autoplay for the web player, cookies/logins remembered, downloads, file uploads, loading bar.

## Get the APK – Option A: GitHub (no install needed)
1. Create a new repository on github.com and upload all files from this folder
   (including the hidden `.github` folder).
2. Open the **Actions** tab – the "Build APK" job starts automatically (~3–5 min).
3. Open the finished run, download **KnockturnAlley-apk** under *Artifacts*, unzip it.
4. Copy `app-release.apk` to your phone and open it (allow "Install unknown apps").

## Option B: Android Studio
Open this folder in Android Studio → let it sync → **Build > Build APK(s)**.

## Change the website
Edit `HOME_URL` in `app/src/main/java/com/knockturn/app/MainActivity.java`.
