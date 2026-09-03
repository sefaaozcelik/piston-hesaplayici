# Piston Hesaplayıcı

Hidrolik silindir / piston hesaplama aracı. Tek dosya, bağımsız (offline) çalışan HTML uygulaması.

## Dosyalar
- `piston-hesap-standalone.html` — güncel web sürümü (v7)
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
