# HTML Runner - Android App

Yeh app kisi bhi HTML code ko Android app ki tarah render karti hai.

## Features
- HTML code paste karein
- "RUN HTML" button dabayein
- HTML turant render ho jayega WebView mein
- JavaScript bhi support karta hai
- Back button se wapas editor pe aa jayein

## APK Build Karne Ka Tareeqa

### Option 1: Android Studio (Sabse Aasan)
1. Android Studio download karein: https://developer.android.com/studio
2. Android Studio mein "Open" karein aur `HTMLRunner` folder select karein
3. Gradle sync hone dein
4. Menu: Build > Build Bundle(s) / APK(s) > Build APK(s)
5. APK yahan milegi: `app/build/outputs/apk/debug/app-debug.apk`

### Option 2: Command Line (Agar Android SDK installed hai)
```bash
cd HTMLRunner
gradlew.bat assembleDebug
```
APK yahan milegi: `app/build/outputs/apk/debug/app-debug.apk`

### Option 3: Online Build (Bina kuch install kiye)
1. GitHub pe yeh project upload karein
2. GitHub Actions ya Codemagic.io use karein for cloud build

## Requirements
- Android SDK 21+ (Android 5.0 Lollipop aur upar)
- Gradle 8.2
- Kotlin 1.9.20
