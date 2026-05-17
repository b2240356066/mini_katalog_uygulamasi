# Mini Katalog Uygulaması

Bu proje, temel seviyede bir mobil e-ticaret katalog uygulaması taslağıdır. [cite_start]Widget yapısı, named routes ile sayfa geçişleri, model sınıfı oluşturma ve `fromJson` ile dinamik JSON listeleme mantığını içerir[cite: 5, 102, 103].

## Özellikler 
- [cite_start]**Discover Ekranı:** `GridView.builder` ile kart tabanlı dinamik ürün listeleme ve kampanya banner alanı[cite: 105].
- [cite_start]**Ürün Detay Ekranı:** `Route Arguments` ile taşınan ürüne ait detaylar, teknik özellikler ve sepet tetikleyicisi[cite: 104, 106].
- [cite_start]**Sepet Ekranı:** Sepete eklenen ürünlerin listelenmesi ve sipariş tamamlama (`Checkout`) simülasyonu[cite: 106].

## Kullanılan Teknolojiler
- [cite_start]**Framework:** Flutter SDK [cite: 9]
- [cite_start]**Dil:** Dart SDK [cite: 10]
- **Çalışma Platformu:** Web (Google Chrome)

## Çalıştırma Adımları

1. Bağımlılıkları ve paket bağlantılarını yükleyin:
   ```bash
   flutter pub get