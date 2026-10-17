# Değişiklik Günlüğü

Tüm önemli değişiklikler bu dosyada listelenir.

## [1.0.1] — 2026-10-17

### Düzeltilenler

- Kök dizindeki yönlendirme `.htaccess` dosyası, belge kökü `public/` olan bazı sunucularda (ör. Hestia) 500 hatasına yol açıyordu. Dosya artık isteğe bağlı `htaccess-kok-ornek.txt` olarak geliyor.

## [1.0.0] — 2026-10-17

İlk sürüm.

### Eklenenler

- Tek sayfa kişisel portfolyo teması: giriş (hero), yetenekler, hakkımda, projeler, hizmetler, referanslar, kayan yazı, fiyatlandırma, markalar, blog ve iletişim bölümleri
- Açık / koyu görünüm, renk özelleştirme, açılış animasyonu ve kaydırma animasyonları
- **Canlı önizlemeli tema düzenleyici:** tüm metinler, görseller, bağlantılar, renkler ve listeler; masaüstü / tablet / mobil önizleme; önizlemede tıkla-düzenle; taslak & yayınla akışı; tema dışa / içe aktarma
- Proje yönetimi (kategoriler, filtreleme, detay penceresi, ızgara boyutu)
- Blog (Markdown içerik, kategoriler, arama, zamanlanmış yayın)
- İletişim formu, gelen kutusu ve e-posta bildirimi
- Medya kütüphanesi ve görsel yükleme
- Web tabanlı kurulum sihirbazı ve `php artisan portfolyo:kur` komutu
