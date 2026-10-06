# Eddy Android App

This is a real Android project for Eddy.

Included:
- Installable Android APK build
- Native microphone permission and speech recognition
- Native Android text-to-speech
- Local persistent memory via WebView storage
- Eesar recognition
- No reset button
- GitHub Actions workflow that builds the APK automatically

## Build on GitHub

1. Create a GitHub repository named `eddy-android`.
2. Upload all files from this project.
3. Push to the `main` branch.
4. Open **Actions**.
5. Open **Build Eddy APK**.
6. Tap **Run workflow** if it is not already running.
7. When it finishes, open the workflow run and download the `Eddy-debug-apk` artifact.
8. Extract the ZIP and install `app-debug.apk` on Android.

The current `eddy.html` is a working local app shell. Replace that file with your more advanced Eddy HTML when ready. The Android bridge remains the part that gives the app native microphone and speech output.
