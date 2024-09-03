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

string a = "ahmet"; 
string b = "mehhmet"; 
a += b; 
Console.WriteLine(a);  // çıktısı ahmetmehmet olacaktır. 

== operatörü, metinsel ifadeleri birbireriyle kıyaslayabilir/karşılaştırabiliriz. Eşitlik durumunu karşılaştırıyoruz.(içerik olarak, değer olarak)

string a = "ahmet"; 
string b = "mehmet"; 
string c = "mehmet"; 

a == b , false döner.
b == c  true döner.

Ben, elimde metinsel değerlerin birinin diğerinden büyük mü küçük mü olduğunu anlayabilmek için bunların lengthlerini karşılaştırırım.

a != b; eşit değil mi operatörüdür, bool döner.

👋 107 - ! Operatörü 

Bu oepratör programlamada olumsuzluk alamına gelir. Yani tersi/değili anlamına gelir. Bu operatör, 1. durum için; Mantıksal yapılarda olumsuzluk ifade eder. True yada false durumlarında yani.

!true, false anlamına gelir. True'nun değili/olumsuzu.
!false, true anlamına gelir. 

2. durum için; Eşit değildir durumuna bakar. "!=" , eşit değillik durumuna karşılık gelir.

3.durumu için; null referance özelliği(C# 8.0 ile geldi), string ifadelerde null durumlarında belirli kontroller yapar. Bool ifadenin başına(mantıksal değerlerin başına) ! konulabilir. 

![107-1](https://github.com/user-attachments/assets/27a81cb4-2b87-4672-b8af-f939fe066423)

👉 ! !3 , !"Ali" diyemezsin. 

👋 108 - Ternary Operatörü

Bir kalıpsal operatördür. Şarta bağlı değer döndüren operatördür. Duruma göre farklı değeri döndürebilmek için, if yada switch yapılanmaları kullanabiliriz ama bu kadar kalıba gerek yok. Ternary operatörü ile yappmak daha basittir. 
Bir değişkene/metoda/propertye değer atarken, eğer ki değer şarta göre fark edecekse satır bazlı/tek satırda şart kontrolünü yaparak duruma göre değeri döndürmemizi sağlayan bir kalıpsal operatördür. 

Ternary oepratörü kalıbı kullanımı,

![108-1](https://github.com/user-attachments/assets/fb114dfb-93f4-4efa-92ea-1dfcfa9ae693)

...şart/durum...?...1.durum : 2.durum; buradaki şarta göre geriye bir değer döndürür. Karşılaştırma yada mantıksal işlem neticesinde bool sonuç döndürür. Şart true ise durum1, false ise durum2 dönecektir. 

Bu kalıbın kendine göre kuralları vardır. True ve false kısımları aynı türde olmalıdır çünkü ona göre gelen değer tutulup, karşılanacaktır. 

👉 ! Polimorfizm kurallarına göre, birbirinden türeyen değerlerde desteklenir. C# 9.0 ile geldi.

bool medeniHal = true;
string mesaj = medeniHal == true ? " evlilere kamanya..." : "bekarlara kampanya...";

👋 109 - Ternary Operatörü - Birden Fazla Condition Uygulamak

Yaşı 25'ten küçük olanlara a, 25 olanlara b, 25'ten büyük olanlara c değerini döndüren ternary oepratörünü oluşturalım. 

string sonuc = yas < 25 ? "A" : (yas = 25 ? "B" : "C");

👋 110 - Ternary Operatörü Örneklendirelim 1 

![110-1](https://github.com/user-attachments/assets/1d3facfb-43b7-4444-9943-6b4ecd672643)

Console.ReadLine: Kullanıcının girdiği değeri string olarak akalayan/getiren komuttur. o satırı okur. Kullanıcının değer girmesini bekler bu komut. Eğer hiçbir şartı sağlamıyorsa en son -1 yada bir hata mesaı fırlatabilirim. 

👋 111 - Ternary Operatorü Örneklendirelim 2 

![111-1](https://github.com/user-attachments/assets/142ef6b7-7195-4a2a-a46b-cc5115a20684)

En sonuncu önergenin şartını bildirmek zorunda değiliz. Zaten diğer şartlar sağlanmadığı için mecbur en son önerge geçerli olacaktır, başka ihtimal yok. 
Algoritmada 4 tane şart verdiyse, ilk üçünün geçerli olmadığı durumda 4. geçerli olacaktır. Buradaki 4. şart, hiçbirinin olmadığı durumunda geçerli olan şarttır aslında. 

👋 112 - Atama (Assign) Operatörü

Bir değişkene/alana/property'e değer atamayı sağlayan operatördür. Değer atarken sol taraftaki değişken kısmına sağ taraftaki değeri atamayı sağlar. Atama operatörünün sağ ve solu bizim için önemlidir. Sol tarafta değişkenin kendisi, sağ tarafta değeri gelir. 

👉 ! İleride referans türlü değişkenlerde atama operatörü, referans etme opepratörü olarak kullanılacaktır. 

👋 113 - (.) Member Access - Üye Erişim Operatörü 

Elimizdeki değerler/türler aslında alt elemanlara sahiptir.

![113-1](https://github.com/user-attachments/assets/01eff2bd-ca42-4c99-9ec7-ec901b663d5d)

int i = 5; dedik ve i. dediğimde erişebileceğim komutlar çıkıyor. İşte bu komutlara memberlar/elemanlar diyoruz. 
Eleman dediğimiz olay, bir türün altındaki kodlardır, altında erişebildiğimiz/çağırdığımız/çalıştırdığımız propertyler/metotlar/fieldlardır.

👉 ! Bir kodun devamında çağırabildiğin bütün kodlar o kodun/o türün memberlarıdır. 

Member access operatörü, elimzdeki kodun değerin türüne uygun memberlarına erişmemizi sağlayan oepratördür. 

. . . şeklinde gidebiliri. Hiyerarşik yapı gibi düşünün, ta ki eldeki değer değersiz duruma gidene kadar yada işin bitene kadar.

👉 ! Member access kodun devamını getirir.

👋 114 - Cast Operatörü

Yapısal olarak genellikle dönüşümlerde kullanılır ve birden fazla sorumluluk üstlenir. 

3 yerde kullanılmıştır. 
Boxing unboxing
Bilinçli tür dönüşümleri
Char int'2 yda int char'a ascıı üzerinden 
genellikle tür dönüşümlerinde kullanılan operatördür. 
()value : parantez cast'i ifade eder. İçine verilen değer neyse ona dönüşüm gerçekleşir. 

![114-1](https://github.com/user-attachments/assets/08b7fa0f-c244-440a-864d-f498e8906b99)

👋 115 - SizeOf Operatörü

Sizeof oepratörü metinsel bir keyworddür. 
Verilen türün bellekte kaç byte yer kapladığını integer olarak geriye döndürür.
sizeof(int) : 4
sizeof(long) : 8
sizeof(decimal) : 16

👋 116 - TypeOf Operatörü

Verdiğimiz türün/değerin typpeını/türünü getirir.
O tür ile ilgili bilgileri edinmek için kullanılan bir oepratördür.
İleride(ileri düzey pprogramlamada) reflection dediğimiz bir konuda elimizdeki bir türün reflectiona girmek için kullanıldığını göreceğiz. 

![116-1](https://github.com/user-attachments/assets/c6dfe7bf-90f0-4c47-8f12-80b48d0af55a)

Type t = typeof(int); // int türüne ait tümm bilgiler burada t değişkenine atanmıştır.

👉 ! Type türü, değer türlü bir değişken değildir. Dolayısıyla referans türlü bir değişken olduğunu ileride konuşacağız.
