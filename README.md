# 1. Hafta Ödevi

## PHP ile E-Ticaret Sistemi

PHP ve Veritabanı kullanarak, admin paneli olan ürünlerimizi satabildiğimiz bir e-ticaret platformu istiyoruz.

### Site Gereksinimleri
- Kategoriler ve ürünler listelenmeli
- Seçtiğimiz ürünleri öne çıkarabilmeliyiz
- Sepet sistemi olmalı
- Üye girişi ile satış yapılmalı
- Ürünlerde stok sistemi olmalı

### Admin Panel Gereksinimleri

- Admin paneline e-posta ve şifre ile giriş yapılmalı.
- Şifremi unuttum sayfası olmalı ve e-posta ile şifre sıfırlanabilmeli.
- Kategori yönetimi.
- Ürün yönetimi.
- Satış yönetimi.
- Üye yönetimi.
- Admin yönetimi.

### Kurallar

- Veritabanı bağlantısı için gerekli olan dosyanın adı **database.php** olmalı ve anadizine eklenmelidir.
- Türkçe karakter sorunu yaşanmamalıdır.
- Ürünlere ait url adresleri kategoriAdi/urunAdi-urunUniqueID şeklinde olmalıdır. Örneğin ayfon12 adlı telefon için (siteadi.com/telefonlar/ayfon-12-12312312) şeklinde olmalıdır.(
  .htaccess dosyası oluşturarak bunu sağlayabilirsiniz.)
- Url adres kuralına uymayan sayfalar için 404 hatası verilmelidir.  
- İlgili veritabanını **data** adında bir klasör oluşturup içine sql formatında yüklemelisiniz.
- Projelerinize ait bir döküman olmalıdır ve bu dökümanda,
  - Projenizin açıklaması ve fonksiyonları
  - Veritabanı tablo açıklaması
  - Kullandığınız teknolojiler (Frontend dahil)
  - Varsa analiz ettiğiniz diğer e-ticaret siteleri ve bu siteler ile sizin projeniz arasındaki farklar
  - Varsa projeye ek olarak eklemiş olduğunuz özellikler ve bilgiler

### İsteğe Bağlı Durumlar

- Admin panel ve site arayüzü için istediğiniz hazır HTML teması kullanabilirsiniz.
- HTML kodlarınızı Layout'lara bölerek kullanabilirsiniz.
- Proje üzerinde MVC yapısı kullanabilirsiniz.
- Bu istekler dışında kendinizin iyi olacağını düşündüğünüz durumlar ekleyebilirsiniz.
- Kodlar OOP ilkesine uygun şekilde yazılırsa iyi olur.
