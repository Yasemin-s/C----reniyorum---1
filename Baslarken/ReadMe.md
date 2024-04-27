👋2 - C# Nedir ? (klavyeyi fn + enter değiştiriyor.)

Orta seviyeli programlama dilidir. Orta seviyeden kastımız, kodların okunabilir ve anlaşılabilir olmasıdır. Kodlara bakıldığında bolca metinsel ifade yer alıyorsa, şiir gibi okuyabiliyorsan, beşeri dile yakınsa bu kodlar yüksek seviyeli bir dildir. Ama kodlara baktığında daha çok sembolik ifadeler yer alıyorsa, anlaşılması güçse bir mantığa/matematiğe dayalıysa bu kodlar düşük seviyeli kodlardır. 

Microsoft tarafından geliştirilmiştir. .Net çatısını kullanır. .Net, developerların kullanacağı teknolojileri bu çatı altında toplar. Bu teknolojiler mimariler, kütüphaneler, programlama dilleri, frameworkler olabilir. 

Açık kaynak kodludur. Open source olması ile birlikte, herkes bu programlama dilinin kodlarına erişim sağlayabilir ve gelişmesine katkıda bulunabilir. 

OOP - object orianted programing'i destekler. OOP, sınıf ve nesne arasındaki ilişkiyi açıklayan bir kavramdır. 

C# ile akla ne geliyorsa yapılabilir. Servis mimarileri, web, mobil, masaüstü programlar... 

  👉 ! C# ile veri madenciliğide yapılabilir. Ama python bu konuda çok daha iyidir. Amaca uygun programlama dili seçmek daha doğrudur. 

C#, C benzeri bir dildir. C' nin bir üst versiyonu C++'dır. C++' ı n bir üst versiyonu ise C++++(# - diyez işareti) , C#'dır. "++", "+1" 'i ifade eder.

Diller birbirlerini örnek alabilirler. Birbirlerinden beliril şeyleri kopyalayabilir/miras alabilir yada farklı vizyonda farklı ürünler ortaya koyabilirler. Kendisinin modellediğinin modellenmesine sebep olabilirler. Dillerin gelişimi işte bu şekildedir.

Derlenen bir programlama dilidir. Derleme, yazılan kodların makinenin anlayabileceği ara dil formatına çevrilmesidir. Editör tarafından otomatik yapılabileceği gibi manuel olarak da yapılabilir. Derleme, proje bazlı(sadece ilgili projenin dosyaları derlenir.) yada solution bazlı(solution altında bulunan tüm projeler derlenir.) yapılabilir.

👋 3 - .Net Framework ve .Net Core Nedir?  Farkları Nelerdir?

.Net, Microsoft'un geliştiriciler için sunmuş olduğu teknolojilerin bulunduğu bir çatıdır dedik. Bu tekonlojiler, programlama dilleri, mimariler, kütüphaneler...

  👉 ! İşletim sistemi, .Net çatısı altına girmez, çünkü geliştiriciler için değil son kullanıcılar için sunulmuştur. 
  
  👉 ! Programlama dillerinde mimari, bir yazılım uygulamasının nasıl yapılandırıldığı, organize edildiğini ifade eder.
  
  👉 ! Biz gerçek hayatta aslında uygulama değil çözüm yazıyoruz.
  
  👉 ! .Net Core ve .Net Framework ifade etmede, yazılım geliştirme platformları yada çerçeve kelimeleri kullanılabilir.


.Net Framework,
Windows işletim sistemlerinde kodlanıp, çalıştırılabilen, kullanılabilen bir çerçevedir. 
Kapalı kaynak kodludur. Sadece Microsoft tarafından güncellenir ve genellikle büyük sürüm güncellemeleri alır.
İlk çıkan sürümdür.
Büyük monolitik bir frameworktür ve tam kurulum gerektirir.
Masaüstü ve web uygulamaları için daha yaygın kullanılır.


.Net Core,
Cross platform desteği sunarak tek bir işletim sistemine bağlı kalmaz. Windows, macOS ve Linux gibi çeşitli işletim sistemlerinde geliştirilip, çalıştırılabilir. 
Açık kaynak kodludur ve bu, gelişimine büyük katkı sağlamıştır. Daha sık güncellemeler alıp hızlı yenilikler sunar.
.Net Core daha sonradan çıkmıştır.
Küçük, modüler bir frameworktür. Uygulamaya ihtiyaç duyulan bileşenler eklenir.
Bulut uygulamaları, mikro hizmetler ve modern web uygulamaları gibi yeni ve dağıtık sistemler için daha uygundur.


.NET Core: .NET Core, C# dışında F#, Visual Basic ve diğer dilleri de destekler. Ayrıca .NET Standard sayesinde .NET Framework ile uyumlu kütüphaneleri kullanabilir.


.NET 5 ve Sonraki Sürümler,
.NET 5, .NET Core ve .NET Framework'ün birleştirilmiş bir sürümüdür. 
Tek bir .NET platformu sunar ve .NET Core ile .NET Framework arasındaki farkları ortadan kaldırır. 
.NET 5 ve sonraki sürümler, .NET'in gelecekteki evrimini temsil eder ve tüm .NET uygulama geliştirme ihtiyaçlarını karşılamak için tasarlanmıştır.


👋 4 - Compiler Nedir ? 

Bir programlama dili derlenecek şekilde çalışıyorsa önce derlenmesi sonra çalıştırılması ve ekranda sonucun gösterilmesi gerekecektir.

Compiler(derleme) işlemi, yazılan kodların makinenin/pc' nin anlayacağı/okunacağı/işleyebileceği ara dil formatına/koduna çevrilmesidir. 
 👉 ! Dikkat edilmesi gereken nokta, kodların 0 ve 1 lere dönüştürülmesi değil, ara dil formatına(assembly, ... gibi) çevrilmesidir.

Kullanıcının çalıştırabileceği yazılım uzantısını derleme sonucunda elde edersiniz. Yani yazmış olduğun C#'taki kodu kullanıcının işletim sisteminde çalıştırılabilir hale getirmen için o kodu derlemen gerekir.

Compile işlemi, editörler tarafından otomatik yapılır ve geriye "exe"" ve "dll" olarak iki şekilde çıktı döner. Bu dosyaların çalıştırılması ile kodların çıktıları ekranda gösterilmiş olur.

"exe" uzantılı dosyalar kullanıcının çalıştırabileceği dosya tipleridir. "dll" uzantılı dosyalar ise başka bir yazılım tarafından kullanılmasına/çalıştırılmasına imkan verir.

👋 5 - Kodlar Nasıl Compile Edilir ? 

Kodların compile edilme süreci editörler tarafından otomatik yapılmaktadır. İstersek manuel olarak da derleme yapabiliriz. 
Developer Command Prompt sayesinde .Net türevlerinden biriyle yazılan kodların barındığı dosyalar derlenir. 

Yazdığımız kodlar derlenmediği sürece kullanılabilir hale gelmez. Kullanılabilir hale gelmesi için kodun derlenip çalıştırılması gerekiyor. Kodların derlenip çalıştırılma süreci manuel olarak değil, kullandığımız editörler yada .Net CLI dediğimiz yardımcı asistan sayesinde yapılabiliyor.

C# kodları, önce C# kaynak kodundan, C# derleyicisi tarafından makine diline daha yakın ara dil olan "Common Intermediate Language" (CIL) veya "Microsoft Intermediate Language" (MSIL) olarak adlandırılan bir ara dil/kod formatına derlenir. Bu ara kod daha sonra .Net Framework veya .Net Core gibi ortamlarda çalıştırılabilir hale gelmek üzere Just-In-Time (JIT) derleyici tarafından hedef makine diline (x86, x64) derlenir.

Örnek: 

![5-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/edc95a35-f8ed-43a8-87b9-159a249d15f3)

![5-2](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/084d54e6-cc5a-4744-af26-f78cd0a782fd)

![5-3](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/b46097f9-055f-481a-8991-e39826d5c08d)

![5-4](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/25a3b133-efa0-4582-8531-0eef1d5b8b51)

"csc" komutunun kullanılabilmesi için, Visual Studio veya .NET Framework SDK'sının yüklü olması gerekmektedir.

👋 6 - Visual Studio Ortamı 

Kompleks projelerde kod maliyetini düşürüp geliştirilmiş kod yazmamızı sağlayan yani developer sürecinde bizlere eşlik edebilecek belirli ortamlar kullanmak gerekir. Bu ortamlardan en yaygın olanı Visual Studio' dur. 

Visual Studio, Microsoft tarafından developerlar için geliştirilmiş bir platformdur. .Net mimarilerinin(.Net Framework, .Net Core, .Net 5 ve Sonraki Sürümler) hemen hemen hepsinin kodlanabileceği bir platformdur.

Visual Studio ortamında, akla gelebilecek her türlü çalışmayı geliştirebiliriz. Mimariler, uygulamalar, programlar, tasarımlar...

Visual Studio da tek seferde derleme işlemi gerçekleştirilir. Derleme sürecini Visual Studio kendi sorumluluğunda dahili bir şekilde yapar.

Visual Studio ortamında üst menülerden debug, tools, solution explorer ve error list önemli ve kodlama sırasında sıklıkla başvurulacak kısımlardır.
Solution Explorer: Üzerinde çalışılan projenin tüm dosyalarının gösterildiği, listelendiği yerdir. 
Error List: Derleme sürecinde alınan hataların gösterildiği penceredir. Dolayısıyla bu pencerede gösterilen hatalar derleme hatalarıdır. 

  👉 ! IDE ve Editör Farkı : 
  
    Editör, bir metin düzenleme aracıdır. Sadece metin dosyalarını düzenlemek için kullanılır. Gelişmiş programlama özelliklerine sahip değildir. Herhangi bir derleme veya hata ayıklama işlevi yoktur.  Notepad, Sublime Text, Visual Studio Code gibi.
    
    IDE(Entegre Geliştirme Ortamı), yazılım geliştirme ortamıdır. Gelişmiş programlama özelliklerine(derleme, hata ayıklama, kod tamamlama, proje yönetimi gibi birçok aracı içerir.) sahiptir. Programlama dili veya platforma özgü geliştirme araçları sağlar. Derleme ve hata ayıklama özellikleri sayesinde kodunuzu geliştirmek ve hataları düzeltmek için birçok araç sağlar. Visual Studio (C#, VB.NET gibi Microsoft teknolojileri için), Eclipse (Java için), IntelliJ IDEA (Java, Kotlin, vb. için) gibi.

👋 7 - Project ve Solution Kavramları

Project, bir amaca dair yazılan çözümlerin kodlarını barıdırır. Kodsal çalışmaların yapıldığı(gerekli algoritmaların yazıldığı, mimarilerin oluşturuluduğu, veritabanı işlemlerini yapıldığı) bir bütündür.

Solution, içerisinde birden çok proje barındırabilir. Evrensel bir kümedir.

![7-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/75c142d5-ef2a-4205-85b7-7efff28deb5d)

  👉 ! Uygulama yazarken, yazdığımız uygulama bir proje değil aslında bir çözümdür. Dolayısıyla bir solution yani yapılacak uygulama birden fazla projenin bir araya gelmiş hali olabilir. 

Örneğin, bir banka uygulaması yapılacak olsun. Bu uygulama için ekibin bir kısmı bakiye projesinde , bir kısmı bankamatik ve başka bir ksımı da ERP kısmında çalışacak olsun. İşte bakiye, bankamatik ve ERP kısımlarının  her biri ayrı bir proje olur. Ve bu ayrı projeler tek bir solution altında bulunabilir. 

👋 8 - Visual Studio İle Proje Oluşturma ve Derleme
  
ilk olarak hangi projede çalışacağımız belirlenir. Platform önemli değildir. 

Visual Studio'yu açtığınızda "create a new project" diyerek proje oluşturma kısmına gidebilirsiniz. Açılan pencerede çözümünüzün kodlarını yazacağınız proje seçimi yapmanız gerekir.(Burada kullandığınız dil, platform, proje türleri ksıımlarını projenize uygun olark kişiselleştirip ilgili projeyi seçebilirisiniz.) 

  👉 ! Visual Studio'nun desteklediği dil,platform ve proje türleri:
  
![8-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/6e98fd64-8a35-41d8-babd-492dcd6e805c)

![8-2](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/ceff7a64-76ae-4418-87a5-06c9262cedcd)

![8-3](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/40c93ab9-0061-4ccd-8e7f-4577b1509d6d)

![8-4](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/b127d9dd-19af-4a61-8434-d654efc8c712)

Çalışılacak proje seçildikten sonra "Project name" (projenin adı, örneğin 7. kısımda verilen örnek için "Bankamatik" olabilir.), "Location" (bilgisayarınızda projenin depolanacağı, tutulacağı, saklanacağı yerdir/yoldur.), "Solution name" (ilgili projelerin tek bir çatı altında olduğunu ifade eden isimdir, yine 7. kısımdaki örneğe göre "BankaUygulaması" solution adı verilebilir.) kısımları doldurulur. 

Bir solution altında birden fazla aynı isimde proje adı bulunamaz. 
Solution name , evrenseldir. Altında bulunan projeler için daha genel bir isimdir. 

Visual Studio'da "Solution Explorer" altında projeler ve dosyaları görülür. 

Bir solutiona birden fazla proje eklemek için, "Solution Explorer" kısmında "Solution name" e sağ tıklanıp "Add > New Project" seçeneği seçilip projeler eklenebilir. 

Proje derleme kısmında ise, ister proje bazlı(sadece o projenin dosylarının derlenmesi), ister solution bazlı(solution altında bulunan tüm projelerin derlenmesi) yapılabilir. 

İlgili projeye sağ tıklandığında "build"(projeyi derler.), "rebuild"(derlenen dosyaları siler ve yeniden derler.), "clean"(derlenmiş dosyaları siler.) şeklinde derleme işlemleri gerçekleştirilebilir ve hatta bu işlemler görülebilir. Proje üstünde sağ tıklanıp "Open Folder in File Explorer" dendiğinde projenin kaynak dosyaları görülür. Kaynak dosyalar içinden "bin > debug > sürüm_dosyası" içine girilip "build","rebuild","clean" işlemleri gerçekleştirilerek silinen ve oluşan dosylar gözlemlenebilir. 

![8-5](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/b1dcfec9-b3ba-4bf7-9129-e222f1529c08)

![8-6](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/53badf31-0d0f-4449-807e-6622ac051e07)

Solution altında bulunan projelerden sadece biri yada duruma göre hepsi seçilip aynı anda çalıştırılabilir. Tek bir projenin çalıştırılması isteniyorsa, ilgili projeye sağ tıklanıp "Set as Startup Project", birden çok projenin aynı anda çalışması için herhangi bir çalıştırılmak istenen projeye sağ tıklanıp "Configure Startup  Projects..." açılan pencerede "Multiple startup projects" seçilip actionlar "start" yapılarak çalıştırılabilir. Bu şekilde seçilen proje/projeleri, ait olduğu solutionda başlangıç projesi yapmış oluyoruz. 

![8-7](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/973647b7-ef83-4107-93e2-73ffb14b6f95)

👋 10 -  Dotnet CLI Nedir ?

Command Line Interface(komut satır arayüzü).

.Net uygulamalarını geliştirirken bize eşlik eden bir komut satırı arayüzüdür. 

Programlama yaparken yazılan kodlara eşlik edecek, bize zaman ve maliyetten tasarruf yaptırmayı sağlyayacak bir asistana ihtiyaç vardır. Mesela bu asistan bize proje oluşturmada, paket güncellemelerinde .DotNet CLI ile yardımcı olabilir. 

.Net CLI, görsel grafik arayüz içermez, siyah ekrandır ve direkt konsoldan komutları/talimatları alır. Günümüz CLI yapılanmaları böyledir, siyah ekrandır. Çünkü kodların/komutların yazılacağı yer herhangi bir görsellik gerektiren bir yer değildir. 

  👉 ! .NET platformu uygulama geliştirmek için genel bir çatı sağlarken, .NET SDK, bu geliştirme sürecini yönetmek için gereken araçları içeren spesifik bir yazılım paketidir. NET SDK, derleyici (C# veya diğer diller için), runtime, kütüphaneler, hata ayıklama araçları, test araçları ve diğer geliştirme araçlarını içerir. .NET SDK, geliştiricilere uygulama oluşturma, derleme, test etme ve yayınlama gibi işlemleri gerçekleştirmek için gereken her şeyi sağlar.

👋 10 -  Dotnet CLI - Temel Komutlar ?

Bir program yazarken genellikle kullanacağımız temel/.NET CLI komutlarımız şunlardır:
help -> Dotnet CLI tarafından desteklenen komutlar hakkında ayrıntılı bilgi veren komuttur.
new -> Dotnet CLI üzerinden proje oluşturmada kullanılır.
restore -> Bildirdiğiniz/referans ettiğiniz paketleri uygulamaya yüklemek için uygulamayı restore etmek gerekir. Eğer restore işleminde belirtilen paket/kütüphane yoksa nuGet denilen havuzdan çeker/yükler. Kısaca harici paketleri sisteme yüklememizi sağlayan yapılanmadır.
build -> Proje önce restore edilir ardından bir sıkıntı yoksa proje derlenir. Derleme çıktısı "bin > Debug > net5.0" dizinine verilir.
publish -> Projeyi derleyerek yayınlanabilir dosyaları çıktı verir.
run -> Uygulamayı derler, ayağa kaldırır, çalıştırır.
dotnet run --no-build -> Uygulamayı derlemeden direkt ayağa kaldırır. Mevcut en son derlenmiş hali neyse uygulamayı onun üzerinden ayağa kaldıracaktır.

"dotnet help" komutu sayesinde neyi nasıl kullanmamız gerektiğini öğrenebiliriz.


  👉 ! Referans mantığı, 
  
  Yazılım geliştirme sürecinde kendimiz yada bir başkası tarafından önceden yazılmış olan  paketlerin/kütüphanelerin desteğini alarak kod yazabiliyoruz, işte buna referans mantığı diyoruz. Örneğin bir algoritma önceden yazılmışsa ve bu bir paket/kütüphane olarak tutuluyorsa daha sonra projede tekrar lazım olduğunda aynı kodları yazmak yerine yazılı olan paketi/kütüphaneyi dahil ediyoruz/çağırıyoruz/referans alıyoruz. 


 👉 ! Restore, 
 
 .NET proje dosyalarının kullanılan bağımlılıklarını (dependencies) yüklemek ve proje dosyalarını kullanıma hazır hale getirmek için kullanılan bir işlemdir. Bir .NET projesinin içinde, projenin gereksinim duyduğu diğer kütüphaneleri, framework'leri veya paketleri belirten bir project file (proje dosyası) bulunur. Bu dosya, projenin bağımlılıklarını ve proje yapılandırmasını tanımlar. Restore işlemi, bu project file içinde belirtilen bağımlılıkları ve gereksinimleri (dependencies) yükler.  Özellikle bir proje ilk oluşturulduğunda veya projeye yeni bir bağımlılık eklendiğinde,çıkarıldığında, restore işlemi yapılması gereklidir. Projenizin bulunduğu dizindeki proje dosyasını (genellikle .csproj uzantılı) okur, projenin bağımlılıklarını indirir ve yükler. Bu sayede, projeyi derlemeye veya çalıştırmaya hazır hale getirir.


👉 ! Publish, 

Çıktı olarak,
dll
.deps.json(projenin tüm bağımlılıklarıı içerir.)
runtimeconfig.json(runtime konfigürasyonları)
Uygulama bağımlılıklarının dll'lerini verir.

"\bin\\Debug\net5.0\publish" dizinine çıktı verir.

Herhangi bir proje kaynak  kodlarıyla birlikte inşa edilip piyasaya sunulmadan önce bu porjenin kaynak kodlarını biz gizlemek isteriz. Bazen algoritmayı piyasaya sunmak istemeyiz. Dolayısıyla böyle bir durumda projeyi yayınlanabilir yani piyasaya sunulabilir hale getirmemiz lazım, eğer ki bu proje bir web uygulaması ise bu projeyi hosting'e atabilir yayınlanabilir hale getirmemiz gerekir. Sonuç olarak, kaynak kodları/dosyaları bizde olacak şekilde biz bunların çıktılarını alıp yayınlayabiliyoruz. İşte bunu yapmamızı sağlayan Publish komutudur. Ayrıca bir uygulama başka bir uygulamayı kullanıyorsa, başka bir paketi yada kütüphaneyi kullanıyorsa ona bağımlıdır. Orada bir bağımlılık söz konusudur. Dolayısıyla Publish işlemi bu bağımlılıkları da referanslayan bir dosya verecektir. 

👉 ! Editörler genellikle derleyici içermedikleri için derleme işlemi yapamazlar. Ancak bazı eklentilerle bu tür editörlerin yetenekleri geliştirilebilir. 

👋 18 -  Paket İle Referans Arasındaki Farklar Nelerdir ?

Projede işlemler yapmayı sağlayan projeyle ilgili kütüphane/paket/referans ekleme/çıkarma işemlemlerini yapmamızı sağlayan proje modifikasyon komutlarıdır.  “add package (paket ekleme)” , “remove package” , “add referance” gibi. 

Paket ve kütüphane "NuGet" dediğimiz aynı havuzdan gelir. 

Referanslar, önceden yazılmış "dll" çıktılarıdır. Yani fiziksel olarak elimizde bulunan .dll dosyalarıdır. "dll" dosyası, başka bir yazılım tarafından kullanılabilecek olan çıktıdır. Ama derleme sonucu oluşan çıktıyı bir başka yazılım değil, bir son kullanıcı kullanacaksa bu çıktılar da "exe" uzantısına sahip çıktılardır. 

"dll" dosyalarına referans ama NuGet dediğimiz havuzdaki farklı kütüphanelere(uzaktan, internetten çektiklerimiz) paket diyoruz. Tabi bir yandan referans olanlar da bizim için paket mahiyetinde oalbilirler ama genel anlamda teknik olarak referans ve paket bu şekilde ayrılmaktadır. 

Elinde fiziksel bir dosya var ve uzantısı dll ise, bunu projene eklerken referans olark eklersin. Eğer sen NuGet denilen havuzdan bir kütüphaneyi uygulamana çekeceksen onu da paket olarak çekersin.

NuGetta bulunan farklı kütüphanelerin toplandığı yere ise paket deriz.

  👉 !  Kütüphane ve paket farkı :

  Kütüphane genellikle kodun bir parçasını ifade ederken, paket genellikle bu kütüphaneleri, araçları veya kaynak dosyalarını toplu olarak içeren bir bileşeni ifade eder. Kütüphaneler belirli bir işlevi yerine getirirken, paketler genellikle bir projenin dışa bağımlılıklarını yönetmek ve entegre etmek için kullanılır. 

👉 !  NuGet : 

.Net geliştiricilerinin kullanabileceği geniş bir kütüphane ve paket deposudur. Bu depoda, .Net uygulamalarında kullanılabilecek çeşitli kütüphaneler, araçlar ve bileşenler bulunur. Bu nedenle NuGet'ta bulunan farklı kütüphanelerin toplandığı yere "paket deposu" yada "paket" denir. NuGet, Visual Studio ve diğer geliştirme ortamları ile entegre çalışır ve geliştiricilere kolayca paket arama, indirme, yükleme ve güncelleme imkanı sunar. 

👉 !  Bir örnek vererek daha anlaşılır şekilde açıklayalım: 
"Python" programlam dili için "numpy" bir pakettir ve bu paket "math" kütüphanesi içerir. "math" kütüphanesi, matematiksel işlemler için hazır fonksiyonları barındırır. İşte bu örneğe göre, "numpy" bir paketken, "math" bir kütphanedir ve bir paket altında birden çok kütüphane/modül bulunabilir. 

![18-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/e3225e14-dbab-474d-9d49-306016eab103)

👉 ! Projeye paket ekleme , derleme ve referans işleyişi/ilişkisi : (sor)

* Proje oluşturulduğunda, genellikle bir ".csproj" dosyası oluşturulur. Bu dosya, projenin yapılandırma ve bağımlılıklarını tanımlar. Bu aşamada herhangi bir NuGet paketi eklenmez.
* Projeye NuGet paketleri eklemek için, ".csproj" dosyasına "<PackageReference>" öğeleri (Bir projenin başka bir projeye veya bir kitaplığa bağımlı olması durumunda, bu bağımlılıklar referanslar aracılığıyla belirtilir. Projede bu bağımlılıkları/paketleri kullancam dediğim kod satırıdır.) eklenir. Bu öğeler, projenin kullanması gereken paketleri ve bunların sürümlerini belirtir. 
* Proje derlendiğinde/build olduğunda , proje bağımlılıkları kontrol edilir ve bu paketler NuGet havuzundan indirilir. Ancak henüz projeye dahil edilmemiştir, dolayısıyla bu aşamada sadece proje derleme süreci başlatılır. Bu aşamada, referanslar projenin bir parçası haline gelir ve projenin derleme sürecine dahil edilirler.
* Derleme esnasında NuGet havuzunda belirtilen paketler indirilir ve projeye yüklenir. Bu işlemi ".csproj" dosyasındaki "PackageReference" 'ye göre yapılır.
* Proje derlenirken paketler de dahil edilir dedik. Derleme işlemi tamamlandığında, projenin çalışabilir çıktı dosyaları oluşturulur.
* Derlenmiş çıktı dosyaları, projenin paketlerini/bağımlılıklarını içerdiği için "referans" olarak adlandırılır.Bu referanslar, projenin derlenmiş çıktı dosyalarına dahil edilir ve projenin bağımlılıklarını temsil ederler.


👋 23 - Programlamaya Başlarken Temel İlkeler

Bir dil öğreneceğiz, bu dil beşeri bir dil olmasada makinelerle ve bilgisayarlarla iletişim kurmamızı sağlayacak bir dildir.

Nasıl ki beşeri dilde cümle kurarken cümlenin öznesi yüklemi varsa, programlama dilinin de kendine has prensibi, geleneği vardır. İleride design pattern sayesinde düzgün kod yazacağız.

Her programlama dili başlangıçta bir gelenek ve kabulle yola çıkar. Biz bunlara prensipler diyoruz. Belirli prensipler/kurallar dahilinde hareket ederseniz o dil üzerinde edebiyat yapmanız/kendinizi/çözümünüzü ifade etmeniz kolaylaşacaktır.

Programlamada temel ilkelerimiz vardır. Bu ilkeler olmazsa olmadzır. 

İlke, sosyolojik açıdan yaparsanız doğru yapmazsan yanlış demek değildir/sıkıntı yoktur.

İlkeler genellikle değişmezler. Çünkü evrensel doğrulardır/kabuldürler. Geneleneksel bir anlayışın üzerine oturmuş doğrular değildir. Bunlar genel/evrensel doğrulardır. Ne zamana yaparsan yap, ne zaman uygularsan uygula her daim bir doğruluğu vardır.

Temiz kod yazma sanatında prensipler bizim için olmazsa olmazımızdır. Prensipsiz temiz kod yazamazsınız.

Bir programcı ilkeli birisi olmaldıır. 

👋 24 - Programlamaya Başlarken Temel İlkeler - Don't Repeat Yourself

Bir programcı kendini tekrar etmez.

Bir programcı komutları/kodları sürekli tekrar etmektense öğrendiği yapılarla bunu daha analitik çözüm haline getirip tekrarlı değilde tek seferli hale getirebilmelidir. 

Kodu tek elden yönetmek içn çabalayın. Çünkü her yerde aynı algoritma çalışacakatır ve bir gün algoritmayı değiştirmek istersen tekrar erden ehr noktada değişiklik yapman büyük bir sıkıntı olacaktır. Bunun için tek bir yerde algoritma yazıp o yazdığını her yerde kullanacak şekilde bir tasarıma geçebilmen lazım. Değişiklik olduğu zaman bir noktayı değiştirirsin onu kullanana her yere o değişiklik yansıyacaktır. İşte doğru tasarım budur.

Hiçbir algoritmayı ezberlemeyin, bir öğrendiğiniz algoritmayı sürekli oalrak aynı şekilde kullanmayın. Bu yaratıcılık zekanızı öldürür. O anda soruna çözüm getirecek algoritmalar bulmak daha doğru/geliştirici/canlıdır. 

Aynı kodun aynı blokta tekrar tekrar yazılmış olmamasına özen gösterin.

Kodda bir tekrar varsa bunu daha analitik nasıl kodlayabilirm diye düşün. Tekrar eden o kodu düzelt. İşte buna refactoring denir. Yani kodu düzeltme, yeniden düzgün/tekrara düşemeyecek, şekilde yazma.

👋 24 - Programlamaya Başlarken Temel İlkeler - Anlamlı İsimlendirme

Bir isimlendirme yaparken anlamlı değilde saçma sapan bir isim verirsen bu kodun gelişimine ciddi manada zarar verir. Lise matematikte görülen x,y değişkenlerini yazılımda isimlendirme kullanmayacağız. Onun yerine değeri ifade eden mantıklı/anlamlı isimlendirme yapılacak.

👋 26 - Main Fonksiyonu Nedir ? 

Bir programda zorunlu olması gereken fonksiyondur.

Oluşturduğumuz tüm uygulamalarda bir ana fonksiyon olması gerekiyor. Ve o ana fonksiyonun adı Main fonksiyonudur. 

Uygulamaların altında Program.cs adında bir dosya vardır. Program.cs dosyasını programnın başlangıç dosyası gibi düşünebilirsiniz.

Başlangıç kodlarının bulunduğu dosya Program.cs dosyasıdır. 

Uygulamalarda Program.cs dosyası başlangıç kodlarının buunduğu yani uygulamaın ayağa kalkabilmesi için başlangıç kodlarının bulunduğu bir dosyadır.

.cs uzantılı dosyalar C#' a karşılık gelir.

Main fonksiyonu, uygulama ayağa kalktığında işletim sistemiyle iletişim kurabilecek metodun ve bu metot içerisinde başlangıca dair gerekli komutların inşa edildiği bir yapılanmadır. 

Siz bir uygulamayı çalıştırdığınızda b uuygulamanın bulunduğu işletim sistemiyle iletişimini sağlayan fonksiyona main fonksiyonu diyoruz.

Başlangıç kodlarını biz Main içnde yazarız. Bir uyugulama ayağa kalkarken işletim sistemiyle ilişkiyi kurar. İlk ilişkiyi kurduğundan doalyı ilk tetiklenen fonksiyonda Main fonksiyonudur. 

Herhangi bir uygulamada Main fonksiyonu sadece ve sadece bir kere olmak zorundadır. Bşaşka bir yerde bir dosyanın içinde Main isimli fonksiyon bulunamaz.

Main fonksiyonu uygulamada Program.cs dosyası içinde Main adında bulunur.

Main fonksiyonu uygulama adına işletim sistemiyle iletişim kurar.
  
Main fonksiyonuyla işletim sistemiyle iletişim sağlanır. Bu iletişim sayesinde bizim uygulamamıza işletim sistemi veri gönderebiliyor. Bizde bu veriyi Main üzerinden yakalayıp içeride işleyebiliriz.

İşletim sistemi veri gönderirken uygulamanın içindeki Program.cs içindeki Main fonksiyonuna veri göndereceğini biliyor.

Dolayısıyla uygulamanın içinde Main fonksiyonu yoksa ayağa kaldıramazsınız/derleyemezsiniz/hata alırsınız. Projenin derlenip çalıştırılabilmesi için Main fonksiyonu olmak zorundadır. 

![26](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/65852c84-61da-43b3-bf9d-9f2e4bbdfb6c)

👋 27 - Dotnet Run Value Yapısı İle Uygulamayı Çalıştırma ve Args Parametresine Değer Gönderme

Main fonksiyonu ayağa kalktığı anda işletim sistemiyle kontağı kuran bir yapılanmaya sahiptir.

Metotlar/fonksiyonlar parametre alan yapılardır.

Dotnet CLI ile uygulamayı çalıştırırsak buradaki uygulamaya args parametresine değer gönderip uygulama içinde de bu değeri yakalayıp/kullanabiliyorum.

![27](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/17b864cf-5b6b-4a06-971f-f05279b19f45)

![27-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/7af6cbba-6a33-4279-b6f3-39674f007226)

Örnekte, Dotnet CLI/terminal ile "dotnet run yasemin" komutu çalıştırıldığında, işletim sistemi bu komutu algılar ve uygulamayı çalıştırır. "yasemin" argümanı, işletim sistemi tarafından main fonksiyonuna iletilir. Main fonksiyonu bu argümanı, paremtre olarak karşılar. 

👉 ! İstediğin kadar değeri arada boşluk bırakarak göndwerebilirsin ve yakalayıp/kullanmak için "args[0]","args[1]" şeklinde index numaralarını değiştirerek kkullanabilirsin. 

Main fonksiyonu parametre kısmında, komutta gönderilen değer olan "yasemin" yakalanır ve uygulamada kullanılabilir. Main fonksiyonu içinde “Console.WriteLine(args[0]);” yazılırsa, çıktı "yasemin" olur.

👉 ! Dolayısıyla, Main fonksiyonu çift yönlü olarak, işletim sistemi ve uygulama arasında çalışır. Uygulamadan işletim sistemine veri gidip işlemler yaptırılabilir, aynı şekilde işletim sisteminden gelen komutlarla uygulamada işlemler yapılabilir. 

👉 ! Komut istemi, kullanıcıların işletim sistemleriyle etkileşim kurmalarını sağlayan bir arayüzdür. Kullanıcının işletim sistemi üzerinde komutlar çalıştırmasına ve dosya yönetim işlemleri gibi temel işlemleri gerçekleştirmesine izin verir. Windows işletim sistemi için komut istemi genellikle "cmd" veya "Command Prompt" olarak adlandırılırken, Linux ve macOS gibi Unix tabanlı işletim sistemlerinde "Terminal" olarak adlandırılır.

👉 ! CMD (Command Prompt), Windows işletim sisteminde kullanılan bir komut istemi programıdır.

👉 ! .NET CLI (Command Line Interface), .NET Core ve .NET 5 ve sonrası sürümlerinde bulunan komut satırı arayüzüdür. Geliştiricilere .NET uygulamaları oluşturma, derleme, yayınlama, paket yönetimi ve diğer geliştirme işlemlerini gerçekleştirmek için komut satırı aracılığıyla bir dizi komut sağlar. 

👉 ! CMD, Windows işletim sistemi için genel bir komut istemi programıdır ve .NET CLI gibi özel bir geliştirme aracı değildir. .NET CLI ise .NET geliştirme araçları için özel olarak tasarlanmış bir komut satırı arayüzüdür ve .NET uygulamalarının geliştirme sürecini yönetmek için kullanılır.

👋 28 - Top Level Statements  (C# 9.0) Özelliği

Biz herhangi yeni bir kouyla ilgili test komutları çalıştıracak olabiliriz. Bir deneme yapmam lazım ve bir projeye ihtiyacım var. Böyle bir durumda developer gider Console uygulması açar ve orada deneme yapar.

Basit bir denemede bile birçok greksiz komuta maruz kalırız. Proje oluşturulduğunda default olarak (boilerplate-basmakalıp) kodlar gelerek istemsiz kodlara maruz kalınabilir. C# 9.0 ile gelen top level statements özelliği sayesinde, main fonksiyonu kullanmadan "using System;" ve "namespace" blokları arasına istenen kodlar yazılıp çalıştırılabilir. Komutlar/kodlar derleme esnasında Main fonksiyonu içerisine alınacaktır.

👉 ! Bu özellik ile main fonksiyonu kullanılması developer'ın isteğine bırakılmıştır. Main fonksiyonu kullansanda kullanmasanda arka planda varsayılan oalrak bir main fonksiyonu olacaktır. Normalde main fonksiyonu olmadan bu kod derlenmezdi ama C# 9.0 ile gelen bu özellik sayesinde bu şekilde kod inşa etmeye izin veriyor. 

Kurallar:

* Kodlar sadece, using blokları ile namespace arasında yazılabilir.
* Bu işlem/özellik sadece Program.cs dosyasında kullanılabilir. Farklı bir dosyada denereseniz program hata verir.

Kodları, Main fonksiyonu içinde yazmak zorunda değilsin derlenme sırasında sistem otomatik Main fonksiyonu içine alacaktır. İçine alacağı kodlar, using blokları ve namespace arasıdaki kodlar için geçerli olacaktır. Buradaki kodları kabul edecek ve Maine'e direkt onları yazacaktır.

Uygulama derlenirken Program.cs dosyasında varsa Top Level Statements özelliği bu dosyaya özel algılayavak ve ilgili alana yazılan kodları Main içerisinde yorumlayacaktır. Bunun dışında zaten bu özelliği başka bir dosyada kullanamayacağımzıdan dolayı dadece Program.cs dosyasına has bir özelliktir.

👋 29 - Yorum Satırları ve Region

Programlama yaparken yazdığımız kodlar karışık ya da anlaşılması güç olabilir. Bu durumlarda kodları anlaşılabilir hale getirerek açıklamak yada önemli gördüğümüz kısımları not almak isteriz.

Yazmış olduğum kodu bir şekilde izah etmem/açıklamam gerekebilir. İşte bunu yorum/açıklama satırı ile yaparız.

Biz yorum satırı kullandığımızda, derleme esnasında "//" bu operaör ile satırın bir yorum satırı olduğu anlaşılacak ve burası derlenmeyecektir. Yani "//" kısımdaki yazılar kod olarak gçrünmeyecektir.

Genellikle açıklama/yorum satırı kullandığımızda kodun izahetini yaparız/açıklarız. Küçük/ufak/kısa açıklamalar yaparız, tutup da destan yazmayız/yazmamız doğru olmaz.

Açıklama/Yorum Satırları:

Kodun niteliğini, anlaşılabilirliğini, kalitesini arttırabilmek için kullanılır.
Kritik noktalarda ve özet olarak kodları izah etmeliyiz.
// Tek satırlık yorumlarda kullanılır.
/* Çok satırlı yorum alanı */
Nerelerde yorum satırları kullanılır ? 
İstediğin her yerde, kod konseptini ve semantik akışı bozmammak kaydıyla, yorum satırı kullanıp açıklama yazabilirsin. 

Region : 

Kod dosyasını kategorik hale egtirmemizi sağlayan ön işlemci komutudur. 

Ön işlemci komutu editörün yorumlayabildiği bir yapılanmadır.

Developer'ın yazmış olduğu kodu daha net görmesini ve kategorize etmesini sağlar.


👋 30 - Todo Nedir ? 

Kodun içine alınan notlara çabuk erişebilmemizi sağlayan bir özelliktir. 

Açıklama yazıyoruz ama bu açıklama oradaki kodu izah etmekten ziyade orada yapılması gereken eksik bir şeyi izah eder.

Programlamada bazen kodlarda unutulan yada yapılması gereken şeyler gözden kaçırılmış/düşünülememiş olabilir. Bunları belirtmek için bir hatırlatıcı gibi "todo" keywordü kullanılır.  

Projede birçok dosya olursa ve birçok todo keywordü kullanılmışsa daha sonradan bu todo'ları bulmak bizim için zorlaşacaktır. Bu durumda Visual Studio da üst sekmeden "View > Task List" penceresi çaılır ve tüm projelerde kullanılan todo'lar bizim için listelenir. Bu şekilde hangi dosyada ve nerede todo kullanılmış rahatlıkla erişilir. Yani bu özellik kod içinde aldığımız notlara hızlı bir erişim sağlayan bir özelliktir.

Bu süreç, compiler tarafından değil editör tarafından sunulan bir hizmettir. Compiler buradaki sorumluluğu üstlenmez. 

👉 ! //todo ornek , burada todo keyword olarak algılanır ve ona göre hareket edilir.
//todo2 ornek, burada ise todo2 şeklinde yazıldığı için todo keyword olarak algılanamaz ve program hata verir. -?

👋 31 - Debbugging Nedir ? 

Debugging, hata ayıklamaktır. Programın hatalarını yok etmeye yönelik kodları gözden gerçirme aktiviteleridir. 

Daha çok yazılan kodlarda mantıksal bir hatanın var olduğu düşünülüyorsa debugging işlemi ile kodlar satır satır incelenip hata ayıklamaya çalışılır. 

Formülde bir hata olduğunda yani genel grammerde bir hata yok ama formülde yaptığın hatayı yakalayabilmen ve çözebilmen için debugging dediğimiz tekniği kullanmak gerekir.

Debugging, kodun akışı esnasında kodu okuyabilmemizi ve gözlemleyebilmemizi sağlamaktadır.

Debug, debug etmek, debugging hepsi aynı anlamı ifade eder.

👋 32 - BreakPoint Nedir ve Nasıl Yapılır ? 

Break Point, işaretlenen kodun debug edilmesini sağlayan bir teknolojidir/yapıdır.

Debug'ın amacı, bir koddaki hatayı ayıklamak, bir koddaki yapılanmayı daha da efektif hale getirmek, var olan mantısal hataları rahat bir şekilde temizleyebilmektir.

Bir kodu Debug'a tabi tutmak demek, ilgili kodu varsayılan olarak debug modda çalıştırmak demektir.

![32-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/f077365e-c989-435f-b4a0-80aefd6f7cba)

İlgili kod satırının en başına konulan kırmızı nokta, break point'i ifade eder.

Break Point konulup proje çalıştırıldığında konsept konsept okunan kodlar işaretli olan satıra geldiğinde durur/ilerlemez ve o kısımdan başlayarak istediğimiz kadar ilerleterek, olan değişiklikleri/yönlendirmeleri incelememize olanak verir. Eğer f10' a basılırsa debug modda kodlar okunmaya devam edilir, f5' e basılırsa debug moddan çıkarılıp sadece sonucun ekranda gösterilmesi sağlanır.

👉 ! Bir projeyi çalıştırdığımızda varsayılan olarak debug modda çalışır ve Break Point kullanılırsa kodların davranışları incelenir.

👉 ! Debug modunda, breakpoint’ler kodun belirli bir noktasında durmasını sağlar. Debug modunda, breakpoint’ler debug işlemine yardımcı olur.

👉 ! Debugsız modda, breakpoint’ler kodun belirli bir noktasında durmasını sağlayamazlar, debug' ı yakalayamazlar. Yani kodun akışı Break Point noktasına geldiği zaman debugging başlamayacaktır.

👋 33 - Watch Penceresi

Bir algoritmayı debug ederken o algoritma içinde bulunan değişkenlerin değerlerini daha hızlı bir şekilde görmemizi sağlayan penceredir. 

Debug modda Break Point koyulmuş kodlar incelenirken değişkenlerin değerlerini görmek için değişken adına sağ tıklanıp "Add Watch" seçeneği ile pencere açılıp değerine bakılabilir.

![33-1](https://github.com/Yasemin-s/C----reniyorum---1/assets/118223063/86a55c11-17f3-42e1-ac66-4b5f482abdc1)

👋 34 - Debugsız Uygulama Nasıl Çalıştırılır ? 

Bir uygulamayı direkt ayağa kaldırıp çalıştırdığımzıda varsayılan olarak debug modda çalışır demiştik.

Debug zaman açısından maliyetli bir süreötir. Bazen hızlı testler yapabilmek için yazılımın derlenmesi ve çıktı vermesi istenir. Bu durumda projeyi debugsız modda çalıştırmak gerekir. Visual Studio'da üst sekmeden "Debug > Start Without Debugging(f5)" ile proje debugsız modda çalıştırılabilir.

