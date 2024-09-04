👋 126 - Akış Kontrol Mekanizmaları Nelerdir ? Ne Amaçla Kullanılır ? 

Belirli şartlara göre akışın yönünü/çalıştıracağın kodu değiştiren mekanizmalardır. Buradaki akıştan kasıt kodun akışıdır. Şarta göre kodun akışını farklı şekilde yönlendirmenin iki farklı mekanizması vardır.  İf else ve switch yapılanmalarıdır. 

Akış kontrol mekanizmalarında if else yada switch yapılanmaları, aynı işi farklı şekilde yapmamızı sağlayan birbirinden farklı yapılanmalardır. 

İkisi arasında teknik olarak fark olsa da işleyiş/kullanım açısından bir fark yoktur. 

👋 127 - Akış Kontrol Mekanizmalarında Switch Case

👉 ! Switch case, kodun akışında belirli bir şarta göre yönlendirme yapmamızı (farklı algoritmalar çalıştırmamızı/farklı operasyonlar gerçekleştirmemizi/tetiklememizi) sağlayan yapılanmadır. 

👉 ! Switch case yapılanması sadece bir değişkenin değerinin eşitlik durumlarını kontrol ederken kullanılabilir. Sadece eşitlik durumu check edilecekse o zaman switch kullanılabilir. 

👉 ! Switch case yapılanmasında kontrol edilen değer ile eşitlik sağlayan case varsa diğer caselere bakılmaksızın switch bloğundan çıkılacaktır. 

👉 ! Switch yapılanmasında amaç kontrol edilen değer ile eşitlik sağlayan case varsa diğer caselere bakılmaksızın switch bloğundan çıkılmasıdır.
 
👉 ! Switch yapılanmasındaki amaç eşitlik durumuna göre belirli kod bloğunu tetiklemektir. 

👉 ! Switch yapılanmasında hiçbir case eşitliği sağlanmıyorsa default belirleyebiliyoruz. Ayrıca default kalıbı zorunlu değildir. İster koy ister koyma. 

👉 ! Kontrol edilen değerin türü ne ise case bloklarında da aynı türde değerlerle kontrol edilmelidir. Ben switch'e değer yazarken değişken adını da yazabilirim static olarak değerini de yazabilirim. Yani string yas = 10 olsun. Switch(yas)'da diyebilirim / switch(10)'da diyebilriim. Ama case de bulunan değerler değişken adı olamaz. (Değişkenlerden gelen değişken adları olamazlar) Sadece static değerler olabilir.

👉 ! Case'lerin bloklarının sıralaması ve default bloğunun yerleştirildiği yer önemli değildir. Amaç zaten eşitliği kontrol etmektir.


