# 🔧 FNIRSI HS-01 Custom Firmware

**FNIRSI HS-01 lehimleme havyası** için geliştirilmiş, tarayıcı tabanlı ve açık kaynaklı bir firmware özelleştirme aracı.

Bu proje sayesinde havyanızın açılış logosunu kişiselleştirebilir ve **LiPo piller için düşük voltaj koruma özelliği** ekleyebilirsiniz.

> ⚠️ **Uyumluluk:** Bu araç yalnızca orijinal FNIRSI HS-01 **V0.3 firmware** sürümünü destekler. Diğer sürümler desteklenmez ve hata oluşturabilir.

## 🚀 Kurulum ve Kullanım Rehberi

### 1. Orijinal Firmware Dosyasını İndirin

[FNIRSI Resmî Firmware İndirme Sayfası](https://www.fnirsi.com/pages/manuals-firmwares) adresini ziyaret edin.

**HS-01** modeli için aşağıdaki dosyaları indirin:

- Orijinal V0.3 firmware (`.s19`)
- Resmî Firmware Update Tool (yazılım güncelleme aracı)

### 2. Özelleştirme Aracını İndirin

Bu GitHub deposundaki `index_V2.html` dosyasını indirin.

Dosyayı istediğiniz internet tarayıcısında açın. Herhangi bir ek kurulum yapmanız gerekmez.

### 3. Orijinal Firmware Dosyasını Yükleyin

İndirdiğiniz orijinal **V0.3 firmware** dosyasını web arayüzüne yükleyin.

**Önemli:** Yalnızca V0.3 sürümü desteklenmektedir. Diğer sürümler hata verecektir.

### 4. Firmware'i Özelleştirin 🎨

Mevcut seçenekleri kullanarak havyanızı kişiselleştirin:

- **Özel Metin:** Açılış ekranında kendi metninizi görüntüleyin.
- **Özel Logo:** JPEG formatında bir görsel yükleyerek açılış logosunu değiştirin.
- **Orijinal Logo:** Fabrika çıkışındaki açılış logosunu değiştirmeden kullanın.
- **LiPo Koruması:** Mevcut düşük voltaj kesme seçeneklerini yapılandırın.

### 5. Yamalanmış Firmware Dosyasını Oluşturun

Özelleştirme işlemlerini tamamladıktan sonra:

1. Firmware oluşturma butonuna tıklayın.
2. Oluşturulan yamalanmış `.s19` dosyasını indirin.
3. Dosyayı bilgisayarınızda kolayca erişebileceğiniz bir konuma kaydedin.

### 6. Bootloader Moduna Girin

1. Havyanın bilgisayarla bağlantısını kesin.
2. Havyanın **sol ok (◀)** tuşuna basılı tutun.
3. Tuşa basmaya devam ederken havyayı bir USB veri kablosuyla bilgisayara bağlayın.
4. Ekranda **Bootloader** yazısı görünmelidir.

Cihazınız artık firmware yüklemeye hazırdır.

### 7. Özelleştirilmiş Firmware'i Yükleyin

1. FNIRSI'nin resmî **Firmware Update Tool** uygulamasını açın.
2. Uygun cihazı/COM portunu seçin.
3. Oluşturduğunuz yamalanmış `.s19` dosyasını yükleyin.
4. Firmware güncellemesini başlatın.
5. İşlem başarıyla tamamlanana kadar bekleyin.

**⚠️ Firmware güncellemesi sırasında USB kablosunu çıkarmayın.**

### 8. Özelleştirilmiş Havyanız Hazır! 🎉

FNIRSI HS-01 havyanızı yeniden başlatın ve kişiselleştirilmiş açılış ekranınızın ve eklediğiniz özelliklerin keyfini çıkarın!

---

## ↩️ Orijinal Firmware'e Geri Dönüş

Havyanızı tekrar fabrika yazılımıyla kullanmak mı istiyorsunuz?

Cihazınız Bootloader moduna girebildiği sürece orijinal firmware'i yeniden yükleyebilirsiniz.

1. Orijinal **HS-01 V0.3 firmware** dosyasını indirin.
2. Havyayı **Bootloader modunda** başlatın.
3. FNIRSI'nin resmî Firmware Update Tool uygulamasını açın.
4. Orijinal firmware dosyasını cihaza yükleyin.

Bu işlemle havyanızın yazılımını üreticinin orijinal sürümüne geri döndürebilirsiniz.

## ⚠️ Önemli Bilgiler ve Sorumluluk Reddi

- **Orijinal firmware bu projeye dahil değildir.** Üreticinin fikrî mülkiyet haklarına saygı göstermek amacıyla orijinal firmware dosyaları, tescilli kaynak kodlar veya üreticiye ait özel yazılım detayları paylaşılmaz.
- Kullanıcıların orijinal V0.3 firmware dosyasını kendilerinin yasal yollarla edinmeleri gerekir.
- Bu proje bağımsız olarak geliştirilmiştir. **FNIRSI ile resmî bir bağlantısı bulunmamaktadır ve FNIRSI tarafından desteklenmemektedir.**
- Firmware değişiklikleri kullanıcının kendi sorumluluğundadır. Hatalı yükleme işlemleri cihazın çalışmamasına neden olabilir.
- LiPo düşük voltaj kesme özelliği ek bir koruma mekanizmasıdır. **Özel bir batarya yönetim veya koruma devresinin (BMS) yerini tutmaz.**

---

## ❤️ Projeye Destek Olun

Bu projeyi faydalı bulduysanız GitHub deposuna bir ⭐ **yıldız vererek** destek olabilirsiniz!

Desteğiniz, projenin geliştirilmesine ve yeni özellikler eklenmesine katkı sağlar.

**73 de TA2IWO**
