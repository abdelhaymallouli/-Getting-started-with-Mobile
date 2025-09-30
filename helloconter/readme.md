# 5.1.5 – Generate the debug APK

## 📒 Quick glossary
- **APK** — Installable file of an Android app.
- **assembleDebug** — Action that generates the debug APK.
- **ADB** — Tool that installs APK on emulator or device.

---

## ✅ Objective
Get a debug APK and verify that it installs and opens on a device or emulator.

---

## 1) Generate the APK
### Using Android Studio
1. Open your project in **Android Studio**.
2. Go to **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
3. Wait until the build finishes.
4. The APK file is generated at:


app/build/outputs/apk/debug/app-debug.apk


### Using command line (optional)
From your project root, run:


./gradlew assembleDebug # macOS/Linux
gradlew assembleDebug # Windows

APK will be at the same location:


app/build/outputs/apk/debug/app-debug.apk


---
