# Kampüs Etkinlikleri - Sprint 3

Sprint 3, JavaScript modülleri ve DOM ile etkinlik listesini `data.js` verisinden üretir. Veriler bu sprintte kalıcı olarak saklanmaz.

## Sayfalar

- `index.html` - Yaklaşan iki etkinlik
- `etkinlikler.html` - Arama, kategori filtresi ve altı etkinliğin listesi
- `etkinlik-detay.html?id=event-3` - Seçilen etkinliğin ayrıntıları
- `etkinlik-ekle.html` - Doğrulamalı etkinlik ekleme formu
- `etkinlik-guncelle.html?id=event-3` - Seçilen etkinliği güncelleme formu

## JavaScript modülleri

- `js/data.js` - Altı örnek etkinliğin ortak veri kaynağı
- `js/event-list.js` - Ana sayfa kartları, arama ve kategori filtresi
- `js/event-detail.js` - URL'deki `id` ile detay gösterimi
- `js/event-form.js` - Form doğrulaması ve başarı/hata mesajları
- `css/2416501043.css` - Responsive sayfa ve form stilleri

`file://` yerine Live Server veya Vercel gibi bir HTTP sunucusu kullanın; ES modülleri HTTP üzerinden yüklenmelidir.
