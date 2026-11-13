# Hello World APK

A minimal Android app that displays "Hello, World!" — built as a starting point for exploring APK development.

## Build it

1. Install [Android Studio](https://developer.android.com/studio).
2. Open this repo as a project (File → Open).
3. Let Gradle sync.
4. Run on an emulator or a connected device: **Run → Run 'app'**.

The debug APK lands at `app/build/outputs/apk/debug/app-debug.apk`. You can sideload that straight onto a phone.

## What's in here

- One Activity (`MainActivity.kt`) that inflates a single layout.
- The layout is just a centered TextView.
- Target SDK 35, min SDK 24, Kotlin, AppCompat.

Enough surface to poke at manifests, resources, and the build pipeline without drowning in boilerplate.
