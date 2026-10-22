# COREX Sitesini GitHub Pages'te Yayınlama

Bu klasör doğrudan yayınlanabilir. Kurulum, Node.js veya başka bir araç gerektirmez.

1. GitHub'da yeni bir **public** repository oluştur. Önerilen isim: `corex-presentation`.
2. `COREX_GitHub_Website.zip` dosyasını bilgisayarda bir klasöre çıkart.
3. Zip'in **içindeki dosyaları** GitHub repository'nin ana dizinine yükle (ZIP'in kendisini tek başına yükleme):
   - `index.html`
   - `corex-demo.html`
   - `COREX_Presentation.pdf`
   - `assets` klasörünün tamamı
   - İstersen `README.md` ve bu dosya
4. Repository içinde **Settings → Pages** menüsüne git.
5. **Build and deployment → Deploy from a branch** seçeneğini aç.
6. Branch olarak **main**, klasör olarak **/(root)** seç ve kaydet.
7. GitHub Pages adresin şu formatta olur:
   `https://KULLANICI-ADIN.github.io/corex-presentation/`

## Sitenin içinde neler var?
- Ürün tanıtımına uygun açılış sayfası
- AbMaxx üst sıra / COREX alt sıra şeklinde karşılaştırma
- Geliştirdiğimiz özellikleri anlatan bölümler
- Tam **16 slaytlık** sunum: ileri-geri, tam ekran, küçük resim seçme, mobil kaydırma
- `Try COREX Live` butonu ile **çalışan COREX uygulama demosu**
- PDF indirme

**Önemli:** Sadece `index.html` dosyasını yükleyip `assets/` klasörünü yüklemezsen görseller görünmez. Bu nedenle ZIP'in tüm içeriğini yükle.
