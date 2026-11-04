# HackerTube Android app

A lightweight Android WebView wrapper for https://hackertube.org/.

## Included
- App name: HackerTube
- Standalone launcher activity
- JavaScript and local storage enabled for the site
- Video playback support and fullscreen custom-view handling
- Android back navigation
- Loading progress indicator

## Build an APK

### Option A: Android Studio
1. Install Android Studio on a computer.
2. Open this folder as an existing project.
3. Let Gradle sync and install the Android SDK Platform 35 if prompted.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. The debug APK is generated at `app/build/outputs/apk/debug/app-debug.apk`.

### Option B: GitHub Actions (no local Android setup)
1. Create a GitHub repository and upload the contents of this folder.
2. Open the repository's **Actions** tab.
3. Run **Build HackerTube APK** (or push to `main`).
4. Download the `HackerTube-debug-apk` artifact from the completed workflow.

The generated debug APK is suitable for personal testing and sideloading. Android may ask you to allow installation from the browser/file manager. This is an independent wrapper and is not an official HackerTube app. The site and its video providers control their own content and playback.
