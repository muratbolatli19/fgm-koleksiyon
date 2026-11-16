# FGM Koleksiyon — Redesign V2

Bu dal canlı `main` dalından ayrıdır. Referans: 14 Kasım 2026 tarihinde sağlanan mobil mağaza ekranı.

## Görsel hedef
- Krem zemin, şampanya-altın aksanlar, koyu kahverengi metin.
- Ortada büyük çiçek çelenkli FGM logosu; hamburger, arama, sepet ve yönetici kontrolleri.
- Sol metin/sağ hediye kompozisyonlu kayan hero, mobilde referans oranlarına uyum.
- Görsel kategori şeridi, filtreleme, iki sütunlu ürün kartları, galeri, favoriler.
- Instagram ve WhatsApp çağrıları, çiçekli altbilgi.

## Uygulama sınırları
- Mevcut index.html içindeki üst üste CSS katmanları yeni tasarıma taşınmayacak.
- Ürün ve görseller mevcut kaynaklarla karşılaştırılmadan silinmeyecek.
- Admin kimlik doğrulaması ve veri erişimi sunucu tarafı kurallarla korunacak; servis anahtarları istemciye yazılmayacak.
- WhatsApp mesajı ürün adı, adet, bağlantı ve açıklama içerir; fotoğraf eki otomatik gönderimi garanti edilmez.
- Testler ve onay olmadan main'e merge yapılmayacak.

## Doğrulama
- iPhone Safari, Android Chrome, tablet ve masaüstü düzenleri.
- Kategori filtreleri, arama, favoriler, sepet miktarı ve WhatsApp mesajı.
- Yönetici giriş/çıkış, ürün CRUD, çoklu fotoğraf ve kalıcı veri erişimi.
- Görsel referans karşılaştırması, PWA ve önbellek sürümleme.
