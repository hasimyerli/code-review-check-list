**Not:** Bazı kavramlar php, symfony ve doctrine için geçerlidir. Liste güncellenecektir.

# Genel
- [ ] Kod çalışıyor mu?
- [ ] Kullanılmayan değişken, sınıf veya metot kullanımı var mı?
- [ ] Constant olarak tanımlanması gereken değerler var mı?
- [ ] Kod tekrarı var mı?
- [ ] Recursive fonksiyon kullanımı var mı? Gerekli mi?
- [ ] Mevcut kod yapısı değiştirilmiş mi? Bu kodu kullanan diğer kısımlar etkileniyor mu?
- [ ] Uzun yazılmış fonksiyonlar var mı?
- [ ] (Doctrine/Orm) Lazy loading yapan ve performans sorunu olan dql sorguları var mı? Varsa optimize edilebilir mi? Cache mekanizması kullanılabilir mi?
- [ ] Debug satırları var mı?(print_r, var_dump, vb)
- [ ] Yorum satırına alınan kod bloğu var mı?
- [ ] Yazılan ama kullanılmayan kodlar mevcut mu?
- [ ] İç içe yazılmış çok fazla if bloğu var mı?
- [ ] Yapılan geliştirme ile talep arasında uyuşmazlık var mı? Talep doküman üzerinde netleştirilmiş mi?
- [ ] Ben olsam nasıl yazardım?

# Mimari
- [ ] Business logic(iş mantığı) ayrı bir katmanda yazılmış mı?
- [ ] Design pattern kullanılmış mı? Problem için doğru çözüm mü? Doğru uygulanmış mı?
- [ ] S.O.L.I.D prensiplerine uymayan bir geliştirme mevcut mu?

# API
- [ ] Response template kullanılmış mı?
- [ ] Gerekli doküman yazılmış mı?
- [ ] Postman collection vb. dosyası paylaşılmış mı?

# Log
- [ ] Loglanan bilgi gerçekten gerekli mi?
- [ ] Kritik hataların takibi için loglama yapılıyor mu?
- [ ] Loglanmış veriler gizlilik veya güvenlik ihlali yapıyor mu? (Kredi kartı vb)
- [ ] Loglama yapılan kanal seçimi doğru mu? (Slack, Sentry vb.)

# Security
- [ ] ...
