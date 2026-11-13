# Hello World APK

A minimal Android app that displays "Hello, World!" — built as a starting point for exploring APK development. No app store involved; the goal is a direct sideloadable APK.

## Get the APK (no Android Studio needed)

1. Go to the **Actions** tab in this repo.
2. Open the latest **Build APK** run.
3. Download the `app-debug` artifact from the bottom of the page.
4. Unzip it — the APK is inside.
5. On your phone, allow installs from unknown sources for your browser or file manager, then tap the APK to install.

The workflow runs on every push to `main` using GitHub-hosted Ubuntu runners with JDK 17 and Gradle 8.10.2.

## Build it locally (optional)

1. Install [Android Studio](https://developer.android.com/studio).
2. Open this repo as a project (File → Open).
3. Let Gradle sync.
4. Run on an emulator or a connected device: **Run → Run 'app'**.

The debug APK lands at `app/build/outputs/apk/debug/app-debug.apk`.

## What's in here

- One Activity (`MainActivity.kt`) that inflates a single layout.
- The layout is just a centered TextView.
- Target SDK 35, min SDK 24, Kotlin, AppCompat.
- CI workflow at `.github/workflows/build.yml`.

Enough surface to poke at manifests, resources, the build pipeline, and headless CI without drowning in boilerplate.
