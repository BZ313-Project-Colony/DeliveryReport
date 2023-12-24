## PROJE TESLİMAT RAPORU

**Proje Bilgileri:**
- **Proje Adı:** QR Pass
- **Başlangıç Tarihi:** 13 Kasım 2023
- **Bitiş Tarihi:** 25 Aralık 2023
- **Proje Ekibi:**
  - Ahmet Faruk Çuha
  - İrem Tapsız
  - Semih Çay
  - Mustafa Umut İdam
  - İsa Uçar
  - Elif İrem Keskin
  - Batuhan Erol
  - Sümeyye Korkmaz

Bu rapor, QR Pass projesinin her aşamasının detaylı incelenmesi ve başarıyla tamamlanarak müşteriye teslim edilmesini onaylar. Proje sürecinde karşılaşılan zorluklar, çözüm yolları ve elde edilen sonuçlar aşağıda ayrıntılı olarak ele alınmıştır.

---

**Agile Proje Yönetimi ve Proje Aşamaları:**

1. **Planlama:**
   - Proje hedefleri, beklentiler ve kapsam, müşteri geri bildirimleriyle sürekli güncellenecek şekilde netleştirildi.
   - Kaynak tahsisi, bütçe planlaması ve zaman çizelgesi, esneklik sağlayacak biçimde düzenlendi.
   - Risk analizi yapılarak olası sorunlar için sürekli adapte edilebilecek önlemler alındı.

2. **Analiz ve Tasarım:**
   - Kullanıcı ve sistem gereksinimleri, düzenli müşteri etkileşimleriyle sürekli olarak incelendi ve güncellendi.
   - Sistem mimarisi, teknolojik altyapı ve kullanılacak araçlar, sık sık tekrarlanan tasarım toplantıları sonucunda belirlendi.
   - Kullanıcı deneyimi (UX) tasarımı için sürekli geri bildirim alınarak ve prototipler oluşturularak şekillendirildi.

3. **Geliştirme:**
   - QR kod okuma ve doğrulama modülleri, kısa süreli geliştirme iterasyonları içinde oluşturulup entegre edildi.
   - Kullanıcı arayüzü ve kullanıcı deneyimi (UI/UX) tasarımları, müşteri geri bildirimlerine dayalı olarak hızlıca uygulandı.
   - Veritabanı tasarımı ve entegrasyonu, sürekli entegrasyon ve test süreçleri içinde tamamlandı.

4. **Test:**
   - Sistemin tüm modüllerinde sık sık tekrarlanan kapsamlı fonksiyonel testler yapıldı.
   - Kullanıcı kabul testleri (UAT), müşteri ile sürekli işbirliği içinde gerçek kullanıcı deneyimlerini değerlendirdi.
   - Performans, güvenlik ve yük testleri, geliştirme süreci boyunca düzenli olarak uygulandı.

5. **Uygulama ve Dağıtım:**
   - Sistem, pilot gruplarla düzenli geri bildirim alınarak ve sürekli iyileştirme prensipleri doğrultusunda test edildi.
   - Geri bildirimlere dayalı olarak sürekli iyileştirmeler yapılarak sistem, hızlı bir şekilde kullanıma hazır hale getirildi ve sürekli dağıtım süreci başlatıldı.

---

**Proje Sonuçları:**
- QR Pass, belirlenen hedeflere uygun olarak ve zaman çizelgesine sadık kalarak başarıyla tamamlandı.
- Kullanıcı deneyimi, sistem performansı ve güvenlik açısından yüksek standartlarda geri bildirimler alındı.
- Proje, müşterinin ihtiyaçlarını karşılayan yenilikçi ve verimli bir geçiş kontrol sistemi olarak değer kazandı.

---

**Öneriler ve İyileştirmeler:**
- Sürekli gelişim çerçevesinde, gelecekteki sürümler için kullanıcı geri bildirimleri esas alınarak iyileştirmeler yapılması.
- Güvenlik ve veri koruma politikalarının düzenli olarak gözden geçirilmesi.
- Sistem entegrasyonu ve kullanıcı deneyimi konularında sürekli iyileştirme ve yeniliklerin uygulanması.

---

## Kullanma Kılavuzu
### Admin Panel
**Kullanıcı adı** : `admin` <br>
**Şifre** : `12345678`
![login](./images/login.png)
![events](./images/events.png)
![create_event](./images/create_event.png)
![events_2](./images/events_2.png)
![event_detail](./images/event_detail.png)
### Etkinlik Kayıt Paneli
![register_event](./images/register_event.png)
### QR Okuyucu Mobil Uygulama
![mobil_login](./images/mobil_login.png)
![mobil_events](./images/mobil_events.png)
![mobil_event_detail](./images/mobil_event_detail.png)
![mobil_qr_scanner](./images/mobil_qr_scanner.png)

## Müşteriye Projenin Teslim Şekli

### Backend QRPass Service
- QRPass web servisi ve postgres veritabanı, yüksek erişilebilirlik ve güvenilirlik sunan Heroku platformu üzerinde çalışmaktadır. Müşterimizin mail adresi Heroku'ya "collaborator" olarak eklenmiştir. Böylece tam erişim sağlanmış ve sistem yönetimi müşteriye devredilmiştir. Kaynak kodlar ve detaylı dokümantasyon müşteriye elektronik ortamda teslim edilmiştir.

### Frontend Admin Panel - Event Registration Panel
- Projenin frontend bileşenleri, kullanıcı dostu ve interaktif bir arayüz sunan Firebase üzerinde barındırılmaktadır. Müşterimizin mail adresi Firebase'e "owner" olarak eklenmiş, böylece tam kontrol sağlanmıştır. Kaynak kodlar ve kullanım kılavuzları müşteriye sağlanmıştır.

### Mobile QR Scanner
- Mobil uygulama, hem Android hem de iOS platformlarında sorunsuz çalışacak şekilde optimize edilmiştir. Uygulamanın uygulama mağazalarına yüklenmesi müşterinin tercihine bırakılmıştır. Kaynak kodlar, kurulum ve yayınlama rehberleri müşteriye teslim edilmiştir.

---

## Yazılım Bakımı ve İleriye Dönük Süreçler

QR Pass projesinin teslimatının ardından, yazılımın sürdürülebilirliği ve gelecekteki gelişmeler için aşağıdaki stratejiler ve planlar önerilmektedir:

1. **Sürekli Bakım ve Destek:**
   - Proje ekibi, belirli bir süre boyunca yazılımın düzgün çalışmasını sağlamak için teknik destek sağlayacaktır. Bu destek, hata düzeltmeleri, sistem optimizasyonları ve acil durum müdahalelerini kapsar.
   - Müşteri, herhangi bir sorun veya ihtiyaç durumunda destek ekibi ile iletişime geçebilecek bir iletişim kanalına sahip olacaktır.

2. **Güncellemeler ve Yenilikler:**
   - Sistemin teknolojik gelişmelere uyum sağlaması ve güncel kalması için periyodik yazılım güncellemeleri planlanmaktadır.
   - Kullanıcı geri bildirimleri ve pazar trendleri doğrultusunda, yeni özelliklerin ve iyileştirmelerin eklenmesi sürekli olarak değerlendirilecektir.

3. **Uzun Vadeli Strateji ve Planlama:**
   - Yazılımın uzun vadeli başarısını sağlamak için stratejik planlama ve danışmanlık hizmetleri sunulacaktır. Bu, pazardaki değişikliklere ve teknolojik yeniliklere adaptasyonu içerir.
   - Düzenli performans analizleri ve raporlamalar, sistem verimliliğini ve kullanıcı memnuniyetini sürekli izleyerek iyileştirmelerin yapılmasını sağlayacaktır.

4. **Güvenlik ve Veri Koruma:**
   - Yazılım ve veritabanının güvenliğinin sürekli olarak sağlanması için güvenlik güncellemeleri ve düzenli güvenlik denetimleri planlanmaktadır.
   - Veri koruma standartlarına uyum, kişisel verilerin korunması ve siber güvenlik risklerinin azaltılması için sürekli gözden geçirme ve iyileştirmeler yapılacaktır.

Bu stratejiler ve planlar, QR Pass yazılımının uzun vadeli başarısını ve müşterinin yatırımının korunmasını hedeflemektedir. Proje ekibi, müşterinin beklentilerini karşılamak ve sürekli olarak değer katmak için bu süreçlerin yönetimine ve uygulanmasına hazırdır.










