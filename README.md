# Mini Katalog Uygulaması

Bu proje, temel seviyede bir mobil e-ticaret katalog uygulaması taslağıdır. Widget yapısı, named routes ile sayfa geçişleri, model sınıfı oluşturma ve `fromJson` ile dinamik JSON listeleme mantığını içerir.

## Özellikler 
- **Discover Ekranı:** `GridView.builder` ile kart tabanlı dinamik ürün listeleme ve kampanya banner alanı.
- **Ürün Detay Ekranı:** `Route Arguments` ile taşınan ürüne ait detaylar, teknik özellikler ve sepet tetikleyicisi.
- **Sepet Ekranı:** Sepete eklenen ürünlerin listelenmesi ve sipariş tamamlama (`Checkout`) simülasyonu.

## Kullanılan Teknolojiler
- **Framework:** Flutter SDK 
- **Dil:** Dart SDK 
- **Çalışma Platformu:** Web (Google Chrome)

## Çalıştırma Adımları

1. Bağımlılıkları ve paket bağlantılarını yükleyin:
   ```bash
   flutter pub get