# Hata raporu dokümente edilmiş

## Hataraporu tarih:07.07.2025

## Hata Bildirimi: Satış Eklenemiyor & Hizmet Listede Görünmüyor

### &#x20;Durum

Uygulamada aşağıdaki iki temel sorunu yaşıyorum:

1. Satış ekleme işlemi başarısız oluyor.
2. Yeni eklediğim hizmet, "Hizmetlerim" listesinde görünmüyor.

***

### &#x20;1. Satış Eklenemiyor

#### &#x20;Beklenen Davranış

Satış formu eksiksiz doldurulup "Satış Oluştur" butonuna basıldığında satışın veritabanına kaydedilmesi ve başarılı mesajı gösterilmesi gerekir.

#### &#x20;Gerçekleşen Durum

* "Satış Oluştur" butonuna basınca sistem yanıt vermiyor veya aşağıdaki genel hata mesajı gösteriliyor:

> Başarısız!\
> Üzgünüz, verilerinizi kaydederken bir hata oluştu.

* Satış kaydı gerçekleşmiyor ve listeye yansımıyor.

***

### &#x20;2. Hizmet Ekleniyor Ama Listede Görünmüyor

#### &#x20;Beklenen Davranış

Yeni eklenen hizmetin başarıyla kaydedilip "Hizmetlerim" listesine otomatik olarak eklenmesi gerekir.

#### &#x20;Gerçekleşen Durum

* Hizmeti ekledikten sonra başarı mesajı görünse de, eklenen hizmet "Hizmetlerim" listesinde yer almıyor.
* Sayfa yenilense de listeye yansımıyor.

***

### Denediğim Adımlar

* Sayfayı yenileyip tekrar denedim.
* Farklı tarayıcılarda test ettim (Chrome, Edge).
* Tarayıcı konsolunu kontrol ettim (JS hatası yok).
* Form alanlarını eksiksiz doldurdum.
* Oturumu kapatıp tekrar giriş yaptım.

***

Varsayımlar

* Satış ekleme işleminde backend tarafında bir doğrulama veya kayıt sorunu olabilir.
* Hizmet eklendikten sonra liste güncellenmiyor veya filtrelenmiş olabilir.
* Veritabanına veri gidiyor ancak UI tarafı güncellenmiyor olabilir.

***

> Bu iki sorun kullanıcı deneyimini doğrudan etkiliyor.  Yardımcı olabilirseniz memnun olurum&#x20;
