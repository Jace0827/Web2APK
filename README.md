# Web2Apk - Convert Your Website to an Android App

## Requirements
- **Minimum SDK:** API 21 (Lollipop)
- **Languages Used:** Java, Kotlin

## How to Change the Website URL
To modify the URL that the app loads, follow these steps:

1. Navigate to:  
   ```
   app/src/main/java/com/example/web2apk/MainActivity.java
   ```
2. Locate the following line in `MainActivity.java`:
   ```java
   myView.loadUrl("https://myURL");
   ```
3. Replace `"https://myURL"` with your desired website URL.
4. Save the file.

## How to Build the APK
Follow these steps to build the APK:

1. Open **Android Studio**.
2. Click on **Build** in the top menu.
3. Select **Build Bundle(s) / APK(s)** → **Build APK(s)**.
4. Wait for the build process to complete.

## APK Output Location
Once the APK is built, you can find it in the following directory:

```
app/build/outputs/apk/debug/app-debug.apk
```

If you are generating a **release** APK, it will be located at:

```
app/build/outputs/apk/release/app-release.apk
```

For a signed APK, make sure to generate it through **Build → Generate Signed Bundle/APK...** and follow the signing process.
