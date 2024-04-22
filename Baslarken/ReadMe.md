2 - C# Nedir ? (klavyeyi fn + enter değiştiriyor.)
Orta seviyeli programlama dilidir. Orta seviyeden kastımız, kodların okunabilir ve anlaşılabilir olmasıdır. Kodlara bakıldığında bolca metinsel ifade yer alıyorsa, şiir gibi okuyabiliyorsan, beşeri dile yakınsa bu kodlar yüksek seviyeli bir dildir. Ama kodlara baktığında daha çok sembolik ifadeler yer alıyorsa, anlaşılması güçse bir mantığa/matematiğe dayalıysa bu kodlar düşük seviyeli kodlardır. 

Microsoft tarafından geliştirilmiştir. .Net çatısını kullanır. .Net, Microsoft'un developerların kullanacağı teknolojileri bu çatı altında toplar. Bu teknolojiler mimariler, kütüphaneler, programlama dilleri, frameworkler olabilir. 

Açık kaynak kodludur. Open source olması ile birlikte, herkes bu programlama dilinin kodlarına erişim sağlayabilir ve gelişmesine katkıda bulunabilir. 

OOP - object orianted programing i destekler. OOP, sınıf ve nesne arasındaki ilişkiyi açıklayan bir kavramdır. 

C# ile akla ne geliyorsa yapılabilir. Servis mimarileri, web, mobil, masaüstü programlar... 
  ! C# ile veri madenciliğide yapılabilir. Ama python bu konuda çok daha iyidir. Amaca uygun programlama dili seçmek daha doğrudur. 

C#, C benzeri bir dildir. C' nin bir üst versiyonu C++'dır. C++' ı n bir üst versiyonu ise C++++(# - diyez işareti) , C#'dır. 

Diller birbirlerini örnek alabilirler. Birbirlerinden beliril şeyleri kopyalayabilir/miras alabilir yada farklı vizyonda farklı ürünler ortaya koyabilirler. Kendisinin modellediğinin modellenmesine sebep olabilirler. Dillerin gelişimi işte bu şekildedir.

Derlenen bir programlama dilidir. Derleme, yazılan kodların makinenin anlayabileceği ara dil formatına çevrilmesidir. Editör tarafından otomatik yapılır. Derleme, proje bazlı(sadece ilgili projenin dosyaları derlenir.) yada solution bazlı(solution altında bulunan tüm projeler derlenir.) yapılabilir.

3 - .Net Framework ve .Net Core Nedir?  Farkları Nelerdir?
.Net, Microsoft'un geliştiriciler için sunmuş olduğu teknolojilerin bulunduğu bir çatıdır. Bu tekonlojiler, programlama dilleri, mimariler, kütüphaneler...
  ! İşletim sistemi .net çatısı altına girmez, çünkü geliştiriciler için değil son kullanıcılar için sunulmuştur. 
  ! Programlama dillerinde mimari, bir yazılım uygulamasının nasıl yapılandırıldığı, organize edildiğini ifade eder.
  ! Biz gerçek hayatta aslında uygulama değil çözüm yazıyoruz.
  ! .Net Core ve .Net Framework ifade etmede, yazılım geliştirme platformları yada çerçeve kelimeleri kullanılabilir.

.Net Framework,
Windows işletim sistemlerinde kodlanıp, çalıştırılabilen, kullanılabilen bir çerçevedir. 
Kapalı kaynak kodludur. Sadece Microsoft tarafından güncellenir ve genellikle büyük sürüm güncellemeleri alır.
İlk çıkan sürümdür.
Büyük monolitik bir frameworktür ve tam kurulum gerektirir.
Masaüstü ve web uygulamaları için daha yaygın kullanılır.

.Net Core,
Ccross platform desteği sunarak tek bir işletim sistemine bağlı kalmaz. Tüm işletim sistemlerinde geliştirilip, kullanılabilir. 
Açık kaynak kodludur ve bu gelişimine büyük katkı sağlamıştır. Daha sık güncellemeler alıp hızlı yenilikler sunar.
.Net Core daha sonradan çıkmıştır.
Küçük, modüler bir frameworktür. Uygulamaya ihtiyaç duyulan bileşenler eklenir.
Bulut uygulamaları, mikro hizmetler ve modern web uygulamalrı gibi yeni ve dağıtık sistemler için daha uygundur.

.NET Core: .NET Core, C# dışında F#, Visual Basic ve diğer dilleri de destekler. Ayrıca .NET Standard sayesinde .NET Framework ile uyumlu kütüphaneleri kullanabilir.

4 - Compiler Nedir ? 
Bir programlama dili derlenecek şekilde çalışıyorsa önce derlenmesi sonra çalıştırılması ve ekranda sonucun gösterilmesi gerekecektir.

Compiler(derleme) işlemi, yazılan kodların makinenin/pc' nin anlayacağı/okunacağı/işleyebileceği ara dil formatına/koduna çevrilmesidir. 
 ! Dikkat edilmesi gereken nokta, kodların 0 ve 1 lere dönüştürülmesi değil, ara dil formatına(assembly, ... gibi) çevrilmesidir.

Kullanıcının çalıştırabileceği yazılım uzantısını derleme sonucunda elde edersiniz. Yani yazmış olduğun C#'taki kodu kullanıcının işletim sisteminde çalıştırılabilir hale getirmen için o kodu derlemen gerekir.

Compiler işlemi, editörler tarafından otomatik yapılır ve geriye "exe"" ve "dll" olarak iki şekilde çıktı döner. Bu dosyaların çalıştırılması ile kodların çıktıları ekranda gösterilmiş olur.

"exe" uzantılı dosyalar kullanıcının çalıştırabileceği dosya tipleridir. "dll" uzantılı dosyalar ise başka bir yazılım tarafından kullanılmasına/çalıştırılmasına imkan verir.








