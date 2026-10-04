# 🐔 Var mı Bişey?

101 okey için yaz-boz uygulaması. Tek dosya (`index.html`), derleme gerektirmez.

## Vercel'e yayınlama
1. `index.html` ve `README.md` dosyalarını bir GitHub deposuna yükle.
2. vercel.com → **Add New → Project** → depoyu seç.
3. Framework: **Other**, build komutu ve output dizini boş kalsın → **Deploy**.

## Puan mantığı
El puanı = el içi ceza + elde kalan sayı − 100 (rekor açıldıysa). Normal/2X/3X/4X/5X seçimi puanı değiştirmez, sadece iddiayı gösterir.
Eli bitiren oyuncunun satırında tire (—) görünür. Her oyuncu oyun boyunca en fazla 2 rekor açabilir. 11 el sonunda en düşük toplam kazanır.
Oyun tarayıcıda saklanır, sayfa yenilense de kaybolmaz.

## Özellikler
- Geçmiş tablosunda ele dokunarak eski eli düzeltme
- Oyun sürerken ekran açık kalır (destekleyen tarayıcılarda)
- Ana ekrana eklenir, internetsiz çalışır (`manifest.webmanifest`, `sw.js`, ikonlar)
- Oyun sonunda WhatsApp'a sonuç paylaşma, istatistikler, konfeti
- Eli bitirirken uyarı, son oynayan isimler, dağıtıcı göstergesi (dokununca değişir)

Yayınlarken tüm dosyaları aynı klasörde (depo kökünde) tut: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`.
