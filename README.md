# StatsAnaliz – iOS

StatsAnaliz uygulamasının iOS sürümü (Swift / Xcode).

- **Paket kimliği:** `com.statsanaliz.app`
- **Sürüm:** 1.0
- **Proje:** `statsAnaliz.xcodeproj`
- **Sürekli entegrasyon:** Codemagic (`codemagic.yaml`)

Aynı uygulamanın Android sürümü için bkz. [stats-google-webview](https://github.com/bertanaslan4/stats-google-webview).

## Yapı

- `statsAnaliz/`: Uygulama kaynak kodu
- `statsAnalizTests/`: Birim testleri
- `statsAnalizUITests/`: Arayüz testleri
- `codemagic.yaml`: Codemagic derleme ve dağıtım ayarları

## Gereksinimler

- Xcode (güncel sürüm)

## Çalıştırma

1. `statsAnaliz.xcodeproj` dosyasını Xcode ile açın.
2. Bir simülatör seçip **Cmd + R** ile çalıştırın.

## Güvenlik notu

Bu repoda dağıtım sertifikası (`.p12`), provisioning profili ve Codemagic ayarları bulunmaktadır. Bunlar gizli bilgi içerdiği için repodan kaldırılmalı ve Apple Developer / Codemagic üzerinden yenilenmelidir. Bkz. ayrıca `codemagic.yaml`.

## Lisans

Lisans dosyası bulunmamaktadır.
