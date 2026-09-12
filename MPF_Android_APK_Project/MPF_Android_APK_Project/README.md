# Manipur Poultry Farm Android APK

This Android project packages the supplied `index main(8).html` as `app/src/main/assets/index.html`.

## Build APK on GitHub (easiest)
1. Create a new GitHub repository.
2. Upload **all files and folders inside this project** to the repository root.
3. Open the repository's **Actions** tab.
4. Open **Build MPF APK**.
5. Click **Run workflow** (or push any change to `main`).
6. When the build is complete, open the build and download the artifact named **MPF-Manipur-Poultry-Farm-APK**.
7. Unzip the downloaded artifact. The APK inside is `MPF-Manipur-Poultry-Farm.apk`.

## Build with Android Studio
Open this folder in Android Studio, allow Gradle sync, then use:
**Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## Included Android support
- JavaScript + DOM/local storage
- Internet access for Supabase/CDN resources
- HTTPS-style local app origin (`https://app.local/`)
- File/photo/document chooser
- Blob/download bridge for generated Excel/PDF/JSON files
- WhatsApp / phone / email external links
- Android back navigation + exit confirmation
- Portrait/landscape support

## Important
This ZIP contains a debug-build workflow. Debug APKs install normally for testing/internal use. For Play Store or public release, create and protect a signing keystore and build a signed release APK/AAB.
