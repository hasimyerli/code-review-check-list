**Not:** Bazı kavramlar php, symfony ve doctrine içindir.

# Genel
- [ ] DRY (Do not Repeat Yourself) prensibine aykırı bir kod var mı?
- [ ] Karmaşık yapılar yorumlar satırları veya dokümantasyon ile destekleniyor mu?
- [ ] Kullanılmayan değişken, sınıf veya metot var mı?
- [ ] Constant olarak tanımlanması gereken değerler var mı?
- [ ] Recursive fonksiyon kullanımı var mı? Gerekli mi? (Hatalı kullanımda sorunlar oluşabilir)
- [ ] Mevcut kod değiştirilmiş mi? Bu kodu kullanan diğer kısımlar bundan etkileniyor mu?
- [ ] Kritik hataların takibi için loglama yapılıyor mu?
- [ ] Uzun yazılmış fonksiyonlar var mı?
- [ ] (Doctrine/Orm) Lazy loading yapan ve performans sorunu olan dql sorgusu var mı? Varsa optimize edilebilir mi? Cache kullanılabilir mi?
- [ ] Debug satırları var mı?(print_r, var_dump, vb)
- [ ] Yorum satırına alınan kod blokları var mı?
- [ ] Yazılan ama kullanılmayan kodlar mevcut mu?
- [ ] İç içe yazılmış çok fazla if bloğu var mı?
- [ ] Daha basit veya optimize şekilde yazılabilir miydi? Neden?
- [ ] Yapılan geliştirme ile talep arasında uyuşmazlık var mı? Talep doküman üzerinde netleştirilmiş mi?

# Mimari
- [ ] Controller içinde business logic yazılmış mı?
- [ ] Design pattern kullanılmış mı? Kullanıldıysa doğru uygulanmış mı?
- [ ] S.O.L.I.D kurallarına uyuyor mu?

# API

# Log

# Security
