# Mini Katalog Uygulaması

Bu proje, temel seviyede bir mobil e-ticaret katalog uygulaması taslağıdır. Widget yapısı, named routes ile sayfa geçişleri, model sınıfı oluşturma ve `fromJson` ile dinamik JSON listeleme mantığını içerir.

## Özellikler

* **Discover (Keşfet) Ekranı:** Kart tabanlı ızgara yerleşimi için `GridView.builder` kullanan dinamik bir ürün arayüzü ve üst kısımda bir kampanya banner alanı sunar.
* **Ürün Detay Ekranı:** Sayfalar arasında ürün verilerini taşımak için `Route Arguments` mekanizmasını kullanır. Ürün görselini, açıklamasını ve teknik özelliklerini dinamik olarak ekrana basar.
* **Sepet Simülasyon Sistemi:** Ürün eklendiğinde arayüzdeki sepet sayısını dinamik olarak güncelleyen ve sipariş tamamlama (`Checkout`) akışını simüle eden bir yerel state yönetimi içerir.

## Veri Kaynakları

* **Kampanya Banner Linki:** `https://wantapi.com/assets/banner.png`
* **Örnek Ürün Veri Yapısı:** `https://wantapi.com/products.php`

## Kullanılan Teknolojiler
- **Framework:** Flutter SDK 
- **Dil:** Dart SDK 
- **Geliştirme Ortamı (IDE):** Visual Studio Code
- **Çalışma Platformu:** Web (Google Chrome)

## Çalıştırma Adımları

1. Bağımlılıkları ve paket bağlantılarını yükleyin:
   ```bash
   flutter pub get

2. Uygulamayı Chrome tarayıcısı üzerinde başlatın:
    ```bash
    flutter run -d chrome

3. Tarayıcı açıldığında mobil görünüm için F12 tuşuna basıp Cihaz Modu (Device Toolbar) ikonuna tıklayın.
    
