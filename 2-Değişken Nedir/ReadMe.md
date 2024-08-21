👋 31 - Değişken Nedir? Bir Programcının Değişkene Neden İhtiyacı Olur?

Bir programcının amacı eldeki verilerle oluşturulan yazılımların doğru bir şekilde işlenip sonuçlar elde edebilmesidir.

Hangi yazılım olursa olsun amaç, burada bir veriyi doğru bir şekilde işleyebilmek doğru bir şekilde işlerken bu veriyle ilgili operasyonları gerçekleştirebilmektir.

Değişken, bu yazılım sürecinde bir amaca hizmet eden bir yapılanmadır.
Yazılımalar veriyi doğru bir şekilde işleyip çıktı veren yapılanmalardır.
Burada merkeze veriyi alırsak bu veri yazılımın neresindedir? İşte işlenecek bir veri var ve bunu yazılımda bir yerde tutmam lazım. 

👉 ! Bilgisayarda ram dediğimiz bir kısım var. Ram'e geçici bellek yada önbellek deriz. O anki çalıştığımız verileri Ram'e koyuyoruz. Dolayısıyla işlem yapma esnasında işlem yapılan/işlenen veri Ram'de tutulur.

Ram kendi içinde bölümlere ayrılmış bir yapılamaya sahiptir.
Yazılımda biz şunu yapıyoruz. Diyoruz ki benim elimde 5 diye bir değer var.
Bu 5 değerini benim Ram'e koyup oradan daha sonra yazılımda işleyebilmem
gerekiyor. Yazılım Ram'deki bu 5 değerini alabiliyor kendi bünyesinde işleyebiliyor yada ürettiği 5'i yine Ram'e koyabiliyor.

👉 ! Yani yazılım veri tutmaz. Yazılım veriyi Ram'den alır Ram'e yerleştirir.

👉 ! Yazılımda veri tutulamz Ram'de tutulur.

Yazılım da yapılacak işlemlerin en küçük en merkezi noktası olan veriyi biz Ram'de tutarız. 

Bir yazılımda işlenecek veriyi Ram'de tutabilmek için değişkenler kullanılır.

Değişken dediğimiz, yazılım adına Ram'e veri koymamızı ve ihtiyaç doğrultusunda o Ram'deki veriyi elde etmemizi sağlayan yapılardır.

Yani sen bir veriyi işleyebilmek için o veriyi yazılıma koyabilmen için onu gidip yazılım adına Ram'e koyman lazım. İşte o yazılım adına veriyi Ram'e koyan yapılanmaya değişken denir. 

Değişken, adı üstünde değişen/değişken yapılardır.

Bir programcı verisini tutabilmek için değişkene ihtiyaç duyar. 

👉 ! İşlenecek veriler veritabanında tutulur doğru ama siz yine bunu işleme esnasında bu verileri Ram'e almanız gerekecektir. 

👉 ! İşlem boyutundayken veritabanında bir veriyi işleyemezsin. Ram'deki veriyi işleyebilirsin. 

👉 ! Biz iş yapıyorsak %100 Ram'de çalışmalıyız. 

Bir yazılımın Ram'de çalışabilmesi, Ram'e değer koyabilmesi, Ram'deki bir değeri elde edebilmesi için değişkenleri kullancağız. 

Değişken bir programcının yazılımda işleyeceği veriyi Ram'de o program adına tutabilmesi için kullandığı bir yapılanmadır. 

Yazılımda işlenecek veriyi yazılım adına Ram'e yerleştirebilmek için biz programcılar değişkenleri kullanırız. 

![36](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/aab36f51-c993-432c-93d6-006870a5b326)

👉 ! Ayrıca Ram'in bu veriler üzerinde işlem yapabilmesi için, veri türününde Ram'e belirtilmesi gerekir. Örneğin, "Ahmet" değeri ile 3 değeri arasında çarpma işlemi yapılamaz. Çünkü veri türleri farklıdır. 


👋 37 - Value Type - Primitive Type - Değer Tipli Değişkenler

Değişkenler bilgisayarda yazılım adına Ram'de veri tutan yapılardır. Yeri geldi mi bu değerler üstünde işlem yapmamızı sağlayan bu değerleri elde etmemizi sağlayan yeni üeretilen değerleri yazılım adına tekrardan Ram'de depolamamızı sağlayan yapılardır. 

👉 ! İşlenecek veriler ram üzerinde tutulur. Ram bu verilerin değerlerini tutabilmek için alan tahsis eder. Bu alan tahsisi verinin türüne göre yapılır. Ayrıca bir türde tanımlanmış alana farklı bir türde olan değer verilemez. Veri türü ve ram de o tür için ayrılan alan uygun olmalıdır.

👉 ! Değişkenlerle tür bildiriken bool, char, byte, int gibi keywordler kullanırız.

👉 ! “String” de metinsel ifadeleri tutmaya yarayan değişken türüdür. Ama değer türlü değil, referans türlüdür.

Yazılımda çalışırken değişken sayesinde yazılımda işleyeceğiniz veriyi değişken vasıtasıyla Ram'e yerleştirip orada işleyceksiniz ve işlerken Ram üzerinde tutmanız gerekecek. Dolayısıyla Ram diyor ki vereceğin değerin türünü bildirmek zorundasın. 

👉 ! Ram'e yerleştireceğin verinin türü neyse onu başta bildirmen gerekiyor ki ona göre Ram'de alan tahsisi yapılsın. 

👉 ! Ram'de hangi türde(int,string, char ...) alan tanımlanırsa/tahsis edilirse oraya sadece o türe ait bir değer atamak zorundasın.

Ram'de veri tutabilmek/depolayabilmek için tanımlanacak olan değişkenin türü/veri türü bildirilmelidir.

👉 ! Tür elimizdeki veriye göre bildirilir. 

Elimizdeki verinin türünü elimizdeki veri belirliyor. Ram'de hangi değeri tutacaksan o elindeki veriden türü çıkartıyorsun. 

Bir değişkenle Ram'de alan tahsisinde bulunulduğunda buna değer türlü değişken denir. Yani tuttuğu değer bir normal değer olan değikenlere değer türlü değişken denmektedir.  

Yani tuttuğu değer bir normal değer olan değikenlere değer türlü değişken denmektedir.  

Ram'de alan tahsisi bulunan bu değişken içinde 3,5,hüseyin gibi değerler tuutluyor. Değişken içinde değer tutar. İşte tuttuğu değerin karşılığında bir alan tahsisi yapan değişkenlere biz değer türlü değişkenler diyoruz. Normal bir değer 3, 5, yaşın gibi normal değerler. 

Referans türlü değişkenler değer tutmaz, değerden daha fazlasını tutar. 

Örneğin, bir değişken var ve benima dımı tutuyor. Bu değer türlüdür çünkü adım bir değerdir. Ama bir değişken daha var komple beni tutuyor. Ben bir değer değilim, değerler bütünüyüm. Adım, yaşım vs var.

Hem adım hem ben birer veriyiz ama adım bir değer türlü veriyken ben farklı bir veri türüyüm. Biz buna nesne deriz. İşte nesneleri tutan değişkenlere de referans türlü değişken deeriz.

Değer türlü değişkenler sadece bir değer tutan değişkenlerdir. yani adımız, soyadımız, doğum tarihimmiz vs. gibi değerlerdir.

Adının, yaşının, doğum tarihinin hepsinin bir değeri var. Yaş sayısaldır, adın metinseldir, adının baş harfi chardır. İşte biz bunun gibi yapıları tutan değişkenlere değer türlü değişken deriz.

Primitive Type, en ilkel türdür. Primitive, yani türetilmemiş, ham/sade bir veridir. Örneğin byte bir primitive türdür. Fakat bytle'lardan meydana gelen decimal türü ise primitive tür değildir, bytelardan türemiştir. Ama value type'dır yani tek bir değeri/normal bir değeri tutar. 

Hiçbir şey olmasa bile var olan tür Primitive türdür. Mesela decimal olabilmesi için byte'ların olması gerekir. Byte'lardan meydana gelen decimal normal value type'dır.

Byte ise tek başına bir veridir. Hiçbir şey olmadan tek başına var olan bir tür oduğu için Primtive'dir. Aynı zamanda da value type'dır.

Value type'lar primitive type'ları kapsar.

Ram'de değişkenler sayesinde değer tutabilmekteyiz. Değişkenler değer türlüyse yani değer tuttuğumuz değişkenlerde bu değerin karşılığını türünü Ram'e bildirmek zorundayız. Dolayısıyla burada değişkenlerdeki türler Ram'de tutulacak verilerin hangi türde olduğunu bildiren yapılanmalardır. Biz bunları bildirmek zorundayız. Ram'de çalışırken hangi türlerle çalıştığımızı bildirmek zorundayız. 

String metinsel ifadeleri tuttuğumuz değişken türüdür. 

Sayısal türlü değişkenlerin max ve min değerleri vardır bu aralıkalrda değişkenlerin değerlerini girebilirsiniz. Tutacağınız sayısal ifadenin boyutuna göre değişken türünü belirlemelisiniz. 

Mesela 3 değerini tutacaksın. Byte'da tutabilirsin int'de de, ama Ram'de bu kadar alan(..........) tahsis etmek var bir de 3'e yakın sınırlarda olan alanı(...) tahsisi etmek var. Hangisi daha mantıklı/az malliyetli olocaksa o tercih edilmelidir. Yani kendisine yakın olan alana tam sınırında girebilen değişken türünü tercih etmemiz en doğrusu olacaktır. Bunlar optimize kod yazarken/yazılımın daha hızlı/performanslı çalışması için dikkat ettiğimiz kurallardır. 

![39](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/28e4079e-613b-4a2f-8244-2502aaf960d3)

👋 38 - Değer Türlü Değişkenlerde Primitive Kontrolü - IsPrimitive

Bir türün primitive(ilkel) olup olmadığı “typeof(kontrol_edilecek_veri_turu).IsPrimitive” ile kontrol edilir. Buradaki "." member access yani üye erişim operatorüdür. Bu kontrol sonucunda dönen true yada false ile primitive tür olup olmadığı anlaşılır. 
"Decimal" bir primitive tür değildir. Çünkü arkada "byte"lardan daha doğrusu int türlerden oluşur/meydana gelir. Değer türlüdür ama "Primitive" değildir. "int" ve "byte" hem değer türlüdür hem de "Primitive"dir yani herhangi bir başka türden meydana getirilmezler. 

👋 39 - Değişken Türleri Nelerdir? Detaylı İnceleyelim

Değişkenlerde tanımlama yaparken bir değer tutarken Ram'de bunun türünü bildirmemiz geerekiyordu. Örneğin "Ali" değerini tutacaksam "string", "1000" değerini tutacaksam "short" veri tipinde tutarım.  "1000" değerini "int"tede tutabilirim ama büyük bir alanı boşa harcamış olurum.

Tutacağımız değer hangi aralığa giriyorsa, en yakın aralığa giren türü tercih etmek gerekir. Doğru değer türünü tercih etmek uygulamanın bellek yönetimi, performansı açısından bize avantaj sunar.

"string" metinsel ifadeleri tuttuğumuz değişken türüdür. Char'da ise sadece tek bir karakter tutabiliriz. 

![39](https://github.com/user-attachments/assets/9d1c9f6b-4d13-4300-bd7a-ecfd9fa22e2c)

👋 40 - C# Temel Kuralları

"{}", scope denir.

![40](https://github.com/user-attachments/assets/181f7cbd-2939-4ade-82a5-9800d108bfd2)

C# Dil Özellikleri;
C# programlama dili nüyük küçük harf duyarlılığına sahiptir.
C# programlama dili tip güvenliği olan dildir. Elde bulunan veriye uygun rame tür bildirimi yapmak gerekiyor. İşte buna tip güvenliği denir. Yani veri türü ile ramde ayrılan alanın türü uygun olmalıdır.

👋 41 - Değişken Tanımlama

Değişken tanımlama/oluşturma bir konsept meselesidir. Bir değişkeni tanımlamak istiyorsak önce modelini oluşturmalıyız. Yani prototipi, çnce "degisken_turu degisken_adi;" şeklinde belirtilir. Burada ";" kod konseptini kapatır.

Örneğin, "string name;", bu tanımlamaya göre derlendiğinde ramde "string" türünde ve "name" adında alan ayrılmıştır.

![41](https://github.com/user-attachments/assets/59cccba1-b493-4ce3-a201-cdc7a81070ec)

👋 42 - Ram Yapısı ? 

Ram, bilgisayarın çalışma belleğini temsil eder ve verilerin saklanması/erişilmesi için kullanılır. Ram temelde stack ve heap olarak iki yapılanmadan oluşur. Stackte, değer türlü değişkenler tutulur. Heapte ise nesneler tutulur. Stackte, değişkenlerin türü, adı ve değeri tutulur. Ayrıca metot isimlerine (bellek adresleri) de tutulur.
Metotlar çağrılabilir yapılardır ve isimleri ile çağrılırlar. O isme karşılık gelen bellek adresi stackte tutulur. 
İleride heap ve stack arasında referans türlü değişkenlerin, referans mantığı anlatılacaktır.
Referans dediğimiz aslında, değişkenin kendisidir. Değişkenin kendisi stackte tutulur. Stackteki değişken, yani referansla heapteki bir nesneyi işaretlemeye referans türlü değişkenler denir.
"int yas = 5" tanımlanmış olsun. Burada "yas"a bazı makalelerde referans denilebileceğini görürsünüz. Aslında "yas" ismi adı/değişkeni anlamlarına gelir. Referans türlü değişken olduğunu düşünmeyin. "yas" ismi 5 değerini tutuyor, referans ediyor.

![42](https://github.com/user-attachments/assets/75323a54-76fe-4a1a-97e7-ce801e77a404)

👋 43 - Değişkenler Ram'de Nasıl Tutulur?

Değişkenler kod olarak yazılır yazılmaz alan tahsis etmezler. Ne zaman ki biz programı çalıştırırsak(yani compiler tarafından derlendikten sonra runtime olduğu anda) o zaman bellekte alan ayrılır.  

int yas;
string adi;
string soyadi; 
kodu çalıştırdığımızda, konsept (her bir ";" a kadar olan kısmı ifade eder.) şeklinde senkron olarak bellekte tutulur. Stack LIFO (Last In First Out) mantığına göre çalışır. Yani Son giren ilk çıkar.

👉 ! LIFO, Ram'in doğrudan çalışma şekli değil, bellek yönetimi algoritmalarının özelliğidir.

![43](https://github.com/user-attachments/assets/a23a455f-e899-422b-9c26-e9d6bfdc9d0f)

👋 44 - Değişken Tanımlama Kuralları 

Değişken isimleri yazılım sürecinde developer açısından bir karışıklığa mahal vermemek için anlamlı olmalıdır.

1- Anlamlı İsimlendirme : Değişken isimlendirmede tutacağım değerin anlamını ifade eden değişken isimlendirmeleri kullanmak yaızlım geliştirme sürecinde developer için faydalı olacaktır.
 
2- Özel Karakter Kullanılmamalı : Değişken isimlendirmelerinde (, . ;) gibi özel karakterler kullanılmaz. "_" ise istisnai bir durumdur.

3- Sayı Durumuna Göre Kullanımlar : Değişken isimlendirmede sayı kullanılmak istenirse değişkenin adına sayı ile başlayamazsın ama değişken adı içinde sayı kullanabilirsin. "1sayi" yanlış bir kullanımken "sayi1"" doğru kullanımdır. 

👉 ! Bir scope içinde birden fazla aynı isimde değişken tanımlanamaz.

👋 45 - İsimlendirme Kuralları - Name Convention - Pascal Case - Camel Case - Snake Case 

Pascal Case : Her kelimenin ilk harfi büyük yazılır. Kısaltma iki harfli ise her 
iki harfte büyük yazılır. In/Out -> IO, InOutStream -> IOStream şeklinde yazılır.

Camel Case : İlk kelime küçük diğerleri büyük yazılır. 

![45](https://github.com/user-attachments/assets/4a8181e9-591f-43f2-8b13-bcb8b073c09e)

Snake Case : İlk kelime küçük diğerleri büyük yazılır.


👋 46 - Değişken İsimlerini "@" Operatorüyle Tanımlama

Normalde bir değişken tanımlanırken, değişken ismi için programatik keyword kullanılmaz. Eğer programatik keyword değişken adı olarak kullanılmak istenirse bunu programa, bu bir keyword değildir şeklinde bildirmemiz gerekiyor. İşte "@" operatorü ile keyword kullanırsak bunun bir programatik keyword olmadığını, bizim tıpkı "age" "name" şeklinde kullanabileceğimiz normal bir değişken ismi gibi değişken adı tanımladığımızı söylemiş/belirtmiş oluruz. 

string name; //normal bir kullanımdır.
string @string; // C#'ta metinsel ifadeleri tanımlamada kullanılan bir keyword olan "string" kelimesi normal bir değişken ismi gibi "@" kullanılarak belirtilmiştir. 

👋 47 - Tanımlanmış Değişkene Değer Atama

Değişkene tanımlandıktan sonra değer atanır. Tanımlanan değişken, belleğin stack kısmında, değer türlü değişkenlerin (tek 1 değeri olan, nesne olmayan) türü, adı ve değerleri ile tutulur. Eğer tanımlama esnasında değişkene değer atamak istersem, "int number = 5;" konsepti kullanılır, burada "=" ifadesi atama(assign) opratorüdür. Assign operatorü, sağdaki değeri soldakine atar. Bir değişkene değer atanacaksa kesinlikle değişken solda, atanacak değer sağda olmalıdır.

![47](https://github.com/user-attachments/assets/7ceecc72-d70f-48ae-ab10-9ae549c2ac42)

Eğer ki değişken ismi assign operatorünün solunda kalıyorsa o alana değişkenin kendisi gelecektir. Tam tersi durum olursa değişken ismi sağda olursa bu defa sol tarafa değişkenin değeri gidecektir.

int x;
...
x = 120; 
Bu örnekte, "int" türünde "x" adında ramde alan tahisi edildi. Daha sonra dedik ki bu x değişkenini getir.  O alana git ve değerine 120 ata. Eğer "x" assign solundaysa kendisi gelecekti. Kendisi ve değeri gitmesi farklı şeyler!

![47-2](https://github.com/user-attachments/assets/c02557ef-0f4c-442e-93ba-fd1f219393f6)
 
👉 ! Bir değişkenin değerinde en son değer geçerlidir. Yani bir değişkene birden fazla değer atayabilirim ve atadığım en son değer geçerlidir. Önceki değerler ezilecektir/yok sayılacaktır/geçersiz olacaktır.

int a = 5;
a = 15;
a = 20;
örneğe göre var olan a değişkei öağırılıp değeri değişir, yeni bir a oluşmaz ve değişkenin son değeri 20 olur.

![47-3](https://github.com/user-attachments/assets/3a8f00f3-be21-4bff-b25d-31be480462d5)

👉 ! Tanımlanmış olan değişken türüne göre değer atanmalıdır.

👋 48 - Bir Değişkene Değer Atama Kuralları

Değişkenler türüne göre kategorize edilir. Dört kategoride değer türleri vardır. Bunlar metinsel, karaktersel, mantıksal ve sayısal değerlerdir.

Metinsel değerler, string keywordu ile tutulur. Metinsel ifadeler "" içine yazılır. Bir sayısal ifade ""(çift tırnak) içinde yazılarak tutulursa yazılım açısından bu ifade metinsel ifade olarak kabul edilir ve tutulan sayısal değer üzerinde herhagi bir matematiksel işlem yapılamaz. "string sayi = 4;" gibi. 

Karakter değerleri ''(tek tırnak) içinde tutulur ve sadece tek bir karakteri tutar. (o ; 3) gibi.

Mantıksal değerler bool türünde tutulur. True(1) yada false (0) olarak belirtilir. "bool medeniDurum = false;" gibi.

Sayısal değerler direkt olarak tutulur. 1000 sayısını tutmak istediğimiz düşünelim. Peki bu hangi türde bir sayısal ifade olacaktır. Sayısal ifadelerde bir değer default olarak "int" kabul edilir. Bir sayısal tür değer aralığına girmeyen değeri tutamaz. Compiler hata verir. "int yas = 1000000000" hatalı bir kullanımdır.
 
Ondalıklı Sayılar : Tüm ondalıklı sayılar tam sayıları karşılayabilir. Ondalıklı sayılar, "float", "double" ve "decimal" türünde tutulabilir. Ama küsüratlı sayılar olmaya başlayınca sıkıntı olmaya başlıyor.

Float : Float türünde küsüratlı bir değer tutarken ilgili değeri sonuna f yada F getirilir. "3.14f" yada "3.14F" gibi.

Double : İlgiil değerin sonuna d yada D getirilir.  "3.14d" yada "3.14D" yada "3.14" gibi.

Decimal : İlgili değişkenin sonuna m yada M getirilir. "3.14m" yada "3.14M" gibi.

👋 49 - (_a,_b) = (a,b) Tuple Türüyle Değer Atama

Tek bir syntax ile birden fazla değişkeni tanımlamamızı sağlayan bir nesnedir. 
(int a, int b, type c, type d) z; burada tuple değişken tanımlaması yapılmıştır. z içinde , int type vs. olmak üzere birden fazla farklı yada benzer türde değişken tanımı yapılır. Yani tuple birden fazla değişken tutar ve bu değişkenlerinde değerleri olacak. Bunlasr yine stackte tutulacak. 

👉 ! Tuple, değişkene değer atama türüdür.

Şöyle ki, C# dilinde tuple'lar kullanılarak birden fazla değeri tek bir değişken içinde gruplayabiliriz. (int a, int b) c = (3,5); Bu durumda, c adında bir tuple tanımlanır ve içinde ik tam sayı değeri saklar. Bu tuple, stack belleğinde oluşturulur. a ve b isimli iki tamsayı değişkeni gibi davranır ve tuple içinde 3 ve 5 değerleri atanır. C#'ta tuple'lar genellikle küçük veri yapılarını temsil etmek için kullanılır ve bu nedenle genellikle stack belleğinde saklanırlar. Ancak, büyük tuple'lar veya tuple'lar bir koleksiyonun içinde kullanıldığında heap belleğinde saklanabilirler. Tuple'ın boyutu ve içeriği ramde saklanacak davranışı etkileyebilir. 

Tuple nesnesi, içine bir veya dah afazla değişken tanımlayabildiğimiz tek bir tanımlık nesnedir. (int a, string b) c = (5,  "ali"); burada atamalar da sırayla oluyor. a'ya be b'ye erişim sağlamak için c. ile erişiyoruz. 

![49](https://github.com/user-attachments/assets/f992b5f4-cb8b-49eb-8a78-f9c85478356c)

Tuple, C# 7.0 programlama dilinde bir veri yapısıdır. Tuple, farklı veri tiplerinden oluşan, sabit uzunlukta ve değerleri değiştirilemeyen(immutable) bir koleksiyondur.

👉 ! Tuple bir nesnedir. C#'ta her şey bir nesnedir ve Tuple da System.Object sınıfından türemiştir.

Değerleri değiştirilemezdir. (immutable)
Farklı veri tipleri içerebilir.
Eleman sayısı oluşturulduğunda sabittir.
Elemanlara Item1, Item2... şeklinde erişilir.

Tuple<int, string> person = new Tuple<int, string>(25,"ali );
int age = person.Item1;

ValueType adında struct kullanılmaya başlayınca;
(int Age, string Name) person = (25, "ali");
Console.WriteLine($"Age: {person.Age}");

Maximum 8 öğe içerebilir. Daha fazlası için iç içe Tuple'lar kullanılabilir.
Orijinal Tuple'larda öğelere anlamlı isimler verilmez. Item1, Item2 ...

Tuple, bir referans tipidir. Yani heap belleğinde saklanır. Bu, büyük miktarlarda kullanıldığında performans açısından dezavantaj olabilir.

✨ Tuple'ın Nesne Olması : Tuple bir nesnedir, ancak sadece System.Object'te türediği için değil. C#'ta her şey(değer tipleri dahil) en temel seviyede Object sınıfından türer. Tuple bir nesnedir çünkü, 
Referans tiplidir.
Heap'te depolanır.
Garbage collection'a tabidir.
 
✨ Koleksiyon ve Nesne Farkı : 
Nesne, veri ve davranışalrı(metotları) kapsülleyen bir yapıdır.
Koleksiyon, birden fazla nesneyi veya değeri içeren bir veri yapısıdır. 
Yani bir koleksiyon aynı zmanada bir nesnedir. Tuple, hem bir nesne hem de bir koleksiyon olarak düşünülebilir.
 
✨ Tuple'ın Heap'te Tutulması :
Tuple heap'te tutulur. Çünkü, 
 * Referans Tipi - Tuple bir referans tipidir. C#'ta tüm referans tipelri heap'te depolanır.
 * Değişken Boyutu - Tuple'lar farklı boyutlarda olabilir ve farklı tiplerde veriler içerebilir. Heap, bu tür değişken boyutlu ve karmaşık yapılar için uygundur.
 * Yaşam Süresi - Heap'teki nesneler, referansları olduğu sürece yaşarlar ve garbage collector tarafından yönetilirler. Bu, Tuple'ların metot çağrıları arasında bil evarlıkalrını sürdürmelerine olanak tanır.
 * Esneklik - Heap dinamik bellek tahsisi sağlar, bu da Tuple gibi yapıların runtime'da oluşturulmasına ve yönetilmesine izin verir.

✨ Stack'te Tutulmamasının Nedenleri:
Stack, genellikle sabit boyutlu ve kısa ömürlü veriler için kullanılır.
Stack'in boyutu sınırlıdır ve büyük veya karmaşık nesneler içi uygun değildir.
Stack'teki veriler metot çağrıalrı arasında otomatik olarak temizlenir, bu da Tuple gibi daha uzun ömürlü olabilen yapıar için uygun değildir.

👉 ! C# 7.0 ile birlikte gelen valueTuple, Tuple'ın bir değer tipi versiyonudur ve stack'te tutulur. 

👋 50 - Literal Düzenlemeler C# 7.0

Kompleks sayısal ifadelerin "_" ile düzenlenmesini sağlayan bir özelliktir. 
int sayi = 1_000_000_000 gibi

👋 51 - Değişken Türüne Uygun Default Değer Atama

Tüm değişkenlerin bir default değeri vardır. Default değeri nerde, nasıl, ne şekilde atandığını daha sonra class yapılanmalarında göreceğiz. 
İleride oop dediğimiz yaklaşşımı gördüğümüzde class içinde tanımlanan değişkenlerin default değerleri otomatik olarak atanır.

👉 ! Null değersiz demektir ve değersizle boş arasında fark vardır. Boş, boştur ama yine de bir karakterdir(boşluk/space tuşunun oluşturduğu karakter). Null, değeri yok demektir.

👉 ! string = null
     char = "\0"
     sayısal ifade = 0
     bool = false
     
👉 ! Normalde bu varsayılan değerler, class içinde otomatik atanmaktadır. Ama main içinde atanmaz. Bir türün default değerini "default(ogrenilmek_istenen_tur)" olarak görebilirsiniz.

👉 ! Main içinde oluşturulan değişkenlerin ilk değerlerini manuel olarak atamaya  özen göstermeliyiz.

👋 52 - Default Literals C# 7.1

"default(ogrenilmek_istenen_tur)" bu kullanım yerine, değişkeninde belli olduğu "default" kullanımı yeterlidir. 
string ad = default; gibi bir kullanım. 

👋 53 - Tanımlanmış Bir Değişkenin Değerini Okuma

Bir değişkenin değerinin okunabilmesi için, önce değişkenin tanımlanmış olması daha sonra atamasının yapılması gerekiyor. Değişken değerini elde edebilmek için değişkenin isminden faydalanılır. 

👉 ! Bir değişken adı, assign operatörünün sağında yada metotların parametrelerinde çağırılıyorsa, ilgili değişkenin değeri gönderilir.

Mesela "Console.WriteLine(x);" veya "int y = x;" burada, işte bu durumda x yazılan yerlere x'in değeri gönderilecektir. x'in kendisi çağrılsaydı(bellek adresi gider) x, değer almaya gidecekti. Amma burda x'in değeri çağırılıyor. 

👉 ! Console.WriteLine() ekrana çıktı veren, ekrana bişey yazmamızı sağlayan bir komuttur.

👉 ! Console bir sınıftır/class'tır. Bu sınıfın üzerinden direkt bir member'a erişilebildiği için static bir yapılanmadır. Bu static member'ın bir metot olduğunu buna erişirkende static yapılanmadan faydalanıp erişebildiğimizi .'nın modifier access operatörü olduğunu metotların parametre alabildiğini ileride göreceğiz.

👋 54 - Tanımlanmış Bir Değişkenin Değerini Okuma - Kritik 1 

int a = 5;
int b = 10;
int c = b;
int d = a;
b = a;
c = b;

![52-1](https://github.com/user-attachments/assets/04c798e6-97e0-45cf-9ee8-d90bfdd04f4f)

![54-2](https://github.com/user-attachments/assets/0d4ab57d-f03f-419c-8e94-48e653131b3d)

👋 55 - Tanımlanmış Bir Değişkenin Değerini Okuma - Kritik 2

int a = 5;
a = a;

![55](https://github.com/user-attachments/assets/3efb199e-5428-40f0-8ea9-f3ff002cd3ee)

👋 56 - Değeri Olmayan Değişkenler

Bir değişkeni main metodu içinde oluşturduğunuzda bellekte alan tahhsis edilir ve bu değeri olmayan değişkenlerle neler yapılır?
Classlarda değişken tanımlanıp atanmazsa otomatik atanma default değerlerle yapılıyordu. 
Mainde değeri olmayan bir değişkeni bir yerde çağıramam(değerini yazdıramam).
Başka bir değişkene, değeri olmayan bir değişkeni atayamam.
Bir metot içinde tanımlanan değişkenlerin ilk değerlerini manuel olarak vermeyi alışkalık haline getirin. Çünkü programın rahatça işlenebilmesi ve kullanılabilmesi içinidr. 

👋 57 - Değişken Davranışları Genel Bakış - Ref İçin Farkındalık 

int a = 5 olsun, stackte tutulur. Ramde veri türüne göre alan tahsis ediliyor ve bulunduğu alana göre veri tutuluyor. Ramde verilerimiz olucak ve biz yazılımcı olarak rame doğrudan pointer ile doğrudan erişebiliyoruz, ancak diğer değişkenlerle doğrudan bellek adresine erişemiyoruz. Ram bellekten değişkeni alırız/işleriz/kullanırız işte bu süreçte davranışsal olarak değişkenler isimleri üzerinden hareket ediyor.

Bir değişkenin ismini assign operatörünün solunda çağırırsak farklı davranış, sağında çağırırsak farklı davranış sergiliyor. Solundaysa, değişkenin kendisini yani bellek adresini bellekteki o kısmı o alanı getirir. Dolayısıyla o kısma bir atama işlemi yapabilirsin. Sağındaysa, değişkenin değerini getirir. 

👉 ! Sol tarafta: Bir değişkenin ismi, bellek adresini işaret eder. Bu, değişkenin hangi bellek bölgesinde saklandığını belirtir ve bu bölgeye yeni bir değer atama işlemi yapılabilir.

👉 ! Sağ tarafta: Değişkenin ismi, bellekte saklanan değeri getirir. Bu, değişkenin içindeki gerçek veriyi kullanmak için gereklidir.

X(a), bu metotta a'ya değişkenin değeri gelecek. Parametre, fonksiyonun parantezinin içini ifade eder.

Değişken davranışında değişkenin kendi gitmesi ve değerinin gönderilmesi farklı şeylerdir. 

👋 58 - Değişkenlerin Faaliyet Alanları - Scope Kavramı 

Scope, faaliyet alanı, kapsamdır. Değişken ve fonksiyonların erişilebilirlik sınırlarını belirleyen alandır. Tanımlamalarda ve algoritmik çalışmalarda karışıklığı önleyen bir sınır çizer. C#'ta "{}" ile ifade edilir. 
Scope içinde tanımladığım değişkene o scope içinde her yerde erişebilirim. Ayrıca bir scope içinde tanımlanan başka scopelar olursa yani scopelar iç içeyse yine erişim olur. Ama bir scope dışında farklı bir scope tanımlanırsa/farklı iki scope için erişim olmaz.

![58](https://github.com/user-attachments/assets/4f0971be-13d8-454d-bdff-0544f4922640)

Bir scope içinde aynı isimde birden fazla değişken olmaz ama farklı scopelarda aynı isimde değişkenler olabilir. Bu scopelar farklı threadlerde işlenir yani iki scope'nda işleri başkadır.

![58-2](https://github.com/user-attachments/assets/d1d8aa6e-8b8b-45d4-a771-0b08bbbb2e0f)

![58-3](https://github.com/user-attachments/assets/f992dcb5-ccc0-40e6-b63b-8d2ef794fb03)

👋 59 - Custom Scope Oluşturmak

Kendimizde scope oluşturabiliyoruz. Kodun içinde metodu faaliyet alanlarına bölebiliyoruz. İstediğiniz kadar Custom Scope oluşturabilirsiniz. {{{{{}}}}} 

👋 60 - Değişmezler/Sabitler/Const

Yazılımda verileri doğru bir şekilde işleyip sonuç elde etmeye çalışıyorduk. İşleyeceğimiz veri her zaman değişiklik gösterebilir ama bazen sabit değerlerle de çalışmamız gerekebilir. Yani sabit değişkenlerin değerlerinin değişmemesi gerekir. Süreçte var olan değişken değiştirilmez, değiştirilmeye çalışılırsa compiler hatta verir. 

Const,
Constanttan gelir.
Tanımlama aşamsındayken değerini atamak zorundasın.
Değişmeyendir fakat  istenildiği kadar okuanbilir/değerleri elde edilebilir.
Prototip olarak değişkenlere çok benzer fakat davranışsal olarak değeri bir daha değiştirilemez. 
Özünde static yapılanmadır.
Bir const tanımlandığında STACK'te ilgili türde alan tahsis edilecektir ve ilk atanan değer dışında bir daha değer kabul etmeyecektir.

✨ Static 
Uygulama bazlı veri depolayabildiğimiz bellekte bir alandır. Static dedğişkenlerde uygulamanın her yerinden erişim sağlayabilirsin. Evrenseldir yani. Static'i bilmek için diğer alanları da bilmek gerekiyor. Stack, heap ve static gibi bellek alanlarına sahiptir. Şimdi scopelarda tanımladığımız yerden erişilebilir demiştir ama staticte öyle değil.

✨ Static İle Const Arasındaki Fark Nedir ? 
Static değişkenler adı üstünde değişkendir, değerleri değiştirilebilir ama consttların değeri değiştirilemez. Constlar statictir ama sabit olan statictir. Her yerde erişirsin ve değerini değiştiremezsin. Yapısal olarak static bellek alanında tutulur. 

✨Readonly
Sadece okunabilir değişkenler tanımlamaktadır. Atanan değer bir daha değiştirilemez. 

✨ Const ve Readonly Arasındaki Fark Nedir ?
Consttan farkı sadece tanımlandığı yerde değil, ayrıca constructor içinde de değeri atanabilir. Dependency injection deseninde çok sık tercih edilir. Yani tanımlama anında yada constructorında atama yapabilirsin. Ama consstta öyle değil sadece tanımalama aşamasında atama yapabilirsin ve readonly static değildir. 

Const tanımlamada "const degisken_turu degisken_adi = değeri;" şeklinde tanımlama yapılır. 
Aslında normal bir şekilde de değişkeni bir kere tanımlayıp kullanabiliriz ama insan hali yanlışlıkla değerini sonradan değiştirebiliriz işte bunun önüne geçebilmek için değişmezleri const keywordü ile işaretleriz. 

👋 61 - Global Değişkenler

Konumlandırıldığı yere göre bir değişken ya global olur yada local olur. Yapısı, işleyişi yada sorumluluğu değişmiyor sadece adı değişiyor.
Bir değişken class scope'u içinde tanımlanıyorsa buna global denir. Metotlar içinde tanımlamaya ise local denir. Scope'lara göre düşünerek local/global diyebilirsin.

👋 62 - Değişken Tanımlama Varyasyonları 

İki tane değişken tanımlama varyasyonu vardır. İlki değişkeni tanımlayıp ister o an istersen daha sonra değer atayabilirsin. 
int a = 5;
int b = 14;

İkinci varyasyon, aynı türden birden fazla değişken oluşturulacaksa eğer bu değişkenlerin tek imzada tanımlanabilmesidir. 
int a = 5, b = 14; şeklinde tanımlama yapılabilir. İstersek değer attanmadan sadece tanımlamada yapılabilir. 

int a, b; gibi. Burda dikkat edilmesi gereken husus aynı türden olmaları gerekmektedir.

👋 63 - Değişkenler Arası Değer Atama Durumları - Deep Copy

Değişkenler arasında değer atama durumlarında veri açısından davranışın nasıl olduğunu inceleyelim.
Değişkenler arasında değer atanırken, değerler birbirine atanırken, bir değişkendeki değer bir başka değişkene atanırken, burada verisel açıdan nasıl bir davranış sergilenir onu inceleyeceğiz.
Değişkenler arası değer atanırken verisel açıdan iki davranış söz konusudur. Deep copy(klonlayıp, tekrar edip yeniden oluşturma) ile yapılabilir yada shallow copy(yüzeysel kopyalama) dediğimiz atama yapılabilir.

✨ Deep Copy

![63-1](https://github.com/user-attachments/assets/fb23a521-8479-4dee-8621-e3f64c18ef3a)

![63-2](https://github.com/user-attachments/assets/4992e69a-b019-4f6c-8e46-134b28ef88ad)

Var olan veriyi derinden kopyalıyor, klonluyor. Eldeki veri çoğalıyor. Eldeki veri birken iki oluyor. 

👉 ! Değer türlü değişkenler birbirine atanırken default olarak deep copy geçerlidir. Yani veri otomatik olarak üretilir. int decimal bool vs. gibi türlerde birbirine atama durumları olursa deep copy ile olur. 

Şimdi klonlama durumunun gerçek olup olmadığını nasıl inceleyeceğiz.
int a = 5;
int b = a;
a = a * 5;
Console.WriteLine(a);
Console.WriteLine(b); 
a'da yaptığın değişiklik b'ye yansımayacaksa deep copydir.

👋 64 - Değişkenler Arası Değer Atama Durumları - Shallow Copy

Davranış olarak biraz daa gelişmiş bir yapılanmadır. Aslında referansı kopyalıyoruz. Değişkenler arası değer atamalarında değeri türetmek/çoğaltmak/klonlamak yerine var olanı birden fazla referansla işaretlemeye dayalı kopyalama yöntemidir. 
Stackteki değişkenler heap'teki değeri işaretliyorsa, bu yüzeysel kopyalamadır.

![64-4](https://github.com/user-attachments/assets/04313dec-d607-45e9-a285-1dc472b1bf17)

👉 ! Default olarak shallow copy, referans türlü değişkenlerde geçerlidir. 

Bellekte birden fazla referansın tek bir veriyi işaret etmesi durumunda değişkenler/referanslar kendi aralarında shallow copydir. 
Sonuçta ilgili değer bir değişikliğe uğradığında, değeri işaretleyen tüm referanslara bu değişiklik yansıyacaktır. 

Normalde değer türlü değişkenler default olarak deep copy edilirler. İleride "ref keywordü" incelenirken, değer türlü değişkenlerde shallow copy nasıl yapılır bunu inceleyeceğiz.
Shallow copy, oop derslerinde ele alacağımmız üzere nesne ve referans arasındaki ilişkide varsayılan davranış olarak kabul edilir. Oop'de nesneler için varsayılan olan shallow copyin haricinde deep copy nasıl yapılır bunu inceleyeceğiz. 

👉 ! Deep copy değer türlü değişkenlerde varsayılandır. Shallow copy referans türlü değişkenlerde varsayılandır. 

👋 65 - Object Türü

Object Nedir ?
Şimdi ben bir değer tutacağım ve bu değer türüne uygun değişkende tutulmalıdır. Örneğin 3 int de, ahmet stringte, a da charda tutulmalıdır ama ben bunların hepsini "object" türünde de tutabilirim.

👉 ! Object, tüm türleri (değer,referans) karşılayabilen bir türdür. Peki neden karşılayabilyor ?
Bütün türler varsayılan olarak objectten türerler. 

![65-1](https://github.com/user-attachments/assets/e6aafdfc-ae74-4e93-a037-52f2373189a6)

Görsele göre string de char da objectte tutulabilir. Object türlerin ademidir, ilkidir, hiçbir tür yokken object vardı. Bu yüzden tüm türleri karşılayabilir. Object, kısaca verilen değeri karşılayabilen türdür. 

👉 ! Object, referans türlü bir değişkendir. Fakar değer türlü değerleri de karşılayabilir. 

Objectte bir değer atandığında nasıl davranış sergiler ?
Object değişkenler, ilgili verileri ramde object türde tutarlar. Fakat verinin öz türünü de içinde bozmadan saklarlar. Yani object içindeki veri, kendi öz türünde tutulur. 

![65-2](https://github.com/user-attachments/assets/e5065024-79f8-4bb2-af1c-5c0d3c460dbd)

Şarap örneği, dışarıdan object görünüyor ama içinde string. Bu durumda, object içindeki veriyi kendi türünde elde edebiliriz anlamına gelir. İşte objectteki bu özelliğe boxing denir. 

👉 ! Boxing, veriyi object içine koymaktır, kutulamaktır. O veriyi object içinden kendi türünde çıkartmaya da unboxing denir.


👋 66 - Object Türü - Boxing

Object türdeki bir değişkene herhangi bir türdeki bir değeri göndermektedir. 

int yas = 23;
object  _yas = 23;

ilk tanımlamada stackte int türünde tutulacaktır. Ama ikinci değişken tanımlamda object türü içinde int tutuluyor.

Boxing işlemi sonucunda ilgili değer object türü içinde kendi türüyle tutulur. Fakat "_yas" değişkeni artık 23 değerini bizlere object türde getirecektir. 

👉 ! Dikkat ederseniz object türde elde edilen değer üzerinde türüne özgü işlemler gerçeklştiremezsiniz. Örneğin, sayısal bir değer varsa o değer object olarak geleceğinden dolayı matematiksel işlem yapamazsınız.

👉 ! Object bir değişkenin içindeki değer üzerinde türe özgü işlemler yapabilmek için o objectin içindeki değeri, kendi türünde elde etmemiz gerekir. İşte bu işleme unboxing denir.

👉 ! Herhangi bir değer object türe assign ediliyorsa eğer, bu işlem kesinlikle boxingdir.

👋 67 - Cast Operatörü

Boxing edilmiş bir veriyi (objecte dönüştürülmüş, objecte set edilmiş, assign edilmiş bir veri) kendi türünde elde etmemizi sağlayan bir operatörüdür. 

Tür dönüşümlerinde bilinçli tür dönüşümü konusunda cast operatörü kullanılacaktır. Ayrıca kalıtsal durumlarda dad karşımıza çıkacaktır. 

Cas operatörü "()" dir. Cast operatörü parantezdir ve yanına object değeri alır.

Cast operatörü,, object olan değişkenin solunda o objectin hangi türe unboxing etmek istiyorsak parantez içinde hedef türü bildirerek kullanırız. Örneğin,
int yas = 5;
object _yas = a; // boxing
(int)_yas; // unboxing - cast operatörü _yas değişkeni/objesi içindeki değeri bana int olarak vermektedir.

👋 68.1 - Object - Unboxing

Unboxing, boxing edilmiş bir değeri kendi türünde objectten çıkartmaktır.

objectt _yas = 28;
_yas * 5; yaptığımızda hata verir. Çünkü biri int diğeri objecttir. Bu işlemi gerçekleştirebilmem için object'i int'e çervirmem gerekiyor. Burada (int)_yas; şeklinde cast edersek/çıkarırsak/unboxing yaparsak artık elimizde int türüne ait bir veri olmuş olacak ve değeri int değişken türüne atayarak matematiksel işlemelri gerçekleştirebiliriz. int __yas = (int)_yas;

✨ Şimdi 28 değerini int'e atayabilirken neden object'e atadık ?

Bazen sınıflarda/metotlarda yada yapmanız gereken tasarımlarda object kullanmanız gerekebilir. Çünkü gelecek verinin türünü bilemeyebilirsiniz. İşte oradaki türü bilemediğimiz için object ile karşılayıp içeride yapacağın işlemler için onu türüne ayıklamak gerekir. 

👉 ! Unboxing işlemi esnasında boxing edilmiş tür ne ise onu bildirmemiz gerekir. 

👋 68.2 - Object - Unboxing

Eğer int türünde veriyi string olarak cast etmeye çalışırsan program patlar.

int _yas = 5;
string yas = (string)_yas; kod semantik açıdan doğru olduğu için hata vermez gibi görünüyor ama compiler edilip runtime kısmına gelince boxing unbozing işlemi yapıldığında orada kod patlar.

👋 69 - C# Var Keywordü Nedir - Ne İşe Yara ? 

"var" bir değişken değil, bir keyworddür ve belli işlemi yapan keyworddür.

Eğer, tutacağın değere göre değişkenin türünü compiler'a belirletmek istiyorsanız var kwyeordü kullanabilirsiniz. 

"var" keywordü, kendisine atanan değerin türüne bürünür.

bool medeniHal = true;
var medeniHal = true; şeklinde tanımlamada yapılabilir. Burada true bool olduğu için var bool türüne bürünecektir.

👉 ! var keywordü, compiler tarafından değerin türüne göre otomatik büründürülen bir keyworddür. Fakat bir tür değildir. Genellikle, yazacağımız değişkenlerin türlerini yazmaktan üşendiğimiz için kullanırız. Halbuki, esasen farklı diller arasında desteklenmeyen türlerdeki verileri karşılayabilmek için oluşturulmuş, ortak bir keyyworddür. 

👉 !  var, diller arasındaki entegrasyonda kullanılıyor.

var keywordü ile tanımlanan değişkenin değeri tanımlama aşamasında verilmeli ki türü belirlenip direkt ona dönüşebilsin ve o türde davranış sergilesin.

👉 ! var keywordüyle tanımlanan değişkene ilk değer verildikten sonra o değerin türüne bürüneceği için sonraki durumlarda değeri farklı türde verilmez. 

✨ Var - Object Arasındaki Fark 

var x = 5;
object y = 15;
var stackte int türünde tutulur. Birinde unboxing boxing işlemi olur diğerinde olmaz. Yani var bir keyword iken object bir türdür. "var" atanan değerin türüne bürünürken, "object" atanan değeri boxing ederek objecte dönüştürür. 

✨ Var Bellek Yapısı 

var anahtar kelimesi, bellek yapısı açısından özel bir yapı oluşturmaz; sadece değişkenin türünü belirlemenin daha kısa bir yoludur. Derleyici, türü belirlediğinde, bu türün bellek yapısı normalde nasıl ise aynı şekilde bellek yönetimi yapılır.

👋 70 - C# Dynamic Keyword Ne İşe Yarar Nedir ? 

var a = 5;
var'a çok benzer, var'ın runtime'daki versiyonudur.
var'da compiler sürecindeyken dönüşüm olur.
dynamic b = 14;
dynamic compiler sürecindeyken hala dynamictir. Ne zamanki program çalıştırılıp runtime olursa o zaman ilgili değerin türüne bürünür. b int olur yani. Dynamic olan değişkenin türü belli olmadan değişkeni çağırırsan herhangi bir şekilde metottaki bir veriye erişemezsin. Çünkü gelecek olan memberları bilmiyorsun/göremiyorsun.

var da tanımlama aşamasında ilgili değerin türüne büründüğünden dolayı, sonradan değeri değiştirilmek istenirse türe uygun olarak değer verilmelidir. Dynamic'te ise, runtime da tür belirlenir ama kararlı davranmaz. Yani dynamic'te önce string sonra int double vs. olabilir.

✨ Dynamic Nerelerde Tercih Edilir ?

Türünü bilmediğimiz uzaktan veri geldiğinde kullanılır, var ile karşılayamayız çünkü.
