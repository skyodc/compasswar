# Compass Wars Android v11

Bu paket, Compass Wars World v11 web oyununu Android WebView içine alan Android Studio projesidir.

## APK alma

1. Android Studio'yu aç.
2. `Open` ile bu klasörü seç.
3. Gradle sync tamamlanınca:
   - `Build > Build Bundle(s) / APK(s) > Build APK(s)`
4. APK şu klasörde oluşur:
   - `app/build/outputs/apk/debug/app-debug.apk`

## Notlar

- Oyun harita verisini CDN üzerinden aldığı için telefonda internet bağlantısı gerekir.
- Uygulama landscape modda açılır.
- Paket adı: `com.mbozguven.compasswars`
- Minimum Android: Android 6.0 / API 23

## Yayın için

Google Play'e koymak istersen:
- `Build > Generate Signed Bundle / APK`
- Yeni bir keystore oluştur
- Release APK/AAB üret
