# CART3R.FF UNIVERSAL TOOLKIT

Native Android companion app for Free Fire and Free Fire MAX. Targets Android 15 (API 35), minimum Android 6.0 (API 23). No native ABI-specific libraries are used, so the APK is architecture-independent.

## Features
- Crimson/black Android UI
- Aim tapping trainer
- Headshot/drag movement practice simulator
- Spin coordination practice
- Sensitivity profile calculator
- HUD layout planner
- DPI calculator
- Basic in-session training statistics
- GitHub Actions APK build workflow

## Build APK with GitHub Actions
1. Create a GitHub repository.
2. Upload all files and folders from this project, including `.github`.
3. Open the Actions tab.
4. Run **Build CART3R FF Universal APK** (or push to main/master).
5. Download artifact `CART3R-FF-UNIVERSAL-APK`.
6. Extract `app-debug.apk` and install on Android.

## Local build
Open the project in Android Studio, sync Gradle, then run `gradle assembleDebug` or use Build > Build APK.

## Compatibility note
"Universal" means this companion app is not tied to a specific Free Fire / Free Fire MAX release or CPU ABI. It does not mean it can modify or inject into every game version. It does not interact with game memory or automate gameplay.

## Safety / scope
This is a practice companion only. It does not implement aimbot, automatic spin bot, auto-fire, game modification, memory reading, code injection, or anti-cheat evasion. The current starter keeps statistics in memory only; permanent history can be added in a later version.
