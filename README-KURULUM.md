# OranjeKip CMS dönüşümü

Bu paket mevcut OranjeKip GitHub Pages sitesinin tasarımını koruyarak içerikleri yönetilebilir hale getirir.

## Önemli
`style.css` mevcut repository'de olduğu gibi bırakılmalıdır. Bu pakete yeniden kopyalanmadı.

## Repository'de değişecek yapı

index.html          -> BU PAKETTEKİ index.html ile değiştir
.pages.yml          -> YENİ
data/products.json  -> YENİ
data/locations.json -> YENİ
data/testimonials.json -> YENİ
data/site.json      -> YENİ

images/             -> mevcut klasör; yeni ürün fotoğrafları buraya yüklenir
docs/               -> mevcut PDF klasörü

## Nohutlu Pilav
Ürün örneği hazır olarak eklenmiştir:
- Ad: Nohutlu Pilav
- Fiyat: €5
- Görsel: /images/Nohutlu Pilav.png

Bu dosyanın gerçekten repository'deki `images` klasörüne yüklenmesi gerekir.

## Pages CMS
1. https://app.pagescms.org/ adresine GitHub ile giriş yap.
2. `oranjekip/oranjekip.github.io` repository'sini seç.
3. `.pages.yml` otomatik olarak yapılandırmayı tanır.
4. `Producten` bölümünden ürünleri düzenleyebilirsin.
5. `Locaties` bölümünden çalışma yerlerini düzenleyebilirsin.
6. `Website instellingen` bölümünden hero, menü görseli/PDF, hakkımızda ve sosyal medya bilgilerini düzenleyebilirsin.

GitHub Pages aynı repository'den yayınlanmaya devam eder.
