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





👉 ! 
