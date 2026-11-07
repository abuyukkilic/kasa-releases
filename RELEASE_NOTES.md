Kasa 0.1.10

- macOS yerel AI bağlantısında istemci isteği geciktiğinde oluşabilen bağlantı kopması giderildi.

- AI izin kapsamı ve süre tercihi her bilgisayarda, her kasa için bir kez kaydedilebilir.
- Kasa ana parolayla açıldığında kayıtlı izin doğrulanıp otomatik etkinleştirilir.
- Varsayılan erişim süresi süresizdir; süreli veya yalnız mevcut oturum için izin de seçilebilir.
- Kayıtlı izinler panelde otomatik doldurulur; ayrıntılı form yalnız gerektiğinde açılır.
- Bu bilgisayardaki izni kaldır seçeneği etkin erişimi kapatır ve yerel tercihi siler.
- Tercihler kasa/Git deposu dışında tutulur; ana parola ve oturum token'ı kaydedilmez.
- Kasa kilitliyken erişim kapalı kalır. Geçersiz tercihler kasa açılmasını engellemez, AI erişimini kapalı tutar.

Kasa biçimi ve mevcut parolalar değişmez. Windows yükleyicisi çevrimdışı önkoşulları içerir ve Tauri güncelleme anahtarıyla imzalanır; Windows Authenticode yayıncı imzası içermez.

Bu yayın macOS Apple Silicon içindir. Paket BEY Bilgisayar Developer ID ile imzalıdır ve Apple noter onayından geçmiştir. Windows için son paket 0.1.9 sürümüdür.

---

Kasa 0.1.9

- macOS Apple Silicon paketi BEY Bilgisayar Developer ID ile imzalanır ve Apple noter onayından geçirilir.
- Sol menüde proje araması; Ortak dahil tüm projelerde kayıt arama ve sonucu ilgili projede açma.
- Hesaplar sekmesi: giriş hesabı, web sitesi, sunucu ve veritabanı kayıtları.
- Kullanıcı adı, parola, web adresi, host, port ve özel not alanları.
- Parolayı göster/gizle; hassas pano temizliğiyle alan kopyalama.
- Kayıt düzenleme, silme, proje arasında kopyalama ve JSON dışa aktarma.
- Tüm projeler araması hesap metadatasını da tarar; parola ve özel notlar aramaya dahil edilmez.
- Terminalden account set/get/list ve remove/export/duplicate account desteği.

Mevcut kasalar açılır. İlk hesap kaydı eklenince kasa biçimi 2’ye yükselir; bu kasayı kullanan tüm cihazlar 0.1.9 veya üstü sürümde olmalıdır. Mevcut kasa parolası değişmez.

Bu yayındaki kurulum paketi macOS Apple Silicon (M serisi) içindir. Windows ve Linux 0.1.9 paketleri bu yayına dahil değildir.


---

# Kasa yayınları

Bu depo yalnızca kurulum paketlerini ve sürüm notlarını içerir.

Kasa 0.1.2

- Yeni sürümler açılışta ve 6 saatte bir kontrol edilir.
- Güncelleme bildirimi, sürüm notları, indirme ilerlemesi ve yeniden başlatma akışı eklendi.
- Güncellemeler imzayla doğrulanır; kurulum öncesinde kasa kilitlenir ve AI izinleri kapatılır.
- Boş, bulunamayan veya kasa içermeyen klasörler için anlaşılır Türkçe mesajlar eklendi.
- Biz kimiz ekranı ve görünür uygulama sürümü bulunur.

Bu yayın macOS Apple Silicon içindir. Windows ve Linux güncelleme paketleri henüz yayımlanmadı.
