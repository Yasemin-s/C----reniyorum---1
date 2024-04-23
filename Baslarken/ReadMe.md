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
Ccross platform desteği sunarak tek bir işletim sistemine bağlı kalmaz. . Windows, macOS ve Linux gibi çeşitli işletim sistemlerinde geliştirilip, çalıştırılabilir. 
Açık kaynak kodludur ve bu gelişimine büyük katkı sağlamıştır. Daha sık güncellemeler alıp hızlı yenilikler sunar.
.Net Core daha sonradan çıkmıştır.
Küçük, modüler bir frameworktür. Uygulamaya ihtiyaç duyulan bileşenler eklenir.
Bulut uygulamaları, mikro hizmetler ve modern web uygulamalrı gibi yeni ve dağıtık sistemler için daha uygundur.

.NET Core: .NET Core, C# dışında F#, Visual Basic ve diğer dilleri de destekler. Ayrıca .NET Standard sayesinde .NET Framework ile uyumlu kütüphaneleri kullanabilir.

.NET 5 ve Sonraki Sürümler,
.NET 5, .NET Core ve .NET Framework'ün birleştirilmiş bir sürümüdür. 
Tek bir .NET platformu sunar ve .NET Core ile .NET Framework arasındaki farkları ortadan kaldırır. 
.NET 5 ve sonraki sürümler, .NET'in gelecekteki evrimini temsil eder ve tüm .NET uygulama geliştirme ihtiyaçlarını karşılamak için tasarlanmıştır.

4 - Compiler Nedir ? 

Bir programlama dili derlenecek şekilde çalışıyorsa önce derlenmesi sonra çalıştırılması ve ekranda sonucun gösterilmesi gerekecektir.

Compiler(derleme) işlemi, yazılan kodların makinenin/pc' nin anlayacağı/okunacağı/işleyebileceği ara dil formatına/koduna çevrilmesidir. 
 ! Dikkat edilmesi gereken nokta, kodların 0 ve 1 lere dönüştürülmesi değil, ara dil formatına(assembly, ... gibi) çevrilmesidir.

Kullanıcının çalıştırabileceği yazılım uzantısını derleme sonucunda elde edersiniz. Yani yazmış olduğun C#'taki kodu kullanıcının işletim sisteminde çalıştırılabilir hale getirmen için o kodu derlemen gerekir.

Compiler işlemi, editörler tarafından otomatik yapılır ve geriye "exe"" ve "dll" olarak iki şekilde çıktı döner. Bu dosyaların çalıştırılması ile kodların çıktıları ekranda gösterilmiş olur.

"exe" uzantılı dosyalar kullanıcının çalıştırabileceği dosya tipleridir. "dll" uzantılı dosyalar ise başka bir yazılım tarafından kullanılmasına/çalıştırılmasına imkan verir.

5 - Kodlar Nasıl Compile Edilir ? 

Kodların compile edilme süreci editörler tarafından otomatik yapılmaktadır. İstersek manuel oalrak da derleme yapılabilir. 
Developer Command Prompt sayesinde .net türevlerinden biriyle yazılan kodların barındığı dosyalar derlenir. 

Yazdığımız kodlar derlenmediği sürece kullanılabilir hale gelmez. Kullanılabilir hale gelmesi için kodun derlenip çalıştırılması gerekiyor. Kodların derlenip çaıştırılma süreci manuel olarak değil, kullandığımız editörler yada .Net CLI dediğimiz yardımcı asistan sayesinde yapılabiliyor.

C# kodları, önce C# kaynak kodundan, C# derleyicisi tarafından makine diline daha yakın ara dil olan "Common Intermediate Language" (CIL) veya "Microsoft Intermediate Language" (MSIL) olarak adlandırılan bir ara dil/kod formatına derlenir. Bu ara kod daha sonra .Net Framework veya .Net Core gibi ortamlarda çalıştırılabilir hale gelmek üzere Just-In-Time (JIT) derleyici tarafından hedef makine diline (x86, x64) derlenir.

Örnek: 

![5-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/edc95a35-f8ed-43a8-87b9-159a249d15f3)

![5-2](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/084d54e6-cc5a-4744-af26-f78cd0a782fd)

![5-3](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/b46097f9-055f-481a-8991-e39826d5c08d)

![5-4](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/25a3b133-efa0-4582-8531-0eef1d5b8b51)

"csc" komutunun kullanılabilmesi için, Visual Studio veya .NET Framework SDK'sının yüklü olması gerekmektedir.

6- Visual Studio Ortamı 

Kompleks projelerde kod maliyetini düşürüp geliştirilmiş kod yazmamızı sağlayan yani developer sürecinde bizlere eşlik edebilecek belirli ortamlar kullanmak gerekir. Bu ortamlardan en yaygın olan Visual Studio' dur. 

Visual Studio, Microsoft tarafından developerlar için geliştirilmiş bir paltformdur. .Net miamrilerinin(.Net Framework, .Net Core, .Net 5 ve Sonraki Sürümler) hemen hemen hepsinin kodlanabileceği bir platformdur.

Visual Studio ortamında, akla gelebilecek her türlü çalışmayı geliştirebliriz. Mimariler, uygulamalar, programlar, tasarımlar...

Visual Studio da tek seferde derleme işlemi gerçekleştirilir. Derleme sürecini Visual Studio kendi sorumluluğunda dahili bir şekilde yapar.

Visual Studio ortamında üst menülerden debug, tools, solution explorer ve error list önemli ve kodlama sırasında sıklıkla başvurulacak kısımlardır.
Solution Explorer: Üzerinde çalışılan projenin tüm dosyalarının gösterildiği, listelendiği yerdir. 
Error List: Derleme sürecinde alınan hataalrın gösterildiği penceredir. Dolayısıyla bu pencerede gösterilen hatalar derleme hatalarıdır. 

  ! IDE ve Editör Farkı : 
    Editör, bir metin düzenleme aracıdır. Sadece metin dosyalarını düzenlemek için kullanılır. Gelişmiş programlama özelliklerine sahip değildir. Herhangi bir derleme veya hata ayıklama işlevi yoktur.  Notepad, Sublime Text, Visual Studio Code gibi.
    IDE(Entegre Geliştirme Ortamı), yazılım geliştirme ortamıdır. Gelişmiş programlama özelliklerine(derleme, hata ayıklama, kod tamamlama, proje yönetimi gibi birçok aracı içerir.) sahiptir. Programlama dili veya platforma özgü geliştirme araçları sağlar. Derleme ve hata ayıklama özellikleri sayesinde kodunuzu geliştirmek ve hataları düzeltmek için birçok araç sağlar. Visual Studio (C#, VB.NET gibi Microsoft teknolojileri için), Eclipse (Java için), IntelliJ IDEA (Java, Kotlin, vb. için) gibi.

7 - Project ve Solution Kavramları

Project, bir amaca dair yazılan çözümlerin kodlarını barıdırır. Kodsal çalışmaların yapıldığı(gerekli algoritmaların yazıldığı, mimarilerin oluşturuluduğu, veritabanı işlemlerini yapılması) bir bütündür.

Solution, İçerisinde birden çok proje barındırabilir. Evrensel bir kümedir.

![7-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/75c142d5-ef2a-4205-85b7-7efff28deb5d)

  ! Uygulama yazarken, yazdığımız uygulama bir proje değil aslında bir çözümdür. Dolayısıyla bir solution yani yapılacak uygulama birden fazla projenin bir araya gelmiş hali olabilir. 

Örneğin, bir banka uygulaması yapılacak olsun. Bu uygulama için ekibin bir kısmı bakiye projesinde , bir kısmı bankamatik ve başka bir ksımı da ERP kısmında çalışacak olsun. İşte bakiye, bankamatik ve ERP ksıımlarının  her biri ayrı bir proje olur. Ve bu ayrı projeler tek bir solution altında bulunacaktır. 










