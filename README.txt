EASE BUILD ANDROID APP PROJECT

This is a native Android WebView wrapper around the current Ease Build website, with the website bundled locally.

HOW TO BUILD AN APK:
1. Install Android Studio on a Windows, Mac, or Linux computer: https://developer.android.com/studio
2. Extract this ZIP.
3. In Android Studio, choose Open and select the extracted EaseBuildAndroid folder.
4. Wait for Gradle sync and install the Android SDK components it requests.
5. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When finished, choose Locate in the notification to find app-debug.apk.
7. Transfer app-debug.apk to your Android phone and open it to install. You may need to allow installation from that source.

APP DETAILS:
- App name: Ease Build
- Package ID: com.easebuild.app
- Minimum Android: Android 6.0 (API 23)
- Website UI is bundled in app/src/main/assets/index.html
- Internet permission is included for external images and web links.
- The project source is provided; an APK has NOT been compiled in this environment because Android SDK/Gradle are not installed here.
- This is a basic WebView APK. Online enquiry storage, customer login, payments, supplier inventory, and a live admin panel are not implemented by this wrapper.
- Before Google Play publishing, set up a signing key, review current Play target API requirements, privacy policy, and app content declarations.
