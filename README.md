# Rift Arena

Mobil ve masaüstü tarayıcılar için tek koridorlu, botlara karşı MOBA prototipi. Bağımlılık ve kurulum gerektirmez. index.html dosyasını tarayıcıda açın.

## Kontroller
- Masaüstü: WASD / yön tuşlarıyla hareket, boşlukla saldırı; Q: şimşek, Shift: atılma, E: nova.
- Mobil: sol joystick ve sağ saldırı/yetenek düğmeleri. Yatay ekran önerilir.
- Önce rakip kuleyi, ardından çekirdeği yok edin. Minyonlar 12 saniyede bir doğar. Üssün yakınında can yenilenir. Altınla saldırı ve can yükseltilebilir.
- Duraklatma sağ üsttedir. Sekmeden ayrılınca oyun duraklar.

## GitHub Pages
1. Yeni, herkese açık bir GitHub deposu oluşturun: rift-arena.
2. index.html, style.css, game.js ve .nojekyll dosyalarını deponun köküne yükleyin.
3. Settings → Pages → Build and deployment → Deploy from a branch seçin.
4. Branch: main; klasör: / (root); Save.
5. GitHub Pages ekranında yayın tamamlandığında verilen bağlantıyı açın. Aynı bağlantı telefonda da çalışır.

Çok oyunculu sunucu, hesap sistemi ve kalıcı kayıt henüz yok. Her cihaz kendi bot maçını çalıştırır. Görseller kodla çizilmiştir; harici oyun varlığı kullanılmaz.

## Doğrulama
JavaScript sözdizimi ve simüle edilmiş DOM/canvas ortamında minyon dalgası, yetenek hasarı ve enerji tüketimi, bekleme süresi, güçlendirme, çekirdek kalkanı, zafer, yeniden başlatma ve 60 saniyelik simülasyon kontrol edildi. Gerçek tarayıcı ve fiziksel telefon testi henüz yapılmadı.
