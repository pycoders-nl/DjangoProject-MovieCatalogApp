# DjangoProject-MovieCatalogApp

Video 2:
- Django kurulum yapildi. pip install Django

Video 3:
- istedigimiz dizinde python-django startproject proje ismi yazip projemizi olusturuyoruz.
- sonra vscode terminalden olusturdugumuz projenin manage.py dosya dizinine gelip python manage.py runserver komutu ile projemizi web tarayicisinda gorebiliriz.

Video 4:
- proje icerisinde bir tane app olusturduk python manage.py startapp app ismi komutu ile.
- olusturdugumuz app'i setting.py'de installed_app kismina ekliyoruz.
- views.py de gerekli fonksiyonlarimizi tanimladik.
- kendi olusturudugumuz app icine bir urls.py dosyasi ekledik.
- gerekli duzenlemeleri yaptik ve gelen request'e bir response verdik.

Video 5:
- burda bir html sayfasi ve layout olusturduk ve bunu setting.py de djangoya tanittik.
- html.sayfalari olsturduk, ve her html sayfasinda ayni iskeleti kullanmamk icin bir ana html sayfasi olusturuyoruz. layout.html.

Video 6:
- burda static file olusturduk, ve burdaki css,image vb dosyalari html'e ekledik.

Video 7:
- bootstrap themasi ekledik projemize ve nav-bar hazirladik.
- header, main ve footer olusturduk.
- resimler ekleyip bilgilerini yazdik.
- nav-barda kullandigimiz isimlerden hangisin icindeysek onun active olmasi icin if statement ekledik.

Video 8:
- movies isminde yeni bir app olusturduk, ve dosya icine urls.py dosyasini olusturduk. birde templates dosyasi altina birtane movies dosyasi olusturduk.
- bu app'i tabikide setting.py de djangoya tanitmamiz lazim. installed_app kismmina app'imiziekliyoruz.
- oncelikle urls.py dosyamizda gerekli pathleri veriyoruz, ve bunu ana urls.py dosyasina include ediyoruz.
- sonra app altindaki views.py de fonksiyonlarimizi yaziyoruz ve html sayfalarimizi olusturuyoruz.
- sonrasinda html sayfalarimizi dizenliyoruz. birde projemize jumbotron ekledik.

Video 9:
- admin panale icin superuser olusturduk.
- admin tablolarini migrate yaptik.
- kullanicilara erisim izni ayarlari yapildi.

Video 10:
- bir model olusturup bu modeli admin panaline ekledik.
- sonrada migrations yaptik.

Video 11:
- admin panalini ozellestirdik, __str__ kullanilarak objenin ismi goruntulendi admin panelinde.
- admin.py de yeni bir class olusturup admin panaelimize filter ve diger ozellikleri ekledik.
- ispublished diye bir degiskene kayitlarin checkbox ile yayinlanip yayinlanmadigini kontrol ettik. burda istersek sadece isaretli filmleri publish edebiliriz.
- her sayfada kac item gosterilecek onu belirledik.

Video 12:
- bu videoda movies sayfamiz icin databasedeki movieleri alip sayfamizda bilgileriyle gosterdik.
- bilgileri gosterirken olusturulmus objelerden name,created_date ve description lari iki suslu parantezle ekranda gosterdik.
- resim almak icin model kisminda class altina bir fonksiyon tanimliyoruz, ve bu bize resime gidecek bir yol veriyor ve biz bu yolu html sayfasinda kullaniyoruz.
- gorulen tarih bilgisini bugun dun 2 gun once seklinde gosterdik.

Video 13:
- bu videoda hazirladigimiz movie list sayfasinda herhangi bir movie tiklandiginda ayrintilari gosterdik. once movie ismini bir link verdik.
- sonra bu movie'nin id'sine gore database'den bilgileri alip details sayfamizda gosterdik.

Video 14:
- projemize user isminde yeni bir uygulama ekledik. bunu setting.py de tanimladik.
- user uygulamasi icin bir model olusturmuyoruz admin panelinde hazir olan tablolari kullanicaz.
- her uygulamada yaptigimiz gibi bir urls.py dosyasi olusturuyoruz ve gerekli duzenlemeleri yapiyoruz dosya icinde.
- navbarimizia login ve register kisayollarini ekledik ve hangi sayfadaysak onu aktif hale getirdik.

Video 15:
- login ve register sayfalarini kullanilir hale getirdik, kullanici kayit yapabilecek.
- login ve register sayfalarinda form'lar olusturduk. Get ve Post methodlarini inceledik.
- user dosyasi altindaki views.py dosyasinda def register kismini duzenledik. gerekli sorgulari yaptik, ornegin bir kullanici kayit olurken username ve emailinin baska
kullaniciyla ayni olmasini engelledik, birde sifre ve sifrre tekrar bolunlerinin ayni olup olmadigini kontrol ettik.

Video 16:
- olusturdugumuz kullanicilarin login sayfasindan sitemize girisini sagladik.
- bir kullaniciyi login yapmak demek sitemizde rahatca dolasabilmesi icin dogru bilgileri verdiginde ona bir session id' si vermektir.
- views.py de verilen bilgileri database'imizde check ettik ve gerekli sorgulari yaptik.

video 17:
- kullaniciya mesaj yollamayi ekledik projemize.
- bir alert.html sayfasi olusturup bunu ana html sayfamiza ekledik.
- birde setting.py dosyasina message_tags frameworku ekledik.

Video 18:
- bu videoda nav-barda kullanici girisi olup olmadigini duzenledik.
- giris yapmis kullaniciya nav-barda kullanici adini ve logout gosterildi.
- giris yapilmadiginda ise login ve register bolmeleri gosterildi.
- logout tiklandiginda kullanici basariyla sitemizden cikarildi.