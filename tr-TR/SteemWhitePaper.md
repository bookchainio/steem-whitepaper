# Steem

## Bir blockchain temelli, tesvikli, kamusal paylasim platformu.

Agustos 2017

# Çevirmenin Notları

Placeholder for translator's notes.

# Özet

Steem topluluk olusturmayi ve kripto parabirimi ödülleri yoluyla sosyal etkilesimi destekleyen bir blockchain veri tabanidir. Steem sosyal medyadan bazi kavramlar ile kripto para birimi ve onlarin topluluklarini olusturmak konusundan cikartilmis dersleri bir araya getirir. Herhangi bir topluluk, para birimi ya da özgür piyasa ekonomisi icerisindeki katilimi yayginlastirmanin anahtarlarindan biri her bireyin katilimini tutarli bir sekilde yansitan bir adil muhasebe sistemidir. Steem sinirsiz sayida bireyin kendi topluluklarina *öznel katkilar* sunmasini dogru ve seffaf bir sekilde ödüllendirmeyi hedefleyen ilk kripto para birimidir.

# Icindekiler

<!-- toc -->

# Giris

Kollektif halde, kullanici tarafindan yaratilmis icerik Reddit, Facebook ve Twitter gibi sosyal medya sirketlerinin hissedarlari icin milyarlarca dolarlik bir deger yaratti. **2014 yilinda Reddit, reddit.com'a hikaye paylasimlari, yorum ekleme, ya da oylama yoluyla katkida bulunmus olan herkesin Reddit'ten adil bir hisse ile ödüllendirilmesi durumunda kendi platformlarinin cok daha gelisecegi varsayimini öne sürdü.<sup id="fnref:1"><a href="#fn:1" class="footnote-ref"></a></sup>**. Steem sosyal medyayi ve cevrim ici topluluklari, sahip oldugu degerin büyük bir kismini ona degerli katkilarda bulunan herkesi kripto parabirimleri ile ödüllendirmek yoluyla onlara iade ederek, desteklemeyi amaclamaktadir.

Steem'in tasarimina rehberlik etmek icin kullanilmis olan bazi ana ilkeler vardir. En önemli ilke bir girisime katkida bulunmus olan herkesin girisimden nisbi oranda hisse, ödeme ya da borc aliyor olmasidir. Bu ilke, kurulus asamasinda ve müteakip fonlama rauntlari sirasinda hisse dagitan tüm startup'larda uygulanan ilkenin aynisidir.

Ikinci ilke, tüm sermaye cesitlerinin esit derecede degerli olmasidir. Bu su anlama gelir: Kisitli zamanlarini ve dikkatlerini digerleri icin icerik üreterek ve küratörlük yaparak katki olarak sunanlar kisitli nakitlerini katki olarak sunanlar kadar degerlidir. Bu emek-yogun sermaye ilkesidir[^2] ve kripto parabirimlerinin öncesinde, cok az sayida sayida bireyden fazlasina yardim edebilmek konusunda cogunlukla sikinti yasamistir.

Ücüncü ilke, toplulugun üyelerine hizmet edebilmek icin ürünler üretiyor olmasidir. Bu ilke, kendi topluluklarinin disina mal ya da hizmet satmaktansa sadece kendi üyelerine hizmet eden kredi birlikleri, yemek kooperatifleri, saglik paylasim planlari üzerinden örneklendirilebilir.

Steem toplulugu üyelerie asagida yer alan hizmetleri sunar:

1. Bir kürete edilmis haber ve yorum kaynagi.
2. Bir kisisellsetirilmis sorulara yüksek kalitede alma araci.
3. Amerikan dolarina es deger stabil bir kripto para birimi.
4. Ücretsiz ödemeler.
5. Yukaridaki servisleri kullanicilara saglayacak isler.

Steem'in ekonomik tesvikleri bir amaca yönelik olarak yeniden siralamasi, ilgili herkes acisindan, kendinden önceki sosyal medya ve kripto para birimi platformlarindakinden cok daha adil ve kapsayici sonuclar üretme potansiyeline sahiptir. Bu makale mevcut ekonomik tesvikleri inceleyecek ve Steem'in tesviklerinin katilimcilarin cogunlugu icin nasil daha iyi sonuclar üretebilecegini gösterecektir.

## Katkiyi Takdir Etmek

Steem sosyal medya temelli ekonominin bensimsenmesinin ve parasallistirilmasinin önündeki engelleri ortadan kaldirmaya yönelik olarak temelden tasarlanmistir. Bizim tezimiz sosyal medya platformlarinin büyütülmesi icin kullanilan ayni tekniklerin basarili bir kripto para birimine ön ayak olmak icin de kullanilabilecegidir. Kripto para biriminin mümkün kildigi ekonomik tesvikler yeni bir sosyal medya platformunun büyümesine carpici bir sekilde olanak saglayabilir. Biz inaniyoruz ki kripto bara birimi ve sosyal medya arasindaki sinerji Steem'e piyasada güclü bir avantaj saglayabilir.

Steem tarafindan yüklenilmis zorlu görev; bireysel katkilari, üyelerin cogunun her katkinin öznel degerinin adil bir sekilde yansitildigini düsünmesini saglayacak bir sekilde puanlayacak bir algoritma gelistirmekti. Ideal bir dünyada, topluluk üyeleri birbirlerinin katkilarini degerlendirme hususunda isbirligi yaparlar ve adil bir mükafat elde ederler. Gercek dünyada ise algoritmalarin kar elde etmek icin yapilan kasti maniplasyonlara karsi direncli olacak sekilde tasarlanmalari gerekir. Puanlama sisteminin yaygin bir sekilde istismar edildigi herhangi bir durum topluluk üyelerinin ekonomik sistemin algilarindaki hakkaniyetine olan inanclarinin düsmesine sebep olabilir.

Mevcut platformlar bir kullanici, bir oy ilkesi üzerine calisir. Bu, siralamalarin sybil saldirilari tarafindan manipüle edilebilecegi ve sunucu saglayicilarinin suistimal edenleri proaktif bir sekilde tespit edip engellemesini gerektiren bir ortam yaratir. Insanlar halihazirda Reddit, Facebook ya da Twitter siralama algoritmalarini ortadaki tek ödül internet trafigi ya da sansürken bile manipüle etmeye calismaktadir.

Steem platformu üzerindeki temel hesap birimi bir kripto para birimi olan STEEM'dir. Steem bir-STEEM, bir-oy temelinde çalışır. Bu modelde, hesap bakiyesiyle ölçüldügü sekliyle, platforma en çok katkıda bulunan kişiler katkilarin nasıl puanlandigi üzerinde çok fazla etkiye sahiptir. Dahasi, Steem kullanicilarina sadece vadeli mevduat cizelgesine oturtulmus olan STEEM ile oy kullanma hakki tanir. Bu modele göre, üyelere kendi STEEM'lerinin uzun vadeli değerini en üst düzeye çıkartacak şekilde oy kullanmaları için maddi bir teşvik vardır.

Steem cok basit bir kavramin cevresinde tasarlanmistir: *herkesin topluluga yaptigi anlamli katkilari, yarattigi deger kadar takdir görmelidir.* Insanlar anlamli katkilari icin takdir gördüklerinde katki yapmaya devam ederler ve topluluk büyür. Bir topluluk icerisindeki alma ve verme arasindaki herhangi bir dengesizlik hali sürdürülebilir degildir. Nihayetinde, verenler almakta olanlari desteklemekten yorulur ve topluluktan ayrilir.

Zorlu görev ise, sinirsiz sayida insana ölceklenebilecek sekilde, hangi katkilarin gerekli olduguna ve onlarin göreli degerine karar verebilme kapasitesine sahip bir sistem yaratmaktir.

Katkilarin degerlendirilmesi ve ödüllendirilmesi konusunda rüsdünü ispatlamis sistem ise serbest piyasadir. Serbest piyasa herkesin bir digeriyle ticaret yaptigi ve ödüllerin kar ve zarara göre paylasildigi tekil bir topluluk olarak görülebilir. Piyasa sistemi digerlerine deger saglayanlari ödüllendirir ve ürettigi degerden fazlasini tüketenleri ise cezalandirir. Serbest piyasa bircok para birimini destekler ve para ise sadece herkesin takas etmeyi kolay buldugu bir metadir.

Serbest piyasa rüsdünü ispat etmis bir sistem oldugundan, icerik tüketicilerinin icerik üreticilerine dogrudan ödeme yaptigi bir serbest piyasa sistemi yaratmaya calismak cezbedicidir. Ne var ki dogrudan ödeme icerik üretimi ve küratörlük icin islevsizdir ve cok da uygulabilir degildir. Iceriklerin cogunun degeri, bilissel, finansal ve firsat maliyetlerine ilintili olarak cok az okuyucu bahsis birakmayi tercih edeceginden, göreli olarak cok düsüktür. Bedava alternatiflerin coklugu, bir 'ödeme duvari'ni zorunlu tutmanin okuyuculari baska mecralara sürükleyecegi anlamina gelir. Okuyucudan yazara yapilacak mikro ödemeleri hayata gecirmeye calismis olan bircok deneme vardi fakat hicbiri yaygin hale gelemedi.

Steem ekonomik denklemi degistirerek her türden katki icin yapilacak mikro ödemelere imkan taniyabilmek icin tasarlandi. Okuyucular bundan böyle kimseye kendi ceplerinden para ödeyip ödemeyeceklerinin kararini vermek zorunda degiller. Bunun yerine, onlar sadece bir icerigi asagi ya da yukari oylayabilirler ve Steem bireysel ödülleri belirlemek icin onlarin oylarini kullanir. Bu ise, insanlara cokca kullanilan ve tanidik bir arayüz verilmesi; ve geleneksel mikro ödeme ve bahsis platformlariyla ilintili bilissel, mali ve firsat maliyetleri ile yüzlesmek zorunda kalmamalari anlamina gelir.

Topluluk üyelerinden gelen oy girdisi Steem'in katki sunanlara yapilacak ödemeleri isabetli bir sekilde dagitmasi icin cok önemlidir. Bundan ötürü oylama mühim bir katki sunma bicimi olarak görülebilir ve kendisi, basli basina, bir ödülü hak etmektedir. Slashdot gibi bazi platformlar dürüst moderatörleri siralamak ve ödüllendirmek icin meta-moderation'u[^3] kullanir. Steem ise, bir icerik parcasinin toplam tanitimina en fazla katkida bulunanlari ödüllendirmeyi tercih eder. Ve oylayanlari da yazara ödenmis nihai ödül üzerinden orantili olarak ödüllendirir.

# Katkida Bulunma Yollari

Bu kisim, Steem'in arkasinda yatan fikirler ve onun Steem topluluguna anlamli ve ölcülebilir katkilarda bulunan üyelerine sundugu ödüller hakkinda genel bir cerceve cizer.

## Sermaye Katkilari

Bir toplulugun sermayeyi cezbedebilmek icin sunabilecegi iki öge vardir: borc ve öy sermaye. Mülkiyet satin alanlar topluluk büyüdünde kazanirlar fakat kücüldügünde ise kaybederler. Borc verenlere ise belirli oranda bir faiz garanti edilir fakat toplulugun büyümesiyle gerceklesen kara katilmazlar. Her iki türden sermaye katkisi da toplulugun büyümesi ve onun para biriminin degeri icin kiymetlidir. Ek olarak, mülkiyetin düzenlenebilecegi iki yol vardir: Likit ve Vadeli Mevduat. Vadeli mevduat hissesi uzun vadeli bir taahhüt getirir ve mümkün olan en asagi zaman diliminde satilamaz.

Steem agi bu farkli malvarligi siniflarini Steem (STEEM), Steem Power (SP) ve Steem Dolari (SBD) olarak adlandirir.

## Steem (STEEM)

Steem, Steem blockchain'i üzerindeki temel hesap birimidir. Tüm diger tokenlar kendi degerlerini STEEM'in degeri üzerinden saglarlar. STEEM likit bir para birimidir ve bu sayede diger kullanicilara bir ödeme yöntemi olarak transfer edilebilirken takaslar sirasinda da alinip satilabilir.

## Steem Power (SP)

Start up firmalari uzun vadeli sermaye taahhüdüne gereksinim duyarlar. Paralarini start up'lara yatiranlar hisselerini satip karlarini paraya donusturmeden önce yillarca beklemek zorundadirlar. Uzun vadeli taahhütler olmaksizin, ilave ilave hisse satimi yoluyla fazladan sermaye yaratmaya calisan bir start up halihazirda mevcut hissedarlarin cikmaya calismasiyla bas etmek zorunda kalabilir. Idrak sahibi yatirimcilar sermaye katkilarinin sirketi büyütmesini isterler, fakat eger yeni sermaye halihazirda cikmak isteyenlere verilirse büyüme gerceklesemez.

Uzun vadeli taahhütlere sahip olmanin önemli bir degeri vardir cünkü o topluluklarin uzun vadeli planlar yapabilmelerine izin verir. Sermayedarlarin uzun vadeli taahhütleri ayni zamanda onlarin kisa vadeli sismelerden ziyade uzun vadeli büyüme icin oy vermelerine de yol acar.

Kripto parabirimi alaninda spekülatörler cogunlukla, hangisinin kisa vadede daha fazla büyüme beklentisine sahip oldugu temelinde, bir kripto para biriminden digerine ziplarlar. Steem, uzun vadeli bakis acisina sahip olanlarin mülkiyetinde olan ve tümüyle onlar tarafindan kontrol edilen bir topluluk insa etmeyi ister.

Kullanicilar Steem'lerini, platform icerisinde kendilerine ilave faydalar da saglayan, on üc haftalik bir vadeli mevduat cizelgesine taahhüt edebilirler. On üc haftalik vadeli mevduat cizelgesinde taahhüt edilmis olan STEEM, Steem Power (SP) olarak adlandirilir. SP bakiyeleri, otomatik olarak tekrar eden dönüsüm talepleri haricinde, transfer ve taksim edilemez. Bu da demektir ki, SP kolaylikla kripto para birimi takaslari sirasinda alinip satilamaz.

Kullanicilar icerikleri oyladiginda onlarin ödülerin dagitimi üzerindeki etkileri sahip olduklari SP ile dogru orantilidir. Daha fazla SP'ye sahip olan kullanicilar ödüllerin dagitimi üzerinde daha fazla etkiye sahiptir. Bu da demektir ki, SP ona sahip olanlara Steem platformu icerisinde münhasir yetkiler saglayan bir giris tokenidir.

SP sahiplerine vadeli mevduatlarinda duran SP bakiyesi üzerinden ayriyeten faiz ödenir. Yillik enflasyonun %15'i SP sahiplerine faiz olarak ödenir. Aldiklari faiz meblagi, tüm kullanicilar arasinda vadeli mevduatta tutulan SP meblagina nispi olarak, tuttuklari SP ile dogru orantilidir.

STEEM'den SP'ye aktarim yapmak ''Powering Up'' olarak adlandirilirken, SP'den STEEM'e aktarim yapmak ise ''Powering Down'' olarak adlandirilir. Power Down edilmis olan SP, power down'un baslatilmasindan bir hafta sonra, haftalik esit ödemeler yoluyla 13 hafta icerisinde kullaniciya ödenir.

## Steem Dolari (SBD)

Istikrar basarili küresel ekonomilerin önemli bir özelligidir. Istikrar olmaksizin, dünya genelinde bireyler ticarete ve tasarrufa yönelirken düsük bilissel maliyetlere sahip olamazlar. Istikrar basarili küresel ekonomilerin önemli bir özelligi oldugundan Steem Dolari Steem agini kullanan kullanicilara ve kripto para birimi dünyasina istikrar getirmeyi amaclayan bir hamle olarak tasarlandi.

Steem Dolari, Start up'lari fonlamak icin siklikla kullanilan dönüstürülebilir senetlere benzeyen bir mekanizma tarafindan yaratildi. Dönüstürülebilir senetler, start up dünyasinda -siklikla ileriki fonlama rauntlari sirasinda- gelecekte belirlenen bir oranda mülkiyete dönüstürülebilecek kisa dönem borclanma araclaridir. Bir blockchain temelli token, toplulukta bir mülkiyet olarak degerlendirebilecekken; dönüstürülebilir senet ise herhangi bir metaya ya da para birimine bagli bir borc olarak görülebilir. Dönüstürülebilir senedin kosullari, onu elinde bulundurana en az cabayla bagli oldugu tokena -tokenin adil piyasa fiyatinda- dönüstürebilme imkani tanir. Tokena dönüstürülebilir dolarlar yaratmak, token sahiplerin kazanclarini maksimize ederken blockchainlere de kendi ag etklilerini büyütme imkani tanir.

Steem Dolari Steem Backed Dollar'in kisaltmasi olan SBD sembolü ile gösterilir. SBD yaratmak güvenli bir fiyat yayininin ve istismarin önüne gececek kurallarin bir araya getirilmesini gerektirir. Güvenilir bir fiyat yayini üretimi üc unsuru barindirir: Dogru olmayan yayinin etkisinin minimize edilmesi, dogru olmayan yayinin sonuclarinin maksimize edilmesi ve zamanlamanin öneminin minimize edilmesi.

### Hileli Yayinlari En Aza Indirmek

SP sahipleri fiyat yayinlarini paylasmalari icin Witness'lar olarak adlandirilan bireyleri secerler. Secilmis Witness'lar, muhtemelen, yayinin kalitesinden nemalanan menfatleri olanlar nezdinde güvenilirdirler. Steem, bu secilmislere ödeme yapmak yoluyla, yayin yapmak icin hak kazanmaya yönelik bir piyasa rekabeti yaratmaktadir. Yayin üreticilerine yapilan ödemedeki artis, onlarin yanlis bilgi paylasimi durumundaki kayiplarini artirir.

Güvenilir ve secilmis yayin üreticileri göz önünde bulunduruldugunda, dönüsümler icin kullanilan aktüel fiyat yayinlarin medyanindan saglanabilir. Bu yolla, eger yayin üreticilerinden bir azinlik uc degerler üretirse, kendi ünlerine tesir edecek etkiye hala sahip olmakla birlikte aktüel medyan üzerinde minimal etkiye sahip olurlar.

Tüm yayin üreticileri dürüst olsa dahi yayin üreticilerinin cogunlugu icin kendi kontrollerinin ötesinde olan bazi gelismelerden etkilenmek hala mümkündür. Steem agi, topluluk aktif olarak sorunu düzeltmek icin calisirken, medyan fiyat yayinindaki kisa dönemlik yozlasmalari tolere edebilmek icin tasarlanmistir. Düzeltmek icin biraz zaman gerektirecek meselelere bir örnek kisa dönemlik piyasa manipülasyonlaridir. Piyasa manipülasyonun uzun zaman dilimleri boyunca sürdürülebilmesi zor ve pahalidir. Baska bir örnek de, merkezi exchange'in bir hatasi ya da exchange'in yayinladigi verilerin kirlenmesi olabilir.

Steem kisa dönem fiyat dalgalanmalarini üc bucuk günlük bir sürenin medyan fiyatini kullanarak hesap disinda tutar. Yayinlanmis fiyat yayini her saat icin saat baslarinda numulendirilir.

Fiyat yayini kirliligi degisen medyan zaman araliginin yarisindan kisa sürdügü müddetce onun dönüsüm fiyatlari üzerindeki etkisi minimal düzeyde olacaktir. Yayinin bozuk olmasi durumunda ag katilimcilarinin, bozuk yayin aktüel dönüsüm fiyatini etkilemeden önce, yozlasmis yayin üreticileri aleyhinde oy kullanma imkani olacaktir. Belkide daha önemlisi, bu, yayin üreticilerine yayinlari fiyati etkilemeye baslamadan önce tespit ve düzeltme sansi sunmaktadir.

Topluluk üyeleri -üc bucuk günlük zaman araliginda- ortaya cikan herhangi bir meseleye yanit vermek icin yaklasik olarak bir bucuk güne sahiptir.

### Zamanlama Saldirilarini Sönümlendirmek

Piyasa katilimcilarinin bilgiye blockchainin üc bucuk günlük hareketli medyan dönüsüm fiyatinin yansitabileceginden daha hizli bir ulasimi vardir. Bu bilgi alim-satimcilarin yarari namina toplulugun aleyhinde kullanilabilir. Eger Steem'in degerinde ani bir yükselir varsa, alim-satimcilar SBD'lerini eski, düsük dönüsüm fiyati üzerinden cevirme talebi gönderip daha sonrasinda edindikleri STEEM'lerini en ufak riskle yeni yüksek fiyat üzerinden satabilirler.

Steem dönüsüm taleplerinin üc bucuk gün bekletilmesini sart kosmak yoluyla oyun alanini kademelendirir. Bu demektir ki, ne alim satimcilar ne blockchain dönüsümün gerceklestigi fiyat hakkinda bir bilgi avantajina sahiptir.

### Dönüsüm Istismarmarini En Aza Indirmek

Eger insanlar iki yönde de rahatlikca dönüstürme yapabilselerdi o zaman alim satimcilar, blockchainin dönüsüm oranlarindan, fiyati degistirmeden büyük hacimlerde ticaret yaparak avantaj elde edebilirlerdi. Fiyatta bir firlama gören alim satimcilar en yüksek fiyattan (en riskli oldugu zamanda) SBD'ye dönüsüm yapabilirler ve gelen düzeltmeden sonra tekrar (STEEM'e) dönüstürebilirler. Steem protokolü sadece SBD'den STEEM'e tek yönlü olarak dönüsüm yapmaya olanak taniyarak toplulugu bu tarz istismarlardan korur.

Nasil ve ne zaman SBD üretilecegine ve kimlerin bunu edinecegine blockchain karar verir. Bu, SBD üretim oranini sabit tutar ve istismar yollarini ortadan kaldirir.

### Sürdürülebilir Borc-Mülkiyet Oranlari

Tüm token arzinda, tokenin kendisi bir mülkiyet olarak degerlendirilir ise, bu durumda token tokena-dönüstürülebilir-dolar bir borclanma olarak görülebilir. Eger borcun mülkiyete orani cok yükseklere cikarsa tüm para birimi istikrarsiz hale gelebilir. Borc dönüsümleri token arzini carpici bir bicimde artirabilir ki bu da sonucunda piyasada satilmasiyla fiyati baskilar. Ardisik dönüsümler cok daha fazla sayida token basilmasini gerektirir. Kontrol edilmedigi durumlarda sistem, ardinda bir borc yiginina dayanan degersiz mülkiyetler birakarak cökebilir. Borcun mülkiyete orani arttikca yeni yatirimcilar masaya sermaye getirme konusunda daha az istekli olurlar.

STEEM'in degerindeki ani bir degisim borc-mülkiyet oranini carpici sekilde degistirebilir. Blockchain, borclanma oraninin %10'u gecmesi halinde, SBD dönüsümleri sayesinde elde edilen STEEM'in meblagini düsürerek borc-mülkiyet oranininin cok yükselmesinin önüne gecer. Eger SBD borclanma miktari STEEM'in piyasa degerinin %10'u gecerse, blockchain dönüsümler yoluyla elde edilen STEEM meblagini otomatik olarak STEEM'in piyasa degerinin maksimum %10'una düsürür. Bu da blockchainin asla %10'dan fazla borc-mülkiyet oranina sahip olmamasini garantiler.

STEEM'i islemek icin kullanilan bu yüzde tabanlari, tahsil edilmemis SBD ve SP (Su anki kur / yayin tarafindan belirlenir) de dahil olmak üzere, arza dayanmaktadir.

### Interest

SBD onu elinde bulunduranlara faiz öder. Faiz orani fiyat yayinini yayinlayanlar ayni kisiler tarafindan belirlenir ki bu sayede degisen piyasa kosullarina adapte olabilsin. Her borclanma borc veren acisindan risk tasir. Geri ödeme yapmaksizin elinde SBD bulunduran kisi efektif bir sekilde topluluga dolar degeri ödünc vermektedir. Onlar gelecekte bir noktada birilerinin dolar karsiligi onlardan SBD almak isteyecegine ya da onlarin SBD'lerini dönüstürmüs olduklari STEEM'i alacak bazi spekülatör veya yatirimcilarin olacagina inanirlar.

STEEM ve SP sahipleri, topluluk üyeleri ellerinde SBD tutmaya istekli oldugu müddetce kaldirac kazanirlar. Bu kaldirac büyümeye katkida bulunurken büyüme kaynakli kazanclari da artirir. STEEM sahipleri eger fiyat düserse özsermayenin azalmasindan müzdarip olurlar. Kripto para birimi projeleri göstermistir ki, sermayeleriyle aga inanmaya istekli kullanici tabanini artirmanin getirdigi gelir, aga nihayetinde, gerileme döneminde olusacak bir özsermaye kaybindan daha fazla deger katmaktadir.

### Fiyat Yayinini Ayarlama

Dikkatli okuyucular fark edecektir ki, kisitli arzda faiz gelirli aktifler -diger ayni varliktan faiz kazanma firsatlarina bagli olarak- dayanak varliktan daha düsük ya da yüksek ticaret yapabilir. Amerikan Dolarina sabitlenmis bir varlik üzerindeki yüksek faiz ile, bir cok insan artik onun degeri $1 olmayana kadar kisitli arzdaki Steem Dolarina ragbet edecektir. Ekonomide Imkansiz üclem[^4] olarak bilinen; asagidaki üc maddeye ayni anda sahip olunamayacagini anlatan bir ilke vardir:

1. Sabit bir döviz kuru
2. Özgür sermaye akisi
3. Bagimsiz bir para politikasi

Eger Steem yayin üreticileri, faiz oranlari üzerinde tümüyle kontrol sahibiyken ayni zamanda onlara Steem Dolari yaratma ya da yok etme imkani taniyacak bagimsiz bir para politikasina sahip olma hedefi koyarlarsa problemlerle karsilasirlar. Imkansiz üclem der ki, Steem Dolari ya sermaye akisini sinirlandirmali ve Amerikan Dolari ile dalgali kura sahip olmali ya da faiz oranlari üzerinde kisitli kontrole sahip olmali.

Steem yayin üreticilerinin öncelikli kaygisi SBD ile Amerikan Dolari (USD) arasinda bire-bir dönüsümü sürdürmektir. SBD'nin $1.00 USD'den fazlaya alinip satildigi her durumda faiz ödemeleri durdurulmalidir. Borclanma üzerindeki %0 faize ragmen hala kar payina ragbet olan bir piyasada, piyasanin toplulugun borclanmak istediginden dafa fazla kredi saglama egiliminde oldugunu söylemek yanlis olmaz. Eger bu gerceklesirse SBD $1.00'dan daha fazla olarak deger bulur ve toplulugun da eksi oranlarda faiz isletmekten daha fazla yapabilecegi bir sey yoktur.

Eger borclanmanin mülkiyete orani düsükse ve SBD $1.00'dan asagiya alinip satiliyorsa, o zaman faiz oranlari artirilmalidir. Bu daha fazla insani elinde SBD tutma konusunda cesaretlendirir ve fiyati destekler.

Eger SBD $1.00'dan daha aza alinip satilirsa ve borc-mülkiyet orani yüksekse, o zaman fiyat yayinlari yukari dogru ayarlanmali ve SBD basina daha fazla STEEM verilmelidir. This will increase demand for SBD while also reducing the debt-to-ownership ratio and returning SBD to parity with USD.

Assuming the value of STEEM is growing faster than Steem is creating new SBD, the debt-to-ownership ratio should remain under the target ratio and the interest offered benefits everyone. If the value of the network is flat or falling, then any interest offered will only make the debt-to-ownership ratio worse.

In effect, feed producers are entrusted with the responsibility of setting monetary policy for the purpose of maintaining a stable peg to the USD. Abuse of this power can harm the value of STEEM so SP holders are wise to vote for witnesses that can be counted on to adjust the price feed and interest rates according to the rules outlined above.

If the debt-to-ownership ratio gets dangerously high and market participants choose to avoid conversion requests, then the feed should be adjusted to increase the rate at which STEEM paid for converting SBD.

Changes to the interest rate policy and/or any premiums/discounts on the STEEM/SBD conversion rate should be a slow and measured response to long-term average deviations rather than attempting to respond to short-term market conditions.

It is our belief that these rules will give market participants confidence that they are unlikely lose money by holding SBD purchased at a price of $1.00. We fully expect there to be a narrow trading range between $0.95 and $1.05 for SBD under normal market conditions.

## Subjective Contributions

Subjective Proof of Work presents an alternative approach to distributing a currency that improves upon fully *objective* Proof of Work systems such as mining. The applications of a currency implementing *subjective* proof of work are far wider than any *objective* proof of work system because they can be applied to build a community around any concept that has a sufficiently defined purpose. When individuals join a community they buy into a particular set of beliefs and can vote to reinforce the community values or purpose.

In effect, the criteria by which work is evaluated is completely subjective and its definition lives outside the source code itself. One community may wish to reward artists, another poets, and another comedians. Other communities may choose to reward charitable causes or help advance political agendas.

The value each currency achieves depends upon the demand for influence within a particular community and how large the market believes each community can get. Unlike prior systems, subjective proof of work enables a community to collectively fund the development of whatever it finds valuable and enables the monetization of previously non monetizable time.

### Distributing Currency

There are two ways people can get involved with a crypto-currency community: they can *buy in*, or they can *work in*. In both cases users are adding value to the currency, however, the vast majority of people have more *free time* than they do *spare cash*. Imagine the goal of bootstrapping a currency in a poor community with no actual *cash* but plenty of *time*. If people can earn money by working for one another then they will bootstrap value through mutual exchange facilitated by a fair accounting/currency system.

Distributing a currency to as many people as possible in a manner that is generally perceived as fair is a challenging task. The tasks that can be entirely evaluated by an objective computer algorithm are limited in nature and generally speaking have limited positive external benefits. In the case of Bitcoin-style mining, it can result in the production of specialized hardware and cause people to invest time developing more efficient algorithms. It may even help find prime numbers, but none of these things provide meaningful value to society or the currency holding community at large. More importantly, economies of scale and market forces will end up excluding everyone but experts from participating in this kind of distribution. Ultimately, computation-based mining is just another way of *buying in* because it requires money to pay the electric bill or the development of hardware necessary to do the work.

In order to give everyone an equal opportunity to get involved and earn the currency people must be given an opportunity to work. The challenge is how to judge the relative quality and quantity of work that individuals provide and to do so in a way that efficiently allocates rewards to millions of users. This requires the introduction of a scalable voting process. In particular it requires that authority to allocate funds must be as distributed and decentralized as possible.

The first step in rewarding millions of users is to commit to distributing a fixed amount of currency regardless of how much work is actually done or how users vote. This changes the question from being *“Should we pay?”* to *“Whom should we pay?”* and signals to the market that money is being distributed and is being auctioned off to whoever “bids” the most *work*. This is similar to Bitcoin committing to award 50 BTC to whoever finds the most difficult hashes. Like Bitcoin, all work must be done prior-to payout and nothing should be paid speculatively on the promise to do work in the future.

The next step is to reward everyone who does anything even remotely positive with *something*. This is accomplished by ranking all work done and distributing proportionally to its value. The more competitive the market becomes, the more difficult (higher quality or quantity) it becomes to earn the same payout.

### Voting on Distribution of Currency

Assume there is a fixed amount of money to distribute, and that those who have a long-term vested interest in the future value and utility of the currency are the ones who must decide how to allocate it. Every vesting user casts their votes on who did the best work and at the end of the day the available money for that day is divided proportional to the votes such that everyone with even one net positive vote gets something.

The naive voting process creates a N-Person Prisoner’s Dilemma[^5] whereby each individual voter has incentive to vote for themselves at the expense of the larger community goal. If every voter defects by voting for themselves then no currency will end up distributed and the currency as a whole will fail to gain network effect. On the other hand, if only one voter defects then that voter would win undeserved profits while having minimal effect on the overall value of the currency.

#### Voting Abuse

Regardless of how much money any one individual has, there are always many other individuals with similar wealth. Even the wealthiest individual rarely has much more than the next couple wealthiest combined. Furthermore, those who have a large investment in a community also have the most to lose by attempting to game the voting system for themselves. It would be like the CEO of a company deciding to stop paying salaries so he could pocket all of the profits. Everyone would leave to work for other companies and the company would become worthless, leaving the CEO bankrupt rather than wealthy.

Fortunately, any work that is getting a large concentration of votes is also gaining the most scrutiny (publicity). Through the addition of *negative-voting* it is possible for many smaller stakeholders to nullify the voting power of collusive groups or defecting large stakeholders. Furthermore, large-stakeholders have more to lose if the currency falls in value due to abuse than they might gain by voting for themselves. In fact, honest large stakeholders are likely to be more effective by policing abuse and using negative voting than they would be by voting for smaller contributions.

The use of *negative-voting* to keep people from abusing the system leverages the *crab mentality* that many people have when it is perceived that one individual is profiting at the expense of everyone else. While crab mentality normally refers to short-sighted people keeping good people down, it is also what allows good people to keep bad people down. The only “problem” with crab mentality is when people *wrongly believe* someone is profiting at everyone else's expense.

**The Story of the Crab Bucket**[^6]

A man was walking along the beach and saw another man fishing in the surf with a bait bucket beside him. As he drew closer, he saw that the bait bucket had no lid and had live crabs inside.

"Why don't you cover your bait bucket so the crabs won't escape?", he said.

"You don't understand.", the man replied, "If there is one crab in the bucket it would surely crawl out very quickly. However, when there are many crabs in the bucket, if one tries to crawl up the side, the others grab hold of it and pull it back down so that it will share the same fate as the rest of them."

So it is with people. If one tries to do something different, get better grades, improve herself, escape her environment, or dream big dreams, other people will try to drag her back down to share their fate.

Eliminating “abuse” is not possible and shouldn’t be the goal. Even those who are attempting to “abuse” the system are still doing work. Any compensation they get for their successful attempts at abuse or collusion is at least as valuable for the purpose of distributing the currency as the make-work system employed by traditional Bitcoin mining or the collusive mining done via mining pools. All that is necessary is to ensure that abuse isn’t so rampant that it undermines the incentive to do real work in support of the community and its currency.

The goal of building a community currency is to get more “crabs in the bucket”. Going to extreme measures to eliminate all abuse is like attempting to put a lid on the bucket to prevent a few crabs from escaping and comes at the expense of making it harder to add new crabs to the bucket. It is sufficient to make the walls slippery and give the other crabs sufficient power to prevent others from escaping.

### Rate Limited Voting

A major part of minimizing abuse is the rate-limiting of voting. Individual users can only read and evaluate so many work items per day. Any attempt to vote more frequently than this is a sign of automation and potential abuse. Through rate limiting, stakeholders who vote more frequently have each vote count for less than stakeholders who vote less frequently. Attempts to divide tokens among multiple accounts also divides influence and therefore does not result in a net increase in influence nor bypass the rate-limit imposed on voting.

Users are allotted a fixed amount of voting power. Voting power is multiplied by a user’s vesting tokens to determine how much share in the reward pool should be allocated to a given work item. Every vote that is cast uses a percentage of remaining voting power. Users can vote for more posts, but each vote will be worth less, and it will take longer to reach full voting power again. Voting power recharges at a fixed linear rate of 20% per day.

### Payout Distribution

One of the primary goals of Steem’s reward system is to produce the best discussions on the internet. Each and every year 75% of the yearly inflation is distributed to users submitting, voting on, and discussing content. At the size of Bitcoin this could be several million dollars per day being given to the top contributors.

The actual distribution will depend upon the voting patterns of users, but we suspect that the vast majority of the rewards will be distributed to the most popular content.

Zipf’s Law[^7] is one of those empirical rules that characterize a surprising range of real-world phenomena remarkably well. It says that if we order some large collection by size or popularity, the second element in the collection will be about half the measure of the first one, the third one will be about one-third the measure of the first one, and so on. In general, the k th-ranked item will measure about 1/k of the first one.

![](\img_the_new_marketplace.png)

Taking popularity as a rough measure of value, then the value of each individual item is given by Zipf’s Law. That is, if we have a million items, then the most popular 100 will contribute a third of the total value, the next 10,000 another third, and the remaining 989,900 the final third. The value of the collection of n items is proportional to log(n).

The impact of this voting and payout distribution is to offer large bounties for good content while still rewarding smaller players for their long-tail contribution.

The economic effect of this is similar to a lottery where people overestimate their probability of getting votes and thus do more work than the expected value of their reward and thereby maximize the total amount of work performed in service of the community. The fact that everyone “wins something” plays on the same psychology that casinos use to keep people gambling. In other words, small rewards help reinforce the idea that it is possible to earn bigger rewards.

### Payouts

When a post receives a payout it takes the form of 50% SBD and 50% SP. The Steem Power give the user increased voting and transaction power while the SBD gives the user an immediate benefit in a stable currency. As we’ve already discussed at length, SP is designed to encourage long-term holding rather than short-term selling. This encourages more users to have a vested interest in the long-term success of the platform.

Users also have the option to be paid in 100% SP, as well as decline payout on posts. When a user declines payout on a post, the money that would have been paid to them remains in the rewards pool, to be distributed to other users.

# Consensus Algorithm

Consensus is the process by which a community comes to a universally recognized, unambiguous agreement on piece of information. There are many algorithms society has developed for reaching consensus about who owns what. Every government on earth is a primitive consensus algorithm whereby the population agrees to abide by a certain set of rules enshrined in a constitution. Governments establish courts, judges, and juries to interpret the subjective facts and render a final decision. Most of the time people abide by the decision even if it was wrong.

The algorithms used by cryptocurrencies provide a better way to reach consensus. Cryptographically signed testimony from individuals is recorded in a public ledger that establishes the absolute global order of events. A deterministic computer algorithm can then process this ledger to derive a universally accepted conclusion. So long as the members of a community agree on the processing algorithm, the result of the algorithm is authoritative.

The primary consideration is determining what testimony is allowed to enter the public record. Systems should be designed to minimize the potential for censorship. Censorship on the public ledger is similar to preventing someone from voting in an election. In both cases an individual is prevented from impacting the global consensus.

## Consensus in Steem

Conceptually, the consensus algorithm adopted by Steem is similar to the consensus algorithm adopted by companies throughout the world. People with a vested interest in the future value of Steem vote to select individuals responsible for including testimony in the public record. Voting is weighted proportional to each individual's vested interest.

In the world of cryptocurrencies, the public record is commonly referred to as a *blockchain*. A *block* is a group of signed transactions.

With Steem, block production is done in rounds. Each round 21 witnesses are selected to create and sign blocks of transactions. Twenty (20) of these witnesses are selected by approval voting and one is timeshared by every witness that didn’t make it into the top 20 proportional to their total votes. The 21 active witnesses are shuffled every round to prevent any one witness from constantly ignoring blocks produced by the same witness placed before. Any witness who misses a block and hasn't produced in the last 24 hours will be disabled until they update their block signing key.

Bu süreç, herkesin en yüksek sıralamalarda bulunmaya yetecek kadar popüler olmasına bakılmaksızın, herkesin blok üretimine katılma potansiyeli taşırken, en iyi güvenilirliği sağlamak üzere tasarlanmıştır. İnsanların top 20 seçilmiş witnessların önüne geçebilmesi için 3 ayrı yolu vardır: Herkes gibi top 20 de bulunmayanlarla beklemek veya oy gücünüzü arttırmak için SP satın almak. Genel olarak konuşursak, piyasayı sansürlemek seçilmiş witnesslar için işlerini kaybetmek için birebir, bu nedenle Steem ağında böyle bir şey olması olası değil.

Aktif witnesslar önceden bilindiği için, Steem witnessları her 3 saniyede blok üretmeleri için sıralayabilmektedir. Witnesslar bloklarını NTP protokolü ile senkronize eder. Bu algoritmanın bir benzeri bir yılı aşkın süredir BitShares ağında kullanılarak güvenilirliğini kanıtlamıştır.

# İşlem Ücretlerini Ortadan Kaldırıyor

Steem ağa katkıda bulunları ödüllendirmek için çabalıyor. Katkıda bulunmak isteyenlerden her defasında ücret alınması bu düşüncenin tam tersi olurdu.

Blokzinciri teknolojisi şu an için spam önlemek için işlem ücretlerine dayalıdır. Bu ücretler bilinen mikroödeme sorunlarından dolayı sıkıntı yaşıyor ve blokzincirlerinin değeri düşük hareketler için kullanılmasını engelliyor. Gerçekten merkezsiz uygulamalar kullanıcılarına ücretsiz hareket sunarak merkezi alternatiflerin önüne geçmelidir. Bu kağıt Steem'in bu konuya ilişkin ücretlere olan bağlantısını ortadan kaldırarak daha önceden mümkünatı olmayan merkezsiz işlemlerin mümkün olmasını vurguluyor.

## İşlem Ücretleri Sorunu

Blokzincirleri bütün hareketlerin, eşlere gönderildiği merkezsiz ağlardır. Her bir blok üretildiğinde bu blok beklemede olan hareketlerin çoğunu ya da hepsini içerebilir. Tüm blokzincirleri zararlı kullanıcıların mevcut ağın kapasitesini değersiz hareketlerle tüketmemesi için bir çözüm bulmalıdır. Bu değersiz hareketler değeri olan hareketlerin ağdaki işlemini engelleyerek uzun vadede ağı yok edebilir.

Şu zamana kadar blokzincirleri tarafından kabullenilen çözüm ise minimum işletim ücretleridir. Sadece bir kaç sent ağa saldırmayı pahalı ve değersiz kılabilir. Bu yaklaşım spam problemlerini çözerken, yenilerini tanıtmaktadır. E-posta spam problemini her eposta gönderildiğinde alınan bir ücret ile çözdüğünüzü düşünün: Kimse eposta göndermezdi.

### Mikroödemeler Çalışmıyor

İşlem ücreti almanın ana problemi mikroödemelerin işe yaramamasıdır, özellikle düşük değerli kullanıcı hareketleri için. Her bir harekette işlem ücreti alındığında, merkezsiz bir ağın işleyebileceği hareket tiplerini sınırlamaktadır. İşlem ücretlerinin gerekliliği her ne kadar kabul edilebilir bir argüman olsa da, kullanıcılar hala yaptıkları en küçük işlem için ücret ödemekten nefret ediyor.

Düşünün, her gün kullandığımız web siteleri şifremizi değiştirmek istediğimiz her sefer bizden ücret isteseydi. Kullanıcılar bazı şeylerin ücretsiz olmasını bekliyor. Kullanıcıların eylemlerinin küçük bir ücrete tabi olup olmadığına karar verdirmek bir süre sonra vazgeçmelerine sebep olacak bir durum oluşturuyor. Bazı hareketler bir karar gerektirmeyecek kadar değersiz olabilir fakat aynı zamanda otomatik karar verilecek değerde de olabilir. Her satın alma işleminde belli bi miktarda kaygı vardır. Ne kadar küçük olursa olsun, ve bu kullanılan arayüz veya gereken zamandan değil de, genel olarak karar vermedendir.

Mikroödemeler, diğer her ödeme türleri gibi bir karşılaştırmaya ihtiyaç duyarlar. *"Bu kadar X bu kadar Y'ye değer mi?* bu durumunu yaratacağı değiştirilemeyecek minimum zihinsel bir düşünce vardır. Çünkü kullanıcının hiç düşünmeden onaylayacağı tek hareket, hiç bir zararı olmayacak olan bir harekettir bu da... hiç bir harekete eşittir.

- Clay Shirky[^8]

Finansal ödemeler dünyasında küçük ücretler kabul edilebilirdir çünkü, hareketin değeri ücretin değerine nazaran daha yüksektir ve alıcı zaten satın almada kararını kılmıştır. Potansiyel blokzinciri uygulamalarının dünyası sadece finansal ödemelerden çok daha büyüktür ve kullanıcılar tarafından kabul edilmeyecek ücretler içeren önemli hareketleri içerir.

BitShares, NXT, Ripple, Counter Party ve Stellar gibi sistemlerin hepsi kullanıcıların blokzinciri üzerinde emirlerini kullanmasına izin verir ve kullanıcılarından bu eylemleri için küçük bir ücret alır. Daha sonra eğer kullanıcı emrini iptal etmek isterse, başka bir ücret daha ödemek zorundadır. Ethereum gibi sistemler ise mikrooödemeleri bir sonraki seviyeye taşırlar: her hesaplama için ücret almak. Bütün bu sistemler sanki merkezsiz bir arama motorunun her arama için ücret alması ve Google'dan kullanıcı çekememesi gibi nedenlerle aynı sebepten kullanıcıları etkilemekte zorlanırlar. Hizmetin ne kadar iyi olduğu önemli değildir, kullanıcılar bazı şeylerin ücretsiz olmasını bekler. Kullanıcı farklı bir ücret yapısıyla genel anlamda daha fazla ödese bile, bu geçerlidir.

### Ücretler Girişlere Engeldir

Her türlü ücret yeni kullanıcıların girişine engel olur. Birisi Ethereum'u ilgilendiren herhangi bir işlem yapmak istediğinde öncelikle biraz ETH'ye ihtiyaç duyacaktır. Ethereum sistemi üzerinde merkezsiz bir uygulama yapmak isteyen herhangi birisi uygulama ücretini kullanıcılara yıkmak zorundadır. Kriptobirim satın almak kolay bir iş değildir ve genel olarak 10$ altı miktarlar için mantıklı değildir. Bu da yeni çıkan bir merkezsiz uygulamayı denemek isteyen yeni bir kullanıcı 10$'dan ayrılmak istediğine karar vermiş olmalıdır.

### Değişken Ücretler

Zaman içinde ağın ücretleri ayarlaması gerekir. Bu kapasitedeki bir oynama veya zaman içerisinde değer artışı nedeniyle kaynaklanabilir. Kullanıcılar tahmin edilebilir ücretleri ve garantilenmiş hizmeti severler. Yüksek kullanım durumlarında dinamik bir biçimde ücretleri arttırmak mümkün olmakla beraber, kötü bir kullanıcı tecrübesine yol açar.

### Sybil Saldırıları

Bazı merkezi websiteleri spamı önlemek için bir nevi kimlik onayı ve hız sınırlaması kullanır. reCAPTCHA [^9] gibi basit bir şey bile sahte hesapların yaratılmasını engelleyebilir. Eğer birisi hesabını kötüye kullanıyorsa merkezi websiteler hesabı kapatma özgürlüğüne sahiptir.

Merkezsiz bir sistemde kullanıcıları yasaklamanın direkt bir yolu olmadığı gibi reCAPTCHA ve hız sınırlaması da mümkün değildir. Aslında, bu mümküniyetsizlik blokzinciri teknolojisin ana satış noktalarından biridir.

### Rezerv ve Kısmı Rezerv

Blokzinciri sistemini bir İnternet Servis Sağlayıcısı (ISS) gibi inceleyelim, şehirdeki tüm kablolara sahip olan ve bir zamanda verebileceği maksimum trafik limiti olan bir ISS. Şehirde yaşayan insanlar ISS'den pay alarak mevcut olan trafiğin bir kısmından yararlanabilirler.

ISS'in iki seçeneği vardır. "rezerv" ya da "kısmi rezerv" sistemini kullanmak. Rezerv sisteminde kullanıcı mevcut olan maksimum trafiğin sadece payını aldığı kadarını alabilmesidir. Çünkü herkes aynı anda interneti kullanmaz, şehrin ağı önemli ölçüde az kullanılır.

Kısmi rezerv sisteminde ise kullanıcılar satın aldıkları payın değerindeki trafikten daha fazla trafik alabilirler, şehirdeki herkesin aynı anda internet kullanmadığı sürece tabii. Kısmi rezerve sahip olmanın sorunu ise herkesin aynı anda ağa bağlanıp internet kullanmak istediğinde oluşan tıkanıklılıktır. ISS bu tür durumlarda trafiklere öncelik vermek için bir yol bulmalıdır. Aşırı durumlarda, tamamen tıkanmış bir ağ tekrardan rezerv sistemine geçmelidir. Zor olan şey ise, doğru kısmi rezerv oranını bulmaktır.

## Mikroödeme Kanalları yerine Trafik

Mikroödemelere çare *dinamik kısmi rezerv* implemetasyonudur. Bu model altında blokzinciri rezerv oranını tıkanılılığa göre otomatik olarak ayarlayabilr. Blokzinciri oranı ayarlarken kısa süreli dalgalanmalar için pay bırakarak bir hedef belirler. Dalgalanmalar olduğunda blokzinciri pay-başına-trafik oranını düşürür. Dalgalanma bittiğinde ve ekstra kapasite olduğunda blokzinciri tekrardan yavaşça pay-başına-trafiği yükseltebilir.

Bir kullanıcı tarafından kullanılan trafik kullanıcının kullanım zamanının değişeceği göz önüne alınarak uzun süreli periyodlar ile hesaplanmalıdır. Kullanıcı oturum açıp, aynı anda bir sürü şey yapıp, çıkmaya meyillidirler. Bu da kısa süreli incelendiğinde fazla gözüken trafiğin aslında uzun süre olarak tam tersi olması anlamına gelir. Eğer süreç çok fazla uzuyorsa sistem kısa sürekli patlamalar için rezerv oranını yeteri kadar hızlı ayarlayamayabilir. Eğer süreç çok kısa ve toplu kullanım varsa normal kullanıcılar için büyük bir etkisi olacaktır.

Tahminlerimize göre, kullanıcıların trafik hesaplamalarını haftalık yapmak yeterlidir. Kullanıcı her hareketi imzaladığında, imzaladıkları hareket kullanıcının geçmiş hareketlerinin ortalaması alınarak hesaplanır. Kullanıcıların hareketleri genel ortalamasının üzerine çıktığında, tekrar düşene kadar gecikmeli olacaktır.

### Kapasitenin Önemi

Blokzinciri kapasitesi aslında limitli değildir. Şu anki internet altyapısının teknolojik kapasitesi Bitcoin blok boyutunu 10MB'e arttırmak için yeterlidir, bu da gerekli bakiye miktarını faktörel olarak 10 kat azaltacaktır. Bitcoin şuanda saniyede 3 hareketi desteklerken, alternatif implementasyonlar saniyede 1000'in üzerinde hareketi destekleyecek kapasitedelerdir.

### Ücretler ile Karşılaştırma

Eğer bir kullanıcının her hafta sadece 25$ dolar değerinde BTC gönderimi yaptığını ve her ödediklerinde 0.04$ cent ücret öderse, yılda 2 doların üstünde bir ücret ödeyecektir. Kullanıcı o 25$ doların sadece 8%ini kazanarak ücretleri ödemek için harcadığı miktarı amorti edebilir. Chances are that users were going to hold their money on the blockchain anyway, so this user with $25 worth of BTC just saved $2 over the course of a year by adopting a rate-limiting approach rather than a fee-based approach. With just $175 they could transact every single day and save $14 per year.

### Hesap Oluşturma

Steem'in hesap bazlı sistemi ve genel olarak bilinen bakiyeleri trafik bazlı hız limitleme algoritmasının implementasyonunu kolaylaştırıyor. Minimum gerekli miktarın altında bakiyesi olan hesapların haftada en az bir hesap hareketi gerçekleştirmesi gerekmektedir. Bu da bütün yeni hesapların en az minimum bakiye miktarını bulundurmaları gerektiğini vurgular. Aynı zamanda daha küçük miktarlarda hareket sağlamak isteyen kullanıcılar bakiyeleri fazla olduğu ve hesabı kullanabilecekleri sürece bu işlemi gerçekleştriebilirler.

Kullanımın az olduğu zamanlarda oluşturulan minimum bakiyeleri hesapların ağ kullanımı arttığında kullanılamayan duruma düşme ihtimali bulunmaktadır. Bu bakiyeler istenildiği zaman büyük bir hesaba delege edilerek kullanılabilir.

Minimum bakiyenin altında ve kullanılamaz olan hesapların sayısını kontrol edebilmek için bütün yeni hesaplar minimum gereken tutarın en az 10 katı ile başlamalıdır. Bu şekilde eğer ağ kullanımı talebe oranla 10 kat artsa bile, hesap geçerli ve kullanılabilir kalacaktır.

Hesap oluştururken gelen herhangi bir bakiye başka bir kullanıcıdan gelmeli ve potansiyel sybil saldırılarını önlemek için token olarak oluşturulmamalıdır.

### Minimum Bakiyeleri Kararlaştırma

Kullanıcıların minimum bir bakiye bulundurmaya zorlama konsepti kullanıcının kendi değerinden gelir. [^10]. Herhangi bir işletme yürüten bilir ki her kullanıcının mutlak bir değeri vardır. İşletmeler yeni bir kullanıcıya sahip olmak için 30$ dan 200$'a kadar ücret ödeyebilirler. Bazen kullanıcılara direk ödeme yaparken bazen reklamlara öderler, ve yine bazı zamanlarda bazı işletmeler tüm kullanıcılarını satın almışlardır. Bir şirket kullanıcıyı kazandıktan sonra genel olarak onlara *ücretsiz hizmetler* sağlayarak başka yollar sayesinde üzerlerinden para kazanmak için kullanıcıları tutmalarını sağlar.

Ripple'ın minimum bakiye miktarı [^11] hesabın kullanım oranı ile birlikte yükselir ve yeni hesapların minimum o miktarda bakiye bulundurmasını gerektirir. Şu an için bu minimum bakiye miktarı yaklaşık 0.15$ cent'dir bu miktarda bizim daha öncesinde haftada bir kez özgürce hareket edilebilir olarak düşündüğümüz miktardan 0.10$ cent fazladır.

Bir blokzinciri kullanıcıların sahip olması gereken minimum değeri, minimum bakiye gereksinimi ile zorlayabilir. Blokzincirine yeni bir kullanıcı kazandırmak isteyen herhangi bir şirket o kullanıcının hesabını daha önceden minimum bakiye ile doldurarak sistemi kullanmasını sağlar. Requiring a relatively large fee ($1.00) to sign up new users will naturally force anyone offering free accounts to vet the quality and uniqueness of each account before registering them with the blockchain.

Maintaining a minimum balance is effectively the same as making users pay transaction fees with the interest they could have earned on their balance. The minimum balance is simply the balance required to earn enough interest to pay a fee in a relatively short period of time.

Fortunately, the minimum balance required can be as low as a dollar and this is something users can understand and appreciate. The opportunity cost of lost interest doesn’t incur the cognitive cost of a micro-fee and is far more acceptable to users.

The STEEM used to pre-fund an account is Powered Up in the new account (i.e., converted to Steem Power). A portion of the SP used to fund a new account may be delegated from the creator of the account. When a user is delegated SP, they may use the SP for voting and bandwidth purposes as if it were their own, but the ownership of the SP remains with the user who delegated it. A user may remove the delegation at any time. After a cool-down period, the SP is returned to their account.

### Effectiveness Relative to Fees

To compare the effectiveness of rate limiting to fees we must consider how the two systems react to intentional network flooding by an attacker. Under Bitcoin an attacker with $10,000 dollars could disrupt service for an entire day by filling every single block. The same attacker would be unable to disrupt service for even a single block under the dynamic fractional reserve rate limiting approach.

If we go to a more extreme case and assume the attacker holds 1% of all coins then we presume an attacker with $60 million dollars. Such an attacker could deny the Bitcoin blockchain service for 16 years unless the miners increased fees or capacity. Even if fees were raised to $15 per transaction, the attacker could still keep the network flooded for 16 days.

Under the rate limiting approach, someone who holds 1% of all coins with an intent to flood the network would achieve their goal for less than 30 seconds.

### Renting vs. Buying vs. Time Sharing

When someone owns a house they expect the right to use the house for free. If a group of people buy a house together then each can expect the right to use the house proportional to their percentage ownership in the house. A fee based blockchain is like renting the house from its owners, whereas rate limiting is like a timeshare among owners.

If a house is owned by multiple people then those individuals must decide how they wish to timeshare the house. Someone who owns 50% of the house but only uses it one weekend per year might expect to be paid by the individuals who take their unused time. This is the mindset of a fee based system.

On the other hand, someone who owns 50% of the house is speculating that demand for the house will increase in the future and they will be able to sell their stake for more. Any owner who owns more of a house than they use becomes a real estate speculator. With this mindset rather than collecting rent, they collect appreciation.

The value of a share is derived from how much time it can potentially grant its owner. Owning 1% of a house and getting it 1 weekend per year is the lowest value of a share. However, if half of the shareholders never use their weekend, then the value per timeshare rises to 2 weekends per year. If those inactive users instead opt to rent their unused time, then it falls back to 1 weekend per year. If those unused timeshares were sold to people who would use them then the value of a timeshare would fall by 50%. Unless the rent collected is greater than the fall in share value the timeshare owners are making an economic miscalculation.

Using this rationale we can assume that a system based on fees will either be more expensive for its users or be less profitable for its collective owners. An individual small owner may profit by renting out his small time slice, but only at the expense of all other timeshare owners. In effect, the cost of the falling timeshare value is shared among all owners whereas the profits are centralized in the single owner who decided to rent his share.

We can conclude from this that a blockchain is best served by not using usage fees at all. If a usage fee were to be charged as an alternative to rate limiting, then it should be the equivalent of buying enough timeshares and committing to hold them long enough to gain the right use it once.

Stated another way, a transaction fee should be equal to the minimum account balance necessary to transact once per week and it should be refunded at the end of the week. Assume the minimum account balance is $1 and allows someone to transact once per week. If someone with a $1 balance that wishes to perform 5 transactions at once they will have to increase their balance to $5 for a week either before or after their transactions.

In theory a market could form where users can borrow the stake required. In practice it is more efficient for users to simply buy and sell the timeshares necessary to meet their desired usage rate. In other words, the cost of negotiating micro-loans is greater than the cost of maintaining a balance suitable for your maximum weekly usage.

Decentralized rate limiting of transactions can enable new types of decentralized applications that were not viable when every use of the application required a micropayment. This new model gives application developers the ability to decide if and when to charge their users for transactions.

# Perfomans ve Ölçeklenebilirlik

Steem agi, BitShares'i calistiran ayni teknoloji olan Graphene üzerine insa edilmistir. Graphene bir dagitik test agi üzerinde saniyede 1000'den fazla islemi destekleyekleyebildigini aleni bir sekilde kanitlamistir. Graphene, sunucu kapasitesi ve iletisim protokollerine yapilacak göreli basit gelistirmeler ile birlikte, saniyede10,000 ya da daha fazla sayida islemi kolaylikla ölcekleyebilir.

## Reddit Ölcegi

Steem Reddit'ten daha büyük bir kullanici tabani ile bas edebilmeye muktedirdir. 2015 yilinda Reddit'in 8.7 milyon üyesi genel ortalama olarak saniyede 23 yorum[^12]; üye basina da yilda 83 yorum üretmistir. Saniye basina iki paylasim ortalamasiyla, 73 milyon üst seviye paylasim mevcuttu. 7 milyara yakin begeni oyunun yarattigi, saniye basina 220 oy sekilde, bir ortalama oylama orani vardi. Tüm bunlar söylendiginde, eger Reddit blockhain üzerinde calisiyor olsaydi saniye basina 250 islem ortalamasina ihtiyac duyardi.

Steem bu sektör-öncüsü performansa erismek icin, saniyede 6 milyon islemi isleyebilen LMAX Exchange'den[^13] cikarilan dersleri ödünc almistir. Bu dersler icindeki anahtar noktalar:

1. Herseyi hafizada tut.
2. Cekirdek isletme mantigini tek bir dizide tut.
3. Kriptografik operasyonlari (hashler ve imzalar) cekirdek isletme mantiginin disinda tut.
4. Teyidi duruma-bagimli ve durumdan-bagimsiz denetlemelere böl.
5. Nesneye yönelik veri modeli kullan.

Steem bu basit kurallari takip ederek, optimizasyona adanmis önemli bir olmaksizin, saniyede 10,000 islemi isleyebilmektedir.

Yakin zamanda Intel tarafindan Optane™ teknolojisinin piyasa sürülmüs olmasi[^14] da göz önünde tutuldugunda herseyi hafizada tutmak artan bir sekilde uygulanabilirdir. Standart bir donanimin, hizli bir indexleme icin, Steem ile ilintili tüm isletme mantiginin -tüm postlar hafizada kayitli bir sekilde- tek bir dizide tutuluyor olmasi ile bas edebiliyor olmasi gerekir. Google bile tüm internete dair kendi indexlerini RAM'in icinde tutar. Blockchain teknolojisinin kullanilmasi veri kaybinin önüne gecmek icin verilerin baska makinalara kopyalanmasini gereksiz hale getirir. Optane™ teknolojisi benimsendikce RAM, direnç kazaniyorken daha da hizli hale gelecek. Bir diger deyisle, Steem ölçeklendirme icin ve gelecegin mimarisi icin tasarlanmistir.

# Paylasim & Arz

## Nihai Paylasim & Arz

Steem Agi 0 para birimi arzi ile ve Miner'lara, Proof of Work araciligiyla dakikada yaklasik 40 STEEM ve icerik ve küratörlük ödül havuzunun yaratilmasi icin harcanan her bir dakika icin de ilaveten 40 STEEM (Toplamda dakika basina 80 STEEM) olmak üzere dagitilan STEEM ile basladi. Sonrasinda, ag SP'ye dönüstüren kullanicilari ödüllendirmeye basladi. Bu noktada STEEM asagida özetlenen cesitli Katki Ödüllerinin muhtelif etkilerinden ötürü dakida basina yaklasik 800 STEEM oranina yükseldi:

Katki Ödülleri:

- Küratörlük ödülleri: Hangisi daha büyük ise, blok basinda 1 STEEM ya da yilda 3.875%
- Icerik Yaratimi ödülleri: Hangisi daha büyük ise, blok basina 1 STEEM ya da yilda 3.875%
- Blok üretimi ödülleri: Hangisi daha büyük ise, blok basina 1 STEEM ya da yilda 0.750%
- 864,00. blok öncesi POW kapsama ödülleri: Blok basina 1STEEM (raunt basina 21 STEEM olarak ödüllendirilir)
- 864,00. blok sonrasi POW kapsama ödülleri: Hangisi daha büyük ise, blok basina 0.0476 STEEM (raunt basina 1 STEEM olarak ödüllendirilir) ya da yilda 0.750%.
- Likidite ödülleri: Hangisi daha büyük ise, blok basina 1 STEEM (saat basina 1200 STEEM olarak ödüllendirilir) ya da yilda 0.750%

### Power ödülleri:

- Steem Power ödülleri: Yukaridaki ödüller tarafindan yaratilan her bir STEEM icin, 9 STEEM tüm Steem Power sahipleri arasinda bölüstürülür.

### SBD operations:

- SBD rewards: A percentage of SBD value is created at an APR set by the witnesses and paid to SBD holders as SBD

The overall supply picture is complicated by the effect of SBD operations, which may result in large-scale creation or destruction of STEEM through feed rate following and SBD rewards, as discussed in the SBD section. Other, smaller-scale complicating effects also exist, including unclaimed incentives (e.g. block rewards for missed blocks), and abandoned accounts.

## Current Allocation & Supply

Starting with the network's 16th hard fork in December 2016, Steem began creating new tokens at a yearly inflation rate of 9.5%. The inflation rate decreases at a rate of 0.01% every 250,000 blocks, or about 0.5% per year. The inflation will continue decreasing at this pace until the overall inflation rate reaches 0.95%. This will take about 20.5 years from the time hard fork 16 went into effect.

75% of the new tokens that are generated go to fund the reward pool, which is split between authors and curators. 15% of the new tokens are awarded to holders of SP. The remaining 10% pays for the witnesses to power the blockchain.

### Impact of Token Creation Rate

It is often said that a coin with an inflationary model is not sustainable, but we know from countless real-world examples that the quantity of money does not have a direct and immediate impact on its value, though it certainly plays a role.

From August 2008 through January 2009 the U.S. money supply[^15] grew from $871B to $1,737B, a rate of over 100% per year and then continued to grow at about 20% per year for the next 6 years. All told the money supply in the U.S. has grown by 4.59x over less than 7 years. During that same time, the value of the dollar relative to goods and services has fallen less than 10% according to the government's price index[^16]. This real-world example demonstrates that supply is only one component of price.

For the first 2 years of Bitcoin’s life the network sustained an annual inflation rate[^17] of over 100%. For the first 5 years it was over 30%, and for the first 8 years it was over 10%. All told the total “spending” Steem does to fund content, curation, and block production amounts to less than 10% APR.

The price of a digital commodity, like STEEM, is driven by both supply and demand. When a long-term holder decides to exit, the supply of STEEM on the market will increase and push the price down. This downward pressure is countered when a new long-term holder decides to buy up the STEEM and convert it back into SP. Additional supply and demand may be be added due to market speculators buying and selling liquid STEEM based on their predictions of the future market price.

# The Power of Steem

Steem recognizes that the value of all user contributions (posts and votes) is greater than the sum of the parts. A single comment is worth next to nothing, but millions of curated posts is worth many millions (or possibly even billions) of dollars. A single vote provides little curation value, but billions of votes is very effective curation. Content without curation is of limited value. Given all the content of the Internet minus the links between it, Google would struggle to produce useful search results. It is the links between information that give it significant value.

Because everyone benefits, everyone should pay. In other words, no individual user should be expected to pay for anything, but instead should be paid for everything they do that brings value to Steem. All we need to do is ascertain which user contributions bring a social network value and which ones don’t.

Collectively Reddit users vote 220 times per second and make 23 posts per second. Reddit is valued between $500 million[^18] and $4 billion[^19] which means that each and every upvote and post is worth between $0.06 and $0.50 assuming the value of Reddit is mostly within the past year’s worth of activity. One could argue that most of the value of Reddit is the near-real-time discussions that have occurred within the past week which would dramatically increase the value of new activity. People go where people are today, not where people were last year.

## No Micropayments, Tips Optional

Existing attempts at integrating a cryptocurrency into a social media platform have focused on enabling users to pay one another. Many services have attempted to introduce tipping. The theory is that if we make tipping simple enough then more people will do it. Other services attempt to get people to pay to promote or boost their content’s ranking. Still others attempt to build small prediction markets on how many tips an article will receive.

All of these approaches boil down to micropayments. They differ only in who is making the payment. They all suffer from insufficient engagement of people making the micropayments. In the search for incentivised content production entrepreneurs have been so focused on who should pay that they missed the obvious reality: everyone benefits from everyone’s actions so everyone should pay or no one should pay, depending on how you look at it.

Steem bypasses micropayments completely because when a user upvotes a post it is the community that pays the bill. The same amount of money will be spent whether the user upvotes a post or not and the funds will not come from the voter.

The mental energy associated with making an economic decision becomes a barrier to participation for most people.

*We already face a multitude of choices everyday with regards to what to access online in this digital era of the information explosion, and every additional decision that we must make simply adds on to the uncertainty and anxiety we face. Micropayment supporters believe that a simplified implementation can minimize the intrusiveness of micropayments and improve user experience, but their argument only creates double standards for the decision making process \[2\]. A transaction cannot simultaneously be worth enough to warrant a decision and worth so little that the decision is automatic. **The only transactions that users can approve without thought are ones that cost them nothing**, thus any micro-transaction of positive value will incur mental costs through its requiring a decision. Furthermore, mental transaction costs actually rise below a certain threshold value, a phenomenon that places micropayments at an even greater disadvantage. For instance, it is easy to think that a copy of today's newspapers costs $1, but readers face much more difficulty and anxiety in deciding on the value of each article or word. Such a dilemma will only be replicated and exacerbated if all online content were to be broken down into their components and individually valued within a micropayment system.*

-Micropayments: A Viable Business Model[^20]

Under Steem, micropayments are paid to content producer, but those who vote for the content do not pay. Instead, the cost of the reward is paid for via new tokens. Someone can join the system, vote to pay someone, and then exit the system with more money than they started with (assuming the market valuation of the Steem system remained constant). In other words, the micropayment solution provided by Steem provides a user-experience similar to many widely used websites that have user-moderated content.

Furthemore, Steem pays people to figure out who should be paid! This kind of thinking is revolutionary.

## Value is in the Links

The Internet would lose the vast majority of its value if all links among content were removed. It is the relationship among web pages that allows Google to identify the best apple pie recipe among the 16 million results. Without the links the only information Google would have is word frequency.

Links can take many forms and have adapted over time. Every time a user votes on content in a social network they add a connection between themselves and the content. This in turn links the consumer to the producer through the content. The more connections a network has the more valuable the information becomes. It is the relative and intentional connectedness of information that gives it value.

A social network can maximize the value extracted from a set of content by maximizing the quantity and quality of connections. Curating content is expensive and time consuming while being near impossible for computers to perform in the absence of links. Steem rewards users who are among the first to find and identify new content.

By incentivising curation the Steem network is able to use automated algorithms to extract the most valuable information from a massive amount of content.

## Solving the Cryptocurrency Onboarding Problem

It isn’t easy to get into cryptocurrency[^21]. Someone who discovers Bitcoin and wants to try it out quickly learns that they will need to sign up with an exchange and fund their account with a credit card or wire transfer. What would Facebook’s adoption rate have been like if you had to fork over money and a two forms of ID?

Steem solves this problem by giving everyone a way to get paid for doing simple, but valuable, tasks. This will help to widely distribute STEEM tokens. This is helpful because cryptocurrencies have a network effect (i.e. more users make it more useful; for an extreme example, consider that if Satoshi had kept 100% of Bitcoin for himself, Bitcoin would be worthless.)

## Solving the Cryptocurrency Liquidation Problem

A currency that is difficult to use or impossible to sell has little value. Someone who comes across $1.00 worth of Bitcoin will discover that it costs more than $1.00 to sell that Bitcoin. They have to create an account with an exchange, perform KYC validation, and pay fees. Small amounts of cryptocurrency are like small change that people are unwilling to bend over to pick up.

Merchants give users a way to quickly convert their cryptocurrency into tangible goods and services. Merchants need a currency pegged to their unit of account, normally dollars. Accepting a volatile currency introduces significant accounting overhead.

Merchants will accept any currency if it increases their sales. Having a large user base with a stable currency such as SBD lowers the barrier to entry for merchants. The presence of merchants improves the system by creating an off-ramp for users to exit the system without going to the trouble of using an exchange.

Another way that people can liquidate the small amounts of cryptocurrency they receive from participating on the Steem platform is through *tipping* others. This is like leaving the small change as a tip for your waiter. When enough people leave small tips it adds up to a meaningful amount. You and the waiter each gain a benefit from the tip.

## Censorship

Steem is a decentralized network that is operated by witnesses in jurisdictions around the world. All user actions are publicly recorded on the blockchain, and can be publicly verified. This means that there is no single entity that can censor content that is valued by STEEM holders.

Individual websites such as steemit.com may censor content on their particular site, but content published on the blockchain is inherently broadcast traffic and mirrors all around the world may continue to make it available.

Freedom of speech is the foundation of all other liberties and any infringement upon freedom of speech undermines the only peaceful means of reaching consensus: discussion. Without free discussion voters cannot be fully informed, and uninformed voters are a greater threat to society than losing the right to vote. Censorship is a means of stealing votes through limiting public discourse. Steem is committed to enabling free speech and building a free society.

## Solving Organic Discovery via Search Engine Optimization

Most cryptocurrencies generate little value for those who are not actively using the network. Steem, by contrast, generates content and encourages users to share it. This content gets indexed by search engines and ultimately will bring value to a large number of passive users. This search traffic creates organic advertising for the Steem network and grows the network effect.

## Shifting Toward Blockchain-based Attribution

The internet represents the easiest medium for distributing information in the world. With that said, it can be a frightening place for content creators who would like to own their content and have it shared with proper attribution. On current social media platforms, attribution is something that can be lost overnight - a posted video or image can be replicated and re-shared without consent or regard for the creator.

Under blockchain-based social media, a creator or author would always be able to point to a public record and timestamp showing proof of their content origination. In a circumstance where a creator would like to address those who have re-shared without permission or attribution, blockchain-based records provide public proof that the content was posted by a particular user at a particular time. In the future, blockchain-based attribution could come to be recognized by governments for its authenticity and could hold weight in court, which would give content creators greater powers to control their work.

While a timestamping service can be built on almost any blockchain, and several efforts exist to build this kind of service on the Bitcoin network, Steem has a useful advantage in this realm because content publishers are “first class citizens” -- the Steem blockchain is built from the ground up around the use case of content publication, which allows content creators to have the blockchain to validate their content at a certain point in time simply by writing their post using the same authoring tools used by other Steem users.

## Replacing Advertising with Blockchain-based Content Rewards

Under most content monetization models, content creators leverage advertising in one form or another. Many creators recognize how advertising may diminish their work’s value to the consumer, yet creators very often must seek returns on their time by monetizing. Advertising represents a double-edged sword: With ads, a creator can make money most easily. Without ads, monetization is difficult but the content is richer.

Creators posting to social media outlets that are connected to Steem may monetize merely by having their work recognized (or ”liked”) by the Steem community. Blockchain-based payouts are completely digital and have no middle-man. Therefore monetization by blockchain-based content rewards should be faster and much lower barrier to use than monetization by advertisements.

# Sonuç

Steem is an experiment designed to address challenges in the cryptocurrency and social media industries by combining the best aspects from both. Steem presents earning opportunities to content creators and internet readers in ways that have not existed within the social media industry. Within Steem, individuals earn real rewards online that are directly correlated to their contributions. Those rewards may have dollar value due to the market price discovery and liquidity of Steem, and the people who hold Steem may have more exclusive earning powers than those who do not.

[^1]: Reddit’s Cryptocurrency, Forbes, Erika Morphy, October 2014 http://www.forbes.com/sites/erikamorphy/2014/10/01/reddits-cryptocurrency-could-have-many-uses/\#4e07b05332b9

[^2]: Sweat Equity, Investopedia http://www.investopedia.com/terms/s/sweatequity.asp

[^3]: Meta-moderation is a second level of comment moderation. Users are invited to rate a moderator's decision in order to improve moderation. https://en.wikipedia.org/wiki/Meta-moderation\_system

[^4]: The Impossible Trinity, economic theory https://en.wikipedia.org/wiki/Impossible\_trinity

[^5]: N-Person Prisoner’s Dilemma https://cs.stanford.edu/people/eroberts/courses/soco/projects/1998-99/game-theory/npd.html

[^6]: The Story of the Crab Bucket http://guidezone.e-guiding.com/jmstory\_crabs.htm

[^7]: Zipf’s Law https://en.wikipedia.org/wiki/Zipf%27s\_law

[^8]: Clay Shirky, The Case Against Micropayments http://www.openp2p.com/pub/a/p2p/2000/12/19/micropayments.html

[^9]: reCAPTCHA, Easy on Humans, Hard on Bots https://www.google.com/recaptcha/intro/index.html

[^10]: Forbes, Tristan Louis, “How Much is a User Worth?” http://www.forbes.com/sites/tristanlouis/2013/08/31/how-much-is-a-us

[^11]: Ripple, Account Reserves https://ripple.com/build/reserves/

[^12]: Reddit Statistics, Number of Users and Comments per Second http://expandedramblings.com/index.php/reddit-stats/2/

[^13]: Martin Fowler, The LMAX Architecture http://martinfowler.com/articles/lmax.html

[^14]: Introducing Intel Optane Technology – Bringing 3D XPoint Memory to Storage and Memory Products https://newsroom.intel.com/press-kits/introducing-intel-optane-technology-bringing-3d-xpoint-memory-to-storage-and-memory-products/

[^15]: United States Money Supply, 2009 https://research.stlouisfed.org/fred2/graph/?s%5B1%5D%5Bid%5D=AMBNS

[^16]: CPI Inflation Index, United States Dollar 2008-2016 http://data.bls.gov/cgi-bin/cpicalc.pl?cost1=1&year1=2008&year2=2016

[^17]: Bitcoin Annual Inflation Rate, Bitcoin Talk Forum https://bitcointalk.org/index.php?topic=130619.0

[^18]: Reddit Valuaton, Newsweek, 2014 http://www.newsweek.com/investors-think-reddit-worth-500-million-26

[^19]: Worth of Web, March 2016 http://www.worthofweb.com/website-value/reddit.com/

[^20]: Micropayments: A Viable Business Model http://www.openp2p.com/pub/a/p2p/2000/12/19/micropayments.html

[^21]: Dailydot, Jon Southurt, April 2015 http://www.dailydot.com/opinion/bitcoin-cryptocurrency-adoption-hard