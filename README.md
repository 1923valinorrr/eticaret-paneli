# Mağaza Paneli

Tek dosyalık, tam donanımlı e-ticaret yönetim paneli. Sunucu gerektirmez; veriler tarayıcıda (`localStorage`) tutulur.

## Özellikler
- **Özet:** ciro, ortalama sepet, son 7 gün grafiği, çok satanlar, stok uyarıları
- **Ürünler:** ekle/düzenle/sil, SKU ve kategori, arama ve filtre
- **Siparişler:** çok kalemli sipariş, kupon, durum takibi, stok otomatik düşer/iade edilir, yazdırılabilir fatura, CSV dışa aktarma
- **Müşteriler:** kayıt, sipariş sayısı ve toplam harcama
- **Kuponlar:** yüzde indirim kodları
- **Ayarlar:** mağaza adı, stok eşiği, JSON yedek alma/yükleme, sıfırlama
- **Kişiselleştirme:** mağaza adı, logo, ana renk, para birimi, fatura notu (Ayarlar sayfasından)
- Açık/koyu tema, mobil uyumlu

## Kendine göre özelleştir
- **`config.js`** dosyasını düzenle: mağaza adı, logo, renk, para birimi, stok eşiği, fatura notu. Panel varsayılan olarak boş başlar; örnek veri görmek istersen `demoVeri: true` yap.
- Panel açıldıktan sonra **Ayarlar** sayfasından da aynıları değiştirilebilir (tarayıcıya kaydedilir).
- Daha fazlası için `index.html` tek dosyadır; istediğin gibi düzenleyebilirsin.

## GitHub Pages ile yayınlama
1. Yeni bir repo oluştur ve `index.html` ile `README.md` dosyalarını yükle.
2. Settings → Pages → Branch: `main` / `(root)` → Save.
3. Birkaç dakika sonra `https://kullaniciadi.github.io/repo-adi/` adresinde açılır.

## Not
Veriler sadece o tarayıcıda saklanır. Gerçek bir mağaza için bir backend (Supabase, Firebase vb.) eklemek gerekir.
