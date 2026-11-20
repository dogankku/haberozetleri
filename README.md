# HaberAkışı

Türkiye ve dünyadan ~30 haber kaynağının RSS akışlarını tek sayfada toplayan, sunucu gerektirmeyen haber özeti sitesi.

## Özellikler
- **30 kaynak, 7 kategori:** Gündem, Dünya, Ekonomi, Spor, Teknoloji, Sağlık & Bilim, Kültür-Sanat. Genel akışlardaki haberler adres ve anahtar kelimeye göre otomatik sınıflandırılır.
- **Manşet düzeni** ve kayan **son dakika** şeridi
- **Haber detay paneli:** geniş özet, okuma süresi, paylaşma, ilgili haberler
- **Mükerrer haber ayıklama:** aynı haber birden çok kaynakta geçiyorsa tek kartta "+N kaynak" olarak gösterilir; "Öne Çıkanlar" bu bilgiye göre sıralanır
- **Gündemdeki kelimeler:** son 24 saatin başlıklarından çıkarılan konu listesi
- **Döviz (USD, EUR, GBP, BTC)** ve **şehir seçmeli hava durumu**
- Arama, zaman filtresi, kaynak seçimi, kart/liste görünümü, açık/koyu tema
- Kaydedilenler ve okunanlar tarayıcıda saklanır; önbellek sayesinde anında açılır, 10 dakikada bir arka planda yenilenir
- Kısayollar: `/` ara · `R` yenile · `Esc` kapat

## Kullanım
`index.html` dosyasını tarayıcıda açmanız ya da GitHub Pages ile yayınlamanız yeterli. Akışlar herkese açık CORS vekilleri (allorigins, corsproxy.io, codetabs, rss2json) üzerinden çekilir; reklam engelleyiciler bu istekleri engelleyebilir.

Kaynak eklemek için `index.html` içindeki `SOURCES` listesine yeni bir satır ekleyin.
