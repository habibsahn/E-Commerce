# E-Commerce

Bu proje, modern bir e-ticaret arayüzü için hazırlanmış statik bir web sitesidir. Ana sayfa, ürün detay sayfası ve alışveriş sepeti sayfası gibi temel e-ticaret bileşenlerini içerir.

## Proje Özeti

- Bootstrap tabanlı responsive tasarım
- Ürün kartları ve indirim etiketleri
- Kategori menüsü ve slider arayüzü
- Ürün detay görünümü ve görsel galeri
- Sepet özeti ve ürün miktarı seçimi
- Mobil uyumlu düzen

## Kullanılan Teknolojiler

- HTML5
- CSS3
- Bootstrap 5
- Font Awesome
- Vanilla JavaScript
- Fancybox benzeri lightbox örneği (`js/fslightbox.js`)

## Proje Yapısı

```text
E-Commerce/
├── index.html              # Ana sayfa
├── details.html            # Ürün detay sayfası
├── shopping-cart.html      # Sepet sayfası
├── css/
│   └── styles.css         # Özel stil dosyası
├── img/                    # Görseller ve slider görselleri
├── js/
│   └── fslightbox.js      # Görsel galeri lightbox betiği
└── README.md              # Proje dokümantasyonu
```

## Özellikler

### Ana Sayfa
- Üst menü ve arama alanı
- Kategori navigasyonu
- Ürün promosyon slider'ı
- Son eklenen ürünlerin listelendiği ürün kartları
- İndirimli fiyat gösterimi

### Ürün Detay Sayfası
- Büyük görsel ve thumbnail galerisi
- Ürün başlığı, fiyat ve açıklama
- Puanlama alanı
- Renk ve boyut seçenekleri
- Sepete ekleme butonları

### Sepet Sayfası
- Ürün listesi ve adet seçimi
- Ürün silme işlemi
- Sipariş özeti
- Kargo ve vergi bilgisi

## Çalıştırma

Bu proje dinamik bir arka uç sunmadığı için statik bir web sunucusu ile açılmalıdır. Aşağıdaki adımları izleyerek projeyi yerelde çalıştırabilirsiniz:

1. Proje klasörüne geçin:

```bash
cd "/home/habibsahn/Masaüstü/Sites/E-Commerce"
```

2. Yerel sunucu başlatın:

```bash
python3 -m http.server 8000
```

3. Tarayıcıda şu adresi açın:

```text
http://localhost:8000
```

> Not: Dosyaları doğrudan tarayıcıdan açmak bazı görsel ve yol sorunlarına neden olabilir. Bu nedenle yerel sunucu kullanılması önerilir.

## Özelleştirme

- Stil düzenlemeleri için: `css/styles.css`
- Görseller için: `img/` klasörü
- Yeni ürünler ve içerik eklemek için HTML sayfalarını güncelleyin
- Ürün görselleri ve fiyat bilgilerini mevcut kart yapısına uygun şekilde düzenleyin

## Notlar

Bu proje tamamen ön yüz (frontend) odaklıdır. Ürün ekleme, kullanıcı girişi, ödeme ve veritabanı işlemleri gibi arka plan işlevleri içermez.

## Lisans

Bu proje özel kullanım için hazırlanmıştır. Kullanım ve dağıtım için uygun izinleri kontrol edin.
