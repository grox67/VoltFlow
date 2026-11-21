# VoltFlow

A starter Android Studio project for a neon charging animation.

## Open and build
1. Install Android Studio.
2. Open this folder as a project.
3. Let Gradle sync and install the Android SDK 35 platform if prompted.
4. Connect an Android phone with USB debugging enabled, or use an emulator.
5. Press Run.

## Important Android limitation
The project listens for `ACTION_POWER_CONNECTED` and attempts to open a lock-screen-capable activity. Android 10+ and some device manufacturers restrict apps from launching activities while in the background. The app includes a manual preview, but automatic lock-screen launch is not guaranteed on every phone. This starter project has not been compiled or tested on physical devices.
