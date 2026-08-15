# Okey Yazboz (Capacitor)

Okey 101 ve 81 için skor tutma uygulaması.

## Özellikler
- 101 Okey (Tekli + Eşli)
- 81 Okey (Eşli)
- +50 Ceza butonu
- Kafa (-100) butonu
- Özel puan girişi
- El geçmişi
- Kazanan gösterimi

## Kurulum (Capacitor - Android APK)

### 1. Gereksinimler
- Node.js 18+
- Android Studio
- Java 17+

### 2. Kurulum Adımları

```bash
# Repoyu klonla
git clone https://github.com/ahmetbayrak19-afk/okey-yazboz.git
cd okey-yazboz

# Bağımlılıkları yükle
npm install

# Android platformunu ekle
npx cap add android

# Web dosyalarını senkronize et
npx cap sync

# Android Studio'yu aç
npx cap open android
```

Android Studio açıldıktan sonra:
1. Bir cihaz veya emülatör seç
2. **Run** butonuna bas
3. APK oluşturmak için: **Build → Build Bundle(s) / APK(s) → Build APK(s)**

## Notlar
- `www/` klasörü web dosyalarını içerir
- `capacitor.config.ts` uygulama ayarlarını tutar
- App ID: `com.okeyyazboz.app`
