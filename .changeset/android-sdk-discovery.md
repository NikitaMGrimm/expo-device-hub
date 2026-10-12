---
"expo-device-hub": patch
---

Find the Android SDK without `ANDROID_HOME`: from the `adb` or `emulator` on PATH, then from Android Studio's default folder on macOS, Linux, and Windows. Android app icons now load when only `adb` and `emulator` are on PATH. When `aapt2` or the emulator is missing, the error names the SDK folders that were checked.
