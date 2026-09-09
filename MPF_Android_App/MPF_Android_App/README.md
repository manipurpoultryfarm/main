# Manipur Poultry Farm Android App

This Android app wraps the MPF HTML dashboard in a WebView using `https://appassets.androidplatform.net` so local assets load with an HTTPS origin.

## Build with Android Studio
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK will be under `app/build/outputs/apk/debug/app-debug.apk`.

## Build automatically with GitHub
Push this project to GitHub. The included GitHub Actions workflow builds a debug APK. Open the Actions tab, run **Build Android APK**, then download the `MPF-APK` artifact.
