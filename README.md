Özellikler
Film Ekleme: Kullanıcı, sistemde film adı, süresi ve türünü belirterek yeni filmler ekleyebilir.
Salon Ekleme: Kullanıcı, mevcut filmlerden birini seçerek bir salon oluşturabilir ve filme bağlayabilir.
Müşteri Ekleme: Yeni müşteriler kaydedilip, belirli bir salona atanabilir.
Salon Bilgilerini Görüntüleme: Kullanıcı, salon bilgilerini (film ve müşteri listesi) detaylı olarak görebilir.
Kodun Yapısı
1. Temel Sınıflar
BaseEntity: Ortak özelliklere (ID, isim) ve bir bilgiGoster metoduna sahip soyut bir sınıftır.
Musteri: BaseEntity sınıfından türetilmiştir ve müşteri bilgilerini içerir.
Film: Film adı, süresi ve türü gibi bilgileri tutar ve bu bilgileri gösteren bir metoda sahiptir.
2. Salon Sınıfı
Salon:
Bir filmi temsil eder ve müşterileri liste halinde saklar.
BaseEntity sınıfından türemiş ve IKayit arayüzünü uygulamıştır.
Müşteri ekleme ve salon bilgilerini gösterme işlemleri için gerekli metodlara sahiptir.
3. Arayüz
IKayit:
musteriEkle ve bilgiGoster metodlarını tanımlayan bir arayüzdür.
4. Ana Program
SinemaSistemi:
Kullanıcıdan giriş alarak sistemin tüm işlevlerini çalıştırır.
Menü tabanlı bir yapı kullanılarak kullanıcı dostu bir arayüz sağlar.
