# Weather Plus #

* Yazar: Adriano Barbieri
* NVDA 2017.3 veya sonraki bir sürümü gerektirir.
* [kararlı sürümü][1] indir.

# WEATHER PLUS HAKKINDA: #

* Bu eklenti, NVDA'ya 2 güne kadar saatlik yerel hava durumu bilgisini
  ekler.
* Telif Hakkı [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* GNU GPL (Genel Kamu Lisansı) v2 olarak yayınlanmıştır
* Weather Plus, hava durumu bilgisini aşağıdaki hizmetlerden alır:
* [https://www.weatherapi.com/](https://www.weatherapi.com/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# KULLANIM: #

* Mevcut sıcaklık ve hava durumu bilgisini öğrenmek için NVDA+w tuşlarına
  basın.
* 24 saatlik ve iki güne kadar hava durumu bilgisini öğrenmek için
  NVDA+shift+W tuşlarına basın.
* Saatlik sıcaklık ve atmosfer koşulları tahminlerini öğrenmek için
  NVDA+shift+W tuşlarına iki kez basın.
* Geçici bir şehir ayarlamak için NVDA+shift+control+w tuşlarına basın.
* Weather Plus ayarları iletişim kutusunu açmak için
  NVDA+shift+control+alt+w tuşlarına basın.
* Hava durumu raporunun güncellendiği tarih ve saati öğrenmek için
  NVDA+alt+w tuşlarına basın.
* Fahrenheit, Celsius veya Kelvin sıcaklık ölçekleri arasında geçiş yapmak
  için control+shift+w tuşlarına basın.

# Weather Plus kurulumu: #

Weather Plus'u kullanmadan önce eklentiyi ayarlamanız gerekir. 
Tercihler alt menüsündeki Weather Plus Ayarları alt menüsüne gidin ve  aşağıdaki seçeneklerden birini seçin:
 * Şehirlerinizi Ayarlayın / Yönetin... - Mevcut şehri görüntüler veya ayarlamanızı sağlar.
 * Geçici bir şehir belirleyin... - Varsa, listeden bir geçici şehri görüntüler ve ayarlamanızı sağlar. 
 * Dokümantasyon - Geçerli dil için yardım dosyasını açar. 
 * Güncelleme için Kontrol Et... - Yeni sürümün kullanılabilirliği hakkında bilgi verir. 

Yeni bir şehir eklemek için: aşağıdaki öğeye basın:

* Şehirlerinizi Ayarlayın / Yönetin... - Mevcut şehri görüntüler veya
  ayarlamanızı sağlar.
* Bu iletişim kutusunu ilk açışınızda aşağıdaki mesaj görüntülenir: F1:
  yardımı göster, F2: son SEKME seçimi, F3: liste and düzenleme kutusu, F4:
  Hava Tahmini süre kontrolü.
* Yazı alanına bir Şehir girin veya varsa listeden birini seçin. Not: Ses
  efektleri etkinleştirilirse F5 tuşu kullanılabilir.
* "Şehirlerinizi Ayarlayın / Yönetin..." seçeneğini etkinleştirdiğinizde,
  aşağıdaki diğer düğmeler görüntülenir:
* Sına - Şehrin geçerliliğini test eder  ve verilerini buler.
* Ekle - Bulunduğunuz şehri listenize ekler. Girilen şehir doğruysa, bu
  düğme etkinleştirilebilir.
* Ayrıntılar - Bulunduğunuz şehirle ilgili bilgileri görüntüler. Bu düğme,
  listeden bir şehir seçerseniz veya testi geçtiyse etkinleştirilir.
* Tanımla - Ses efektlerini uyarlamak için alanı tanımlamanızı sağlar. Bu
  düğme, ses efektleri yüklenip etkinleştirilirse ve listeden bir şehir
  seçerseniz etkinleştirilebilir.
* Ön Ayar - Bir şehri varsayılan olarak önceden ayarlar, eklentiyi her
  yeniden başlattığınızda kullanılacaktır. Bu düğme, listeye önceden
  eklenmiş ve önceden ayarlanmamış bir şehri seçerseniz veya sınamayı
  geçmişse etkinleştirilir.
* Kaldır - Bulunduğunuz şehri listenizden siler. Bu düğme, daha önce listeye
  eklenmiş bir şehri seçerseniz etkinleştirilebilir.
* Yeniden Adlandır - Mevcut şehri yeniden adlandırır. Bu düğme, daha önce
  listeye eklenmiş bir şehri seçerseniz etkinleştirilebilir.
* Yeni şehirleri içe aktar... - Bu düğme, *.zipcodes; İçe aktarmak
  istediğiniz şehri, onunla ilişkili onay kutusunu açarak seçebilirsiniz.
* Şehirleri dışa aktar... - Şehirleri *.zipcodes uzantısıyla belirtilen
  dosyaya kaydetmenizi sağlar. Listeye en az bir şehir eklediyseniz ve
  kaydettiyseniz bu düğme etkinleştirilebilir.
* saatlik hava tahmin ayarı... - Bu düğme, saatlik tahmin raporunun
  içeriğini seçmenizi sağlar.
* Sıcaklık ölçümü ölçeği: Celsius (varsayılan olarak), Fahrenheit ve Kelvin
  arasında seçim yapmak için radyo düğmesini kullanın.
* Dereceler şu şekilde gösterilir: Aşağıdakiler arasında seçim yapmak için
  radyo düğmesini kullanın: Celsius `-` Fahrenheit `-` Kelvin (varsayılan
  olarak) C `-` F `-` K veya Belirtilmemiş.
* Şu kadar günlük hava durumu tahmini: 1; 1 ila 3 arasında seçim
  yapabilirsiniz (varsayılan olarak 1 gün)
* API yanıt dili seçim kutusu: İngilizce, tr; hava koşulları metninin dilini
  seçebilirsiniz.
* Aşağıdaki eylemleri gerçekleştirmek için şu onay kutularını değiştirin:
* Şehir ayrıntıları da dahil olmak üzere hava durumu raporunu ve hava
  tahminini panoya kopyala; onay kutusu işaretli değil (varsayılan olarak)
* Ses efektlerini etkinleştir (yalnızca geçerli hava koşulları için); bu
  onay kutusu ayrıca ses efektlerinin kurulumunu yönetmenizi sağlar; ses
  efektleri yüklenir ve onay kutusu etkinleştirilirse F5 tuşu ve ses ayarı
  kullanılabilir hale gelir.
* Ayrıca yalnız hava durumu efetlerini kullan adında ek bir onay kutusu da
  bulunur.
* Genel ses seviyesini veya son duyulan ses efektini
  değiştirebilirsiniz. Ayrıca  ortamdaki diğer sesleri
  filtreleyebilirsiniz. Onay kutusu varsayılan olarak işaretli değildir.
* Yalnızca hava durumu efektlerini kullan - Bu seçenek, ses efektleri
  etkinleştirilmişse kullanılabilir; etkinleştirilirse, tüm çevresel
  etkileri filtreleyerek yalnızca yağmur, rüzgar, gök gürültüsü vb. gibi
  hava etkilerinin dinlenmesine izin verir. (varsayılan olarak işaretli
  değil)
* Saatlerin 24 saat formatında okunmasını etkinleştir. - Bu onay kutusu
  işaretli değilse, saati 12 saatlik biçimde duyurur, örneğin, 12 AM `-` 12
  PM. Onay kutusu işaretli (varsayılan olarak)
* Ayarlar penceresinde yardım düğmelerini etkinleştir; onay kutusu işaretli
  (varsayılan olarak)
* Rüzgar bilgisini seslendir; onay kutusu işaretli değil (varsayılan
  olarak). Bu onay kutusu etkinleştirilirse, aşağıdaki onay kutularını da
  etkinleştirebilirsiniz:
* Rüzgar yönü bilgisini ekle; rüzgarın kaynağını gösterir. Varsayılan olarak
  onay kutusu işaretlidir.
* Rüzgar hızını ekle; hızı kilometre veya mil/saat olarak
  gösterir. Varsayılan olarak onay kutusu işaretlidir.
* Rüzgarın saniyede kaç metre hızda estiği bilgisini ekle;Varsayılan olarak
  onay kutusu işaretlidir. 
* Rüzgar esinti hızını ekle;  Varsayılan olarak onay kutusu  işaretlidir.
* Hissedilen sıcaklığı ekle; Varsayılan olarak onay kutusu işaretlidir.
* Atmosferik bilgileri seslendir;  Varsayılan olarak onay kutusu  işaretli
  değildir. İşaretlenirse, aşağıdaki onay kutuları da işaretlenebilir:
* Nem değerini ekle; yüzde olarak nemi gösterir. Varsayılan olarak Onay
  kutusu işaretlidir.
* Görüş mesafesi değerini ekle; görünür mesafeyi kilometre veya mil olarak
  gösterir. Varsayılan olarak onay kutusu işaretlidir.
* Atmosferik basınç değeri ekle; atmosfer basıncını milibar veya inç cıva
  olarak gösterir. İşaretliyse, basıncı milimetre cıva cinsinden
  belirtmenize izin veren ek bir onay kutusunu etkinleştiri. Varsayılan
  olarak Onay kutusu işaretlidir.
* Barometrik basınç durumunu ekle; Varsayılan olarak onay kutusu
  işaretlidir.
* Bulutluluk değeri ekle; Varsayılan olarak onay kutusu işaretlidir.
* Yağış değeri ekle; Varsayılan olarak onay kutusu işaretlidir.
* Ultraviyole radyasyon değeri ekle; Varsayılan olarak onay kutusu
  işaretlidir.
* Astronomik bilgileri seslendir; gündoğumu ve günbatımı ve ay doğuş ve
  batış zamanlarını gösterir. Varsayılan olarak Onay kutusu işaretli
  değildir.
* Ondalık ayracı için virgül kullan; etkinleştirilirse, ondalık ayırıcı
  olarak virgül kullanır, aksi takdirde noktayı kullanın. Varsayılan olarak
  onay kutusu işaretli değildir.
* Güncelleme olup olmadığını denetle; etkinleştirilirse, bu, eklentinin bir
  güncellemesi olduğunda uyarır. Varsayılan olarak Onay kutusu işaretlidir
* Ayarları kaydetmek için tamam tuşuna, iptal etmek için iptal tuşuna basın.
* Şehirler listesini değiştirdiyseniz, "İptal" düğmesine basarak yine de
  ayarlarınızı kaydedebilirsiniz. Not: Ayarlarınız şu adlı dosyaya
  kaydedilecektir:
* "Weather.ini": Weather Plus'ın başlangıç ​​ayarları.
* "Weather.volumes": genel ses seviyesinden bağımsız olarak özel ses
  seviyeleri.
* "Weather.zipcodes": Posta kodları ve tanımlarıyla birlikte şehirlerin
  listesi.
* "Weather.default": Varsayılan şehriniz.
* "Weather_searchkey": arama anahtarı kaydedildi.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=Weather_Plus
