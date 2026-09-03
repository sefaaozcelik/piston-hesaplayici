# Piston Hesaplayıcı

Hidrolik silindir / piston hesaplama aracı. Tek dosya, bağımsız (offline) çalışan HTML uygulaması.

## Dosyalar
- `piston-hesap-react.html` — **iOS / mobil sürüm**. React 18 + ReactDOM gömülü tek dosya,
  harici çalışma zamanı yok. Hesaplar localStorage'da kalıcı (`ozmaksan.piston.v1`).
  Safari'de aç → "Ana Ekrana Ekle" ile uygulama gibi çalışır.
- `piston-hesap-standalone.html` — web sürümü (v7, `__bundler` formatı)
- `piston-hesap-scriptsiz.html` — script'siz varyant
- `design/` — Claude Design canvas kaynak dosyaları
- `android/` — Android Studio WebView sarmalayıcı projesi
- `dist/Piston_Calc.apk` — derlenmiş Android paketi (debug imzalı)

## APK derleme
```
cd android
./gradlew.bat assembleDebug
# çıktı: app/build/outputs/apk/debug/app-debug.apk
```

Claude ile hazırlanmıştır.
