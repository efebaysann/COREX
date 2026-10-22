# COREX — Mobil Site Düzeltmesi

Bu sürümde mobil telefonlardan dokunmatik kullanım iyileştirildi.

## Düzeltilenler
- "Try the live app / Try COREX live" bağlantıları, mobil cihazlarda `corex-demo.html` dosyasına **aynı sekmede** gider. Bu, iç içe iframe kullanımından kaynaklanabilecek iPhone Safari / uygulama içi tarayıcı dokunma ve kaydırma sorunlarını önler.
- Masaüstünde canlı demo eski biçimde açılır pencere içinde çalışır.
- Mobilde üstteki Try the live app düğmesi artık gizlenmez; hamburger menü de kullanılabilir.
- Menü açma/kapatma, slayt ileri/geri, tüm slaytlar, tam ekran alternatifi ve paylaşım işlemleri iyileştirildi.
- Mobil dokunma alanları büyütüldü; slayt küçük görselleri seçildiğinde sayfanın beklenmedik şekilde kayması azaltıldı.
- Tek dosyalık HTML kullanıldığında mobil demoyu ayrı bir sayfa olarak göstermek için gömülü içerikten tarayıcı içerisinde geçici bir sayfa oluşturulur. Böylece `corex-demo.html` dosyası gerekmez.

## GitHub Pages'e yükleme
1. ZIP'i aç.
2. İçindeki `index.html`, `corex-demo.html`, `assets/` ve diğer dosyaları kendi GitHub Pages repository'sinin **kök dizinine** ekle. ZIP dosyasını olduğu gibi tek dosya olarak yükleme.
3. Önceki aynı isimli dosyaları değiştir. Özellikle `index.html` ve `corex-demo.html` güncellenmeli.
4. GitHub Pages ayarı `Settings → Pages → Deploy from a branch → main → /(root)` olsun.
5. Değişiklik görünmezse siteyi gizli sekmede aç; gerekirse Safari'de sayfayı yenile. GitHub Pages önbelleği nedeniyle eski sürüm kısa süre görünebilir.

## Test ve sınırlama
Mobil Chromium dokunmatik emülasyonunda 360, 375, 390, 430 ve 760 px ekranlarda menü, slayt geçişleri, fullscreen ve mobil demo yönlendirmesi doğrulandı. COREX demo akışı da 375 ve 390 px genişliklerde baştan sona test edildi. Gerçek iPhone Safari cihaz testi yapılmadı.
