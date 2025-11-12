# JEE 48yrs Android App (skeleton)

This project is a complete Android Studio project skeleton implementing:
- Room database for questions
- CSV importer (assets + file-uri)
- Jetpack Compose UI to browse and search questions

## How to build
1. Install Android Studio and Android SDK (compileSdk 34) and Java 17 SDK.
2. Open the project folder `jee48yrs_project` in Android Studio.
3. Let Gradle sync and then Run the app on an emulator or device.
4. To build an APK from command line:
   - `./gradlew assembleDebug` (Linux/macOS) or `gradlew.bat assembleDebug` (Windows)
   - The debug APK will be at `app/build/outputs/apk/debug/app-debug.apk`

## Notes about compiling here
I cannot compile APKs in this environment because the Android build toolchain (Gradle + SDK + Java) is not available here. This ZIP contains a ready-to-import project you can build locally or set up CI (GitHub Actions).

