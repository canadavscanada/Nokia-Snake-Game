# Nokia-style Snake (Android)

## Get the APK (no Android Studio needed)
1. Create a free GitHub account, make a new repository, and upload everything in this folder
   (keep the `.github` folder).
2. Open the repo's **Actions** tab -> **Build APK** -> wait ~3 minutes for the green check.
3. Open the finished run, download the **snake-apk** artifact, unzip it -> `app-debug.apk`.
4. Copy the APK to your phone, tap it, and allow "Install unknown apps" when asked.

## Or build locally
Install Android Studio, open this folder, then Build > Build APK(s).
Output: app/build/outputs/apk/debug/app-debug.apk

The game itself lives in app/src/main/assets/index.html.
