👋 92 - Programlamada Operatör Nedir ? 

Operatörler bir işin sorumluluğunu üstlenen temel yapı taşlarıdır. Operatör ,bir operasyonu/işlemi gerçekleştiren yapılanmadır. İşlemlere uygun metinsel yada sembolik operatörler vardır. 
Farklı şekilde yapabileceğin uzun uzun yapacağın işlemleri kısaca yapmanı sağlayan sembolik yahut metinsel değerlere operatörler diyoruz.

👋 93 - Programlamada Operatör Okuryazarlığı

Herhangi bir operatör genellikle sağındaki ve solundaki değer ile bir bağıntı oluşturur. Bu operatör aritmetik operatör, mantıksal yada bir işleyişi/sorumluluğu üsttlenen operatör de olabilir.
Operatör, genellikle iki değer arasına konulur ve iki değer için işlem yapan yapıdır. 
Operatörler genellikle yaptıkları işler neticesinde bi sonuç dönerler.

İki değer arasında işlem yapar, kıyaslama yapar, dönüştürme yapar vs.
Semantik açıdan illa bu şekilde yazılmak zorunda değildir.

![93-1](https://github.com/user-attachments/assets/d7ea5031-4361-4ec5-9ef1-715ef19f4cb3)

Örneğin cast operatörünü düşün. Yine iki değer var ve değerlerin yyanında türler var. Bir değer var, o değerin yyanında bir tür var. O ikisini kıyaslıyor, gerekli işlemi yapıyor.

👉 ! Operatörleri kullanırken geriye dönüş değerlerine dikkat edilmesi gereklidir.

Hangi türde operatörler var? 
Aritmetik türde,
Karşılaştırma işlemlerinde,
Mantıksal yapılanmalarda,
Diğer, özel işlemler operatörleri de vardır.

👋 94 - Aritmetik Operatörler Nelerdir ? Geriye Dönüş Değeri Nedir ?

Aritmetik oepratörler, iki sayısal değer üzerinde işlem yapan operatörler oldukları için işlem neticesinde geriye uygun türde sonuç dönerler. 
Aynı türde olan sayısal değerler üzerinde işle yaparken sonuç türü aynı olacaktır.

👋 95 - Aritmetik Operatörlerde Kritik Yapalım 1 -  İnt - Double

İki farklı türde sayısal değerler üzerinde yapılan aritmetik neticesinde sonuç büyük olan türde dönecektir.

![95-1](https://github.com/user-attachments/assets/5a56da33-534f-45ab-81a1-e323cfd1b4d9)

Aritmetik operatörlerde küçük olan tür büyük olan türe bilinçsiz bir şekilde dönüştürülerek o şekilde hesap yapılır. O yüzden sonuç büyük türde elde edilir. 

👋 96 - Aritmetik Operatörlerde Kritik Yapalım 2 - İnt - Byte

![96-1](https://github.com/user-attachments/assets/f25d9de5-260a-4ed9-97de-fec3af2631de)

👋 97 - Byte -Byte

![97-1](https://github.com/user-attachments/assets/c001a75a-0981-4611-bea9-2ebcf2ecf7e2)

👉 ! Normalde iki aynı türde sayısal değer üzerinde yapılan aritmatik işlem neticesinde sonuç aynı türde dönecekken, bu iki değer byte ise sonuç er daim int dönecektir. Böyle kabul edilmiştir. İstisnadır.

👋 98 - Matematiksel İşlemlerde Öncelik Sırası Nasıldır ? 

Matematiksel işlemlerde öncelik sıralaması yazılımda da geçerlidir.

👋 99 - Karşılaştırma Operatörleri Nelerdir ? 

İki sayısal değer arasında büyüklük, küçüklük ve eşitlik durumuna göre karşılaştırma yapan oepratörlerdir. Ayrıca metinsel durum eşitliği de kontrol edilebilir. 
"<" soldaki sağdakinden küçük mü?

![99-1](https://github.com/user-attachments/assets/f3c0a251-67f5-4eee-acca-d09825a99dd8)

👋 100 - Karşılaştırma Operatörlerinin Geriye Dönüş Değerleri Nedir ? 

Sayısal değerler yada metinsel değerler için iki değer birbirleri ile karşılaştırılıyorsa, geriye ne döner. Karşılaştırma operatörleri geriye daima bool türünde değer dönecektir.

👋 101 - Mantıksal Operatörler Nelerdir ? 

Belirli şartları vardır ve bu şartları değerlendirip kendine göre sonuç döndüren oepratörlerdir.

![101-1](https://github.com/user-attachments/assets/bb0c423e-c84c-4892-ab83-8446d4e36809)

ve (&&) operatörü : Tüm şartların yerine getirilmiş olmasını ister. Patates ve köfte getir - tru true olmalıdır.

veya (||) operatörü: Şartlardan en az bir tanesinin yerine getirilmesini ister. Patates veya köfte getir. true false yada false true olabilir.

yada (^) operatörü : Şartlardan sadece/kesinlikle birinin sağlanması gerekir. Ya köfte olacak ya patates, ikisi birlikte olamaz. 

👋 102 - Mantıksal Operatörlerin Kullanım Mantığı Nasıldır ?

İki değerimiz var ve değerler arasında mantıksal ilişki değerlendiriyordu, dikkat edersen karşılaştırma yok ve bu her iki değer de bool türünde olmak zorundadır.
Mantıksal oepratörler, mantıksal değerler üzerinde kullanılır.

![102-1](https://github.com/user-attachments/assets/e760dbae-717e-45f8-aba4-92e0939c11bd)
Patates köfte örneği

Mantıksal oepratörlerde geriye bool yani mantıksal sonuçlar dönerler.

👋 103 - Mantıksal Değerlerin Geriye Dönüş Değerleri

"Ve" operatöründe, her iki şartın da true olması gerekir; aksi takdirde sonuç false olur.
true && true   // true
true && false  // false
false && false // false
false && true  // false

"Veya" operatöründe, şartlardan en az biri true ise sonuç true olur.
true || true   // true
true || false  // true
false || false // false
false || true  // true

"Yada" operatörü (XOR), şartlardan yalnızca biri true olduğunda sonuç true olur. Her iki şart da aynı (ikisinin de true veya ikisinin de false olması) olduğunda sonuç false olur.
true ^ true    // false (her ikisi de true)
true ^ false   // true  (yalnızca biri true)
false ^ false  // false (her ikisi de false)
false ^ true   // true  (yalnızca biri true)

👋 104 - C#'da Arttırma (++) Azaltma (--) Operatörleri

Sayıyı sadece 1 arttırır yada 1 azaltır. Çok kullanıldığı için bu işleme özel oepratörler geliştirilmiştir. 
int i = 5;
i++; // Önce i'nin mevcut değeri kullanılır, sonra i 1 artırılır. Çıktı değeri: 5 (eski değer), bellek değeri: 6 (arttırılmış değer).

++i; //  Önce i 1 artırılır, sonra bu artırılmış değer döndürülür. Çıktı değeri: 7, bellek değeri: 7 (arttırılmış değer).

++ ve -- : İlgili işlem sonucunda değişkenin değerini döner.

int a = 5;
int b = a++; 

![104-1](https://github.com/user-attachments/assets/7cc02cee-96fe-42c6-ae74-86e2a2fa0cf5)

int i1 = 5;
int i2 = ++i1;
int i3 = i1;
i2 = ++i2; 

![104-2](https://github.com/user-attachments/assets/1766f0a1-0ad9-423d-b107-ce3f5fe04fc3)

👋 105 - Üzerine Ekleme/Yığma Operatörü

+= operatörü, metinsel ifadelerde kullanılır. Bir sayının değerini sadeece 1 arttırmak yada 1 azaltmak istiyorsan ++ yada -- operatörü kullanılır. Eğer ben elimdeki sayısal ifadeye 3 eklemek istiyorsam, i = i + 3; yada i += 3; şeklinde kullanabilirşm. Bu işlem compiler tarafından arka pplanda aslında i = i + 3; demektir.
Benzer mantıkla i -= 3;  yada i *= 3; şeklinde kullanıp çıkan sonuç i'ye atayabilirim. Bu kullanım pratik aritmatik işlemmler yapmamızı sağlıyor.

👋 106 - Metinsel İfadelerde Kullanılan Operatörler

Üç tanedir. İki tanesi aritmatik operatörlerdekiler ile aynıdır. Sonuncusu ise karşılaştırma operatörlerindekilerle birebir aynı olacaktır. 

+ operatörü : Metinsel ifadeler + operatörü ile yanyana birleştirilebiliyorlar. Sayısal değerler + operatörü ile aritmatik işleme tabi tutulurlar. Ama eldeki değerler metinselse bu defa metinsel birleştirme operasyonuna tabi tutulurlar.
string a = ahhmet, b = mehmet; olursa
Console.WriteLine(a + b); //ahmetmehmet olacaktır.

✨ Peki metinsel bir ifade ile, metinsel olmayan bir ifade yan yana toplanabilir mi ? Eğer işin içinde metin varsa oradaki toplama aritmatik değildir, yan yana birleştirme olacaktır. 

int a = 3; 
string b = "yaso"; 
Console.WriteLine(a + b); //3yaso olacaktır. Burada cevap string döner. Bilinçsiz tür dönüşümü ile int, object türünde kabul edilir ve string ile herhangi bir türü toplarsan, int bool yada string, cevap string türde döner. 

Tür dönüşümlerinde herhangi bir değeri string'e dönüştürebilmek için ToString fonksiyonu kullanıyorduk. Ayriyeten ilgili türü string'e dönüştürebilmek için + "" ifadeyi kullanmak yeterlidir. Yani stringin bir ifade ile + oepratörüne tabi tutulması yeterlidir.

+= oepratörü, metinsel ifadelerde de kullanılabilir. Metinsel ifadeler birbirlerinin üstüne yığılabilirler.
