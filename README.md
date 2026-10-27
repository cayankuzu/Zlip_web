# Zlip — web sitesi

Galaxy Z Flip kapak ekranı uygulaması **Zlip**'in tanıtım sitesi ve gizlilik politikası.

- Canlı: https://zlip-web.vercel.app
- Gizlilik politikası: https://zlip-web.vercel.app/gizlilik (`/privacy` da buraya yönlenir)

## Yapı

Derleme adımı olmayan statik bir site:

- `index.html` — tanıtım sayfası
- `gizlilik.html` — gizlilik politikası (Türkçe ve İngilizce)
- `404.html` — bulunamadı sayfası
- `styles.css` — tüm stiller (koyu tema, uygulamanın renkleri)
- `assets/` — ikonlar, paylaşım görseli ve uygulama ekran görüntüleri
- `vercel.json` — temiz adresler, yönlendirme ve önbellek başlıkları

## Yerelde açmak

```bash
python -m http.server 8080
```

Sonra http://localhost:8080 adresini aç.

## Yayın

Vercel'de statik proje olarak yayınlanır: `npx vercel --prod`.

© 2026 MeMoDe
