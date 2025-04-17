# AMTM Android App

This is a simple blank Android application with the title "AMTM".

## Building the APK

To build the APK, you'll need:

1. Java Development Kit (JDK) 8 or newer
2. Android SDK with Build Tools
3. Gradle 7.2 or newer

### Build Steps

1. Install Android Studio (which includes the JDK, Android SDK, and Gradle)
2. Open this project in Android Studio
3. Wait for Gradle sync to complete
4. From the menu, select Build > Build Bundle(s) / APK(s) > Build APK(s)
5. The APK will be generated at: `app/build/outputs/apk/debug/app-debug.apk`

### Command Line Build

If you prefer using the command line:

```
./gradlew assembleDebug
```

This will generate the APK at `app/build/outputs/apk/debug/app-debug.apk`

## Installation on Android Device

1. Enable "Install from Unknown Sources" in your Android device settings
2. Transfer the APK to your device
3. Tap on the APK file to install it
4. You should see the AMTM app in your app drawer 