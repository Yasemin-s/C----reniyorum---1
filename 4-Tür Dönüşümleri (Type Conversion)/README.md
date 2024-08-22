👋 77 - Tür Dönüşümü Nedir ? Neden Verilerin Türlerini Değiştirmek/Dönüştürmek İsteriz ?

Elimizde t1 türünde n değeri olsun biz bunu yazılımda t2 türünde bir değişkene dönüştürebiliyoruz. Yazılım sürecinde elimizde bulunan değerlerin türlerini değiştirebiliyoruz. 

✨ Neden Verilerin Türlerini Değiştirmek/Dönüştürmek İsteriz ? 

Elimizde bir elma var ve ben bu elmayı elma türünde de tutabilirim meyve türünde de tutabilirim. Yani değeri genişleterek de daraltarakta tutabilirim bir objectte de tutabilirim. 

Örneğin, string a = "123"; varsa ve ben bunun üstünde sayısal işlem yapmak istiyorsam bunun için tür dönüşümü yaparım. int short byte vs dönüştürebilirim.
Örnek, farklı servislerden gelen değerleri uygun türlere dönüştürmek isteyebiliriz. 
Örnek, int a = 50; bununla büyük işlemler yapacaksak, double da vs. tutabiliriz. 

👉 ! Dikkat, tür dönüşümlerinde amaç türü dönüştürmek, değeri değil. Yani eldeki veriye uygun türe geçiş yapmaktır. Eldek veriyi uygun olmayyan bir türe dönüştürmeye çalışırsan bu hata verir. Elmayı meyveye dönüştürebilirsin ama elmayı armut yapamazsın. Amaç, veriyi dönüştürmek değil o veriyi karşılayabilecek farklı bir türe dönüştürmektir. 

👉 ! int a = 123; değeri char'a dönüşebilir, istisnadır. 

👋 78 - Metinsel İfadelerin Diğer İfadelere Dönüştürülmesi - Parse Fonksiyonu

Elimde stirng a = "123"; olsun, buu diğer türlere iki şekilde dönüştürebilirim. Parse metodu yada convert fonksiyonlar ile bu işlemi gerçekleştriebilirim. 

Parse metodu, sadece string dataları hedef türe dönüştürürken kullanılır. Yani string üstünde dönüşüm yapmak istersen kullanırsın. Örnek type.Parse(...); ile dönüşüm yapabilirsin. Buradaki type(int, short, long, doouble vs. olabilir.)

string a = "12"; olsun bunu int.Parse(a); yapabilirim.

👉 ! Parse dönüşümü runtime da olur. 

👋 79 - Metinsel İfadelerin Diğer İfadelere Dönüştrülmesi - Convert Fonksiyonları

Her türü farklı türe dönüştürmede convert fonksiyonu kullanılır, parse gibi illa string türlerle çalışmaya gerek yoktur. Sadece tür dönüşümünün değere uygun olması gerekir. 
Örnek, stringg x = "3";

👉 ! Convert, dediğimde to ile başlayan bütün fonksiyonlar convert işlemine giriyor. 

![79-1](https://github.com/user-attachments/assets/59968fe9-75b8-44e3-801e-16c209ac0e9c)

Yine aynı şekilde türüne uygun veriyi dönüştürmen gerekir. 

👋 80 - Diğer İfadelerin Metinsel İfadelere Dönüştürülmesi

İki farklı şekilde olabilir, convert fonksiyonu yada ToString fonksiyonu ile. 
int a = 3;
string d = Convert.ToString(a);

ToString fonksiyonu ile daha hızlı dönüşüm sağlayabiliriz. Genelde metinselden diğerine doğru değilde diğerlerinden metinsele doğru dönüşüm olduğu için daha hızlıdır. 
float f = 23;
string f3 = f.ToString();

👉 ! ToString fonksiyonu tüm ama tüm türlerde mevcuttur.

👋 81 - Sayısal İfadelerin Kendi Aralarında Tür Dönüşümleri 

![81-1](https://github.com/user-attachments/assets/bb5485e2-189a-440f-aade-08e78bf05d65)

Bir veriyi kendisinden üst olan türe dönüştürüyorsanız buna bilinçsiz tür dönüşümü deriz. Örnek int türünde n değeri olsun bunu float double vs. yapabilirim.
Kendisinden daha alt dar alanlı bir türe dönüşüyorsa, buna bilinçli tür dönüşümü deriz. Yine int türünde n değerinde olsun bunu short kapsıyor ama byte kapsamıyor olabilir. Yani değer dikkate alınarak tür dönüşümü yapılmalıdır. Dönüştürmek istediğim türe eldeki veri sığmayabilir ama ben buna rağmen dönüşümü yap dediğimde bilinçli bir şekilde tür dönüşümü yapmış oluyorum. 

👉 ! Compiler bilinçsiz tür dönüşümünü ben hallederim diyor.Herhangi bir türdeki sayısal değeri kendisinden büyük olan sayısal değere dönüştürme yaparken bunun sorumluluğunu üstleniyor ama elimizdeki bir sayısal değeri kendisinden küçük olan sayısal değerlere dönüştürürken Compiler orada veri kaybı ihtimali olduğu için bu riski/sorumluluğu almıyor. Taşın altına elini sokmuyor. Sen kendi iradenle karar ver diyor. İşte buradaki karar durumu da bilinçli tür dönüşümü oluyor.

✨ Bir sayısal türün alt türüne veriyi dönüştürdüğünde eğer ki veri o alt türün değer aralığında değilse ne olur ? 
Veri kaybı olur.
Örnek 37000 olan int türündeki değeri biz byte'a dönüştürmek istiyoruz. Evet tür dönüşümü olur ama veri kaybı olur, veri kaybı da şu şekilde olur. 0-255 yani 256 tane alan olduğu için eldeki veriyi yani 37000'i sürekli 256'ya bölecek yani 256 modunu alacaktır ve kalanı son değer olarak byte'a yazacaktır. 

![81-2](https://github.com/user-attachments/assets/2fa38b84-fdf5-493b-8da2-487259655d0c)

👋 82 - Bilinçsiz Tür Dönüşümü - Implicit Type Conversion

Elimizde bulunan sayısal ifadenin, bulunduğu türden daha geniş bir değer aralığına sahip olan türe dönüştürülürken buradaki sorumluluğu compiler alır. 

int a = 3000;
float _a = a; burada tür dönüşümü oldu, bizim kararımızla/bilincimizle yyaptığımız bir dönüşüm değil, compiler bunu kendisi algıladı. 

Bir sayısal türün kendisinden daha geniş aralıkta bir başka sayısal türe atanması bilinçsiz bir dönüşümdür. 
short x = 123;
long y = x; burda da bilinçsiz tür dönüşümü oldu compiler tarafından. 

👋 83 - Bilinçli Tür Dönüşümü - Explicit Type Conversion

Elimizdeki sayısal ifadeyi kendisinden daha dar daha küçük alana sahip olan türe atamak istediğimizde compiler veri kaybı olabileceğinden sorumluluk almıyor, buna sen karar ver diyor. 

✨ Bilinçli Tür Dönüşümü Nasıl Yapılır ?

Cast operatörü ile yapılır.
Boxing işlemlerinde tanıştığımız cast operatörü bilinçli tür dönüşümlerinde sayısal türleri kendi aralarında dönüştürüken iradeli bir şekilde yapılmasını sağlayan operatördür. 

int x = 3000;
short y = (short)x; bilinçli şekilde tür dönüşümü yaptık. 

👋 84 - Bilinçli Tür Dönüşümü - Kritik Yapalım

int a = 3000;
short s = (byte)a;
Normalde int değişkenini kendisinden daha küçük değer aralığına sahip olan türe cast etmişler. Burada bilinçli tür dönüşümü vardır. 

👋 85 - Checked Bloğu İle Bilinçli Tür Dönüşümü Kontrolü

👉 ! Checked komutu bilinçli tür dönüşümü yapılırken, eğer veri kaybı söz konusu ise runtime da hata fırlatılmasını sağlar. 

Checked{
//veri kayybı söz konusu oalbilecek dönüşüm buraya yazılır. 
}

![85](https://github.com/user-attachments/assets/c9306392-89e2-4073-8de1-a4456b63f937)

![85-2](https://github.com/user-attachments/assets/317e588f-acd0-427e-9518-f60e57fab760)

Checked bloğu kullanmadan program çalıştırılırsa, program çalışır ama veri kaybı olur. Checked bloğu olursa program çalıştırılır veri kaybı durumu olduğu anlaşılırsa/olursa devam etmez yyani işlemler gerçekleştirilmeden runtime da bizi uyaracak olan bir kontrol mekanizmasıdır. 

👋 86 - Unchecked Bloğu İle Bilinçli Tür Dönüşümü Kontrolü

Unchecked, bilinçli  tür dönüşümleride veri kaybı söz konusu ise bunu görmezden gelir ve runtime da hata vermez. Normal bir kod bloğu default olarak zaten unchecked'dır. 

![86](https://github.com/user-attachments/assets/232a399b-d902-4b41-b00c-599a75de05ba)

👋 87 - Bool Türünün Sayısal Türe Dönüştürülmesi

İki tane özel tür arasında dönüşüm vardır. 
(bool ile int) ve (char ile int) arasında yapılır.
Eldeki mantıksal bir değeri true yada false'u herhangi bir sayısal değere convert edersek ilgili değerin mantıksal karşılığını elde edebiliriz. 
bool b = true;
int i = Convert.ToInt32(b); // long i = Convert.ToInt64(b); //short i = Convert.ToInt16(b); // decimal i = Convert.ToDecimal(b); 
Console.WriteLine(i); 

True 1 , false 0 olarak int'e dönüşür. İlla bool ve int arasında olacak diye bir şey yok, bool ve long arasında da yaptık. 

👋 88 - Sayısal Türlerin Bool Türüne Dönüştürülmesi

Elimizdeki herhangi bir sayısal ifadeyi bool'a dönüştürebiliriz. Biz hep şunu dedik, tür dönüşümünde eldeki veriyi karşılayabilecek olan türe dönüştürmemiz gerekir diye.
int i = 1;
bool b = Conevrt.ToBoolean(i);
Console.WriteLine(b);
Burada i, 0 ve 1 olursa duruma göre true yyada false olur. Peki i 23452 gibi bir sayı olursa ne olur ? Burada bool true döner bu bir istisnadır. Yani 0'ın haricinde bize hep true döner. -23 versem bile yine true dönecektir. 

👋 89 - Char Türünün Sayısal Türe Dönüştürülmesi (Ascii)

Klavyedeki her bir karakterin aslında arka planda tam sayı karşılığı vardır. Bu sayısal değerlere ascii kaynak kodu denir.

Biz "a" yazmaya çalıştığımızda aslında bilgisayar onu ascii tablosuna göre 97 algılıyor olarak düşünebilirsiniz.

![89-1](https://github.com/user-attachments/assets/fdefa14c-ac1b-4c56-b0fb-ea4e5aaaa9ed)

Bir karakteri int'e cast edersek, eldeki karakterin ascii kaynak kodunu bize verir. Bir int'i char'a cast edersek eldeki int'e karşılık gelen char'ın karakterini verir.

Ascii tablosunda olan sayılar için dönüşüm olursa karakterler verilebilir. Tabloda olmayan sayısal karakteri olmadığı için "?" döner. Ayrıca özel karakterler ve diğer tuşların da tab, null vs. karşılıkları vardır. 

👉 ! Dikkat edilmesi gereken bir diğer nokta ise sadece int'de değil aynı zamanda double vs. gibi tüm sayısal türler için bu işlemler geçerlidir.

👉 ! Klavye üzerindeki bütün tuş kombinasyonlarının esasında arka planda bir ASCII kaynak kodu vardır.

👉 ! Cast operatörü duruma ve bulunduğu yere göre farklı davranış/sorumluluk üstleniyor.

👋 90 - Sayısal Türlerin Char Türüne Dönüştürülmesi

int oAscii = 111;
int OAscii = 79;
System.Console.WriteLine((char)oAscii);
System.Console.WriteLine((char)OAscii);
