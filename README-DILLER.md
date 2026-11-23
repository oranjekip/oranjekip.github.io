# OranjeKip çok dilli site

Varsayılan dil Hollandacadır. Sağ üstte NL, TR, EN ve AR seçilir. Seçim tarayıcıda saklanır.

Çeviriler `data/lang-tr.json`, `data/lang-en.json`, `data/lang-ar.json` içindedir. `dictionary` bölümünde anahtar Hollandaca kaynak metin, değer çevirisidir. CMS üzerinden Hollandaca kaynak metin değişirse yeni metin otomatik çevrilmez; ilgili dil dosyasında yeni kaynak metin anahtarı eklenmelidir.

Menü kartları, lokasyon günleri, müşteri yorumları, WhatsApp hazır mesajları, başlıklar, açıklamalar çevrilir. Ürün fiyatları ve lokasyon adresleri değiştirilmez. Tam menü PDF/görseli Hollandaca kalır; başka dilde PDF isteniyorsa ayrı sürümler gerekir.

Cloudflare Worker / OAuth ayarları değiştirilmemiştir.
