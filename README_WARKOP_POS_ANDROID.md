# Warkop POS MLT — Android Free Wrapper

Android WebView wrapper untuk Warkop POS Multi-Cabang. Native WebView menangani HTML file chooser, gallery/file picker, camera capture, download, dan printing.

## App ID
`com.krianapps.warkoppos.mlt`

## URL
Konfigurasi di `app/src/main/java/com/krianapps/warkoppos/mlt/MainActivity.java` pada konstanta `WEBSITE_URL`.

## GitHub Actions
- Debug: `Build Warkop POS MLT APK`
- Release: `Build Warkop POS MLT Release APK`

Release membutuhkan repository secrets: `ANDROID_KEYSTORE_BASE64`, `ANDROID_KEYSTORE_PASSWORD`, `ANDROID_KEY_ALIAS`, `ANDROID_KEY_PASSWORD`.
