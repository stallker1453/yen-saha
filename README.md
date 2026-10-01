# Halı Saha Grubu — Online MVP

## Özellikler
- Telefon uyumlu web uygulaması
- Haftalık maç kaydı
- Oyuncuların Geliyorum / Gelemiyorum bildirimi
- ⚪ Beyaz / ⚫ Siyah takım tercihi
- Otomatik 14 kişilik kadro
- Fazla gelenlerin yedek sırası
- Gelmeyenlerin yerine yedeklerin otomatik alınması
- Katılım geçmişine göre yedek/kadro önceliğini dengeleyen temel rotasyon
- Yönetici anahtarı ile oyuncu ekleme

## Çalıştırma
Node.js 18+ gerekir.

```bash
npm install
ADMIN_KEY="guclu-bir-sifre" npm start
```

Sonra tarayıcıdan `http://localhost:3000` açılır.

## İnternete yayınlama
Node.js destekleyen bir hosting servisine yüklenebilir. Ortam değişkenleri:
- `ADMIN_KEY`: yönetici şifresi
- `DB_PATH`: kalıcı SQLite dosya yolu (hosting'in kalıcı disk yoluna ayarlanmalı)

## Sonraki geliştirmeler
- SMS/WhatsApp davet linki
- Oyuncuya özel giriş
- Yönetici paneli
- Haftayı tek tuşla kopyalama
- Maç sonucu ve skor
- Oyuncu istatistikleri
- PWA / ana ekrana uygulama olarak ekleme
