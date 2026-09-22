# WARKOP POS MLT — Build APK Gratis via GitHub Actions

## 1. Repository
Upload seluruh isi folder project ke repository GitHub baru.

## 2. Debug
Actions -> Build Warkop POS MLT APK -> Run workflow.
Artifact: `WARKOP_POS_MLT-debug-apk`.

## 3. Release
Buat Repository Secrets berikut:
- `ANDROID_KEYSTORE_BASE64`
- `ANDROID_KEYSTORE_PASSWORD`
- `ANDROID_KEY_ALIAS`
- `ANDROID_KEY_PASSWORD`

Lalu jalankan `Build Warkop POS MLT Release APK`.
Artifact: `WARKOP_POS_MLT-release-apk`.

## 4. Konfigurasi URL
Edit hanya konstanta WEBSITE_URL di `app/src/main/java/com/krianapps/warkoppos/mlt/MainActivity.java` sebelum build apabila URL Netlify MLT final berbeda.
