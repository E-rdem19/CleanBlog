# CleanBlog

CleanBlog, minimal ve okunabilir bir blog şablonu/teması olacak şekilde tasarlanmış örnek bir proje şablonudur. Amacı temiz tipografi, basit yapı ve kolay özelleştirilebilirlik sunmaktır — statik HTML/CSS/JS tabanlı veya bir statik site jeneratörüyle (ör. Jekyll, Hugo) kullanılmak üzere kolayca uyarlanabilir.

Demo
- (İsteğe bağlı) Çalışan bir demo bağlantısı varsa buraya ekleyin: https://your-demo.example.com

Özellikler
- Minimal ve temiz tasarım
- Mobil uyumlu (responsive)
- Kolay özelleştirilebilir renk ve yazı tipleri
- Basit içerik yapısı — makaleler, kategori/etiket desteği (jeneratöre göre)
- Hızlı başlangıç için örnek içerik ve şablonlar

Hızlı Başlangıç

1. Depoyu klonlayın
```bash
git clone https://github.com/E-rdem19/CleanBlog.git
cd CleanBlog
```

2. Projeyi statik olarak kullanma
- Eğer proje tamamen statik HTML/CSS/JS ise index.html dosyasını tarayıcıda açarak çalıştırabilirsiniz.

3. Node tabanlı geliştirme (varsa)
- Eğer proje bir paket.json içeriyorsa:
```bash
npm install
npm run dev      # geliştirme sunucusu
npm run build    # üretim derlemesi
```

4. Jekyll/Hugo gibi bir jeneratörle (varsayılan değil — proje yapısına göre)
- Jekyll için:
```bash
bundle install
bundle exec jekyll serve
```
- Hugo için:
```bash
hugo server -D
```

Proje Yapısı (örnek)
- index.html / src/ : Ana sayfa ve şablonlar
- assets/css/ : Stil dosyaları
- assets/js/ : JavaScript dosyaları
- content/ veya _posts/ : Yazılar ve içerik (kullanılan jeneratöre göre değişir)
- images/ : Görseller

Özelleştirme
- Renkler: assets/css/ içindeki değişkenleri veya root CSS değişkenlerini düzenleyin.
- Yazı tipleri: head bölümünde veya CSS içinde font-family ayarlarını güncelleyin.
- Başlık ve meta: index.html veya şablon dosyalarından güncelleyin.

Geliştirme İpuçları
- Yeni bir makale eklerken içerik klasör yapısını takip edin (ör. content/ veya _posts/).
- Stilleri küçük değişikliklerle test etmek için tarayıcı geliştirici araçlarını kullanın.
- Değişiklikleri küçük commit'lerle yapın ve anlamlı commit mesajları kullanın.

Katkıda Bulunma
- Fork → feature branch → pull request akışını öneririz.
- Lütfen değişiklikleri küçük adımlarda, test edilebilir ve açıklayıcı commit mesajlarıyla gönderin.
- Bir hata bildirimi veya yeni özellik önerisi için Issues kullanın.

Lisans
- Bu depo için lisans dosyası (LICENSE) ekleyin. Önerilen: MIT lisansı. (Projeye uygun lisansı seçip LICENSE dosyası ekleyin.)

İletişim
- Sorular, öneriler veya iş birliği için: git kullanıcı adı veya e-posta bilgilerinizi buraya ekleyin.

Notlar
- Bu README genel bir şablondur. Depodaki gerçek yapı ve bağımlılıklara göre (ör. package.json, _config.yml, hugo config) bölümleri güncelleyin.
- İsterseniz ben README'yi repoya push edebilirim veya mevcut içeriklere göre README'yi otomatik uyarlayabilirim — hangi yolu tercih edersiniz?
