# Steem

## Blockchain temelli, teşvik sistemine dayalı, kamuya açık bir içerik platformu.

Ağustos 2017

# Çevirmenin Notları

Placeholder for translator's notes.

# Özet

Steem, kripto para birimi ödülleri aracılığıyla topluluk oluşturmayı ve toplumsal etkileşime girmeyi teşvik eden bir blockchain veri tabanıdır. Steem, sosyal medyaya özgü kavramları, kripto para birimlerinin ve kripto para birimi topluluklarının yaratım sürecinde öğrenilen derslerle birleştirmektedir. Bireylerin katılımını tutarlı bir şekilde temsil edecek adil bir muhasebe sisteminin varlığı, herhangi bir topluluğa, para birimine veya serbest piyasa ekonomisine katılımı teşvik etmenin kilit unsurlarından biridir. Steem, çok sayıda birey tarafından Steem topluluğuna sunulan *bireysel katkılar*ın doğru ve şeffaf bir şekilde ödüllendirilmesini hedefleyen ilk kripto para birimi olma özelliğine sahiptir.

# İçindekiler

<!-- toc -->

# Giriş

Kollektif halde, kullanıcı tarafından yaratılmış icerik Reddit, Facebook ve Twitter gibi sosyal medya şirketlerinin hissedarları icin milyarlarca dolarlık bir değer yarattı. **2014 yılında Reddit, reddit.com'a hikaye paylaşımları, yorum ekleme, ya da oylama yoluyla katkida bulunmuş olan herkesin Reddit'ten adil bir hisse ile ödüllendirilmesi durumunda kendi platformlarının çok daha gelişeceği gelişeceği varsayımını öne sürdü.<sup id="fnref:1"><a href="#fn:1" class="footnote-ref"></a></sup>**. Steem sosyal medyayı ve çevrim içi toplulukları, sahip olduğu değerin büyük bir kısmını ona değerli katkılarda bulunan herkesi kripto para birimleri ile ödüllendirmek yoluyla onlara iade ederek, desteklemeyi amaçlamaktadır.

Steem'in tasarımına rehberlik etmek için kullanılmıs olan bazı ana ilkeler vardır. En önemli ilke, bir girişime katkıda bulunmuş olan herkesin girişimden nisbi oranda hisse, ödeme ya da borc aliyor olmasidir. Bu ilke, kurulus aşamasında ve müteakip fonlama rauntları sırasında hisse dağıtan tüm startup'larda uygulanan ilkenin aynısıdır.

İkinci ilke, tüm sermaye çeşitlerinin eşit derecede değerli olmasıdır. Bu şu anlama gelir: Kısıtlı zamanlarını ve dikkatlerini diğerleri için içerik üreterek ve küratörlük yaparak platforma katkı olarak sunanlar, kısıtlı nakitlerini katkı olarak sunanlarla aynı oranda değerlidir. Bu emek-yoğun sermaye ilkesidir[^2] ve önceki birçok kripto para birimi, sinirli sayida insandan fazlasina refah sağlamak konusunda bu kavram ile sıkıntı yasamıştır.

Üçüncü ilke, topluluğun üyelerine hizmet edebilmek için ürünler üretiyor olmasıdır. Bu ilke, kendi topluluklarının dışına mal ya da hizmet satmaktansa sadece kendi üyelerine hizmet eden kredi birlikleri, yemek kooperatifleri, sağlık paylaşım planları üzerinden örneklendirilebilir.

Steem topluluğu üyelerie aşagıda yer alan hizmetleri sunar:

1. Bir kürete edilmiş haber ve yorum kaynağı.
2. Kişiselleştirilmiş sorulara yüksek kalitede yanıtlar alma araçları.
3. Değeri Amerikan Doları'na sabitlenmiş, istikrarlı bir kripto para birimi.
4. Ücretsiz ödemeler.
5. Yukaridaki servisleri kullanıcılara sağlayacak işler.

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

Bir toplulugun sermayeyi cezbedebilmek icin sunabilecegi iki öge vardir: borclanma ve mülkiyet. Mülkiyet satin alanlar topluluk büyüdünde kazanirlar fakat kücüldügünde ise kaybederler. Borc verenlere ise belirli oranda bir faiz garanti edilir fakat toplulugun büyümesiyle gerceklesen kara katilmazlar. Her iki türden sermaye katkisi da toplulugun büyümesi ve onun para biriminin degeri icin kiymetlidir. Ek olarak, mülkiyetin düzenlenebilecegi iki yol vardir: Likit ve Vadeli Mevduat. Vadeli mevduat hissesi uzun vadeli bir taahhüt getirir ve mümkün olan en asagi zaman diliminde satilamaz.

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

### Faiz

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

Eger SBD $1.00'dan daha aza alinip satilirsa ve borc-mülkiyet orani yüksekse, o zaman fiyat yayinlari yukari dogru ayarlanmali ve SBD basina daha fazla STEEM verilmelidir. Bu, borcun mülkiyete oranini düsürürken ve SBD'yi USD denkligine geri cekerken, SBD'ye olan talebi de artirir.

STEEM'in degerinin Steem'in yeni SBD üretiminden daha hizli arttigini varsayarsak; borc-özkaynak orani hedeflenen degerden asagi olmalidir ve sunulan faizden herkes yararlanmalidir. Eger agin degeri sabit seyirdeyse ya da düsüs halindeyse, bu durumda sunulan herhangi bir faiz borc-özkaynak oranini kötülestirmekten baska bir sey yapmaz.

Fiiliyatta USD ile denklik yaratacak sekilde bir para politikasi benimsenmesi fiyat yayini üreticilerine emanet edilmistir. Bu gücün istismari STEEM'in degerini düsürür. SP sahipleri fiyat yayinini ayarlamak ve faiz oranlarini yukarida özetlenmis kurallara göre ayarlamak icin güvenilir Wittness'lari oylayacak bilgeliktedir.

Eger borclanma - Özkaynak orani tehlikeli seviyede yukari cikarsa ve piyasa katilimcilari dönüsüm talepleri yapmaktan kacinirlarsa, bu durumda yayin SBD'ye dönüsüm icin ödenen STEEM oranlarinda artis saglayacak sekilde ayarlanmalidir.

STEEM/SBD dönüsümlerindeki faiz orani politikalarindaki ve/veya harhangi bir kar payi/iskonto'daki degisiklikler kisa vadeli piyasa sartlarina cevap vermek icin degil; yavasca ve uzun vadeli ortalama sapmalara verilen hesapli bir yanit olarak yapilmalidir.

Inancimiz odur ki bu kuralar piyasa katilimcilarina $1.00'dan aldiklari SBD'yi ellerinde tutmalari halinde para kaybetmeyecekleri hususunda güven temin edecektir. Biz normal piyasa kosullari altinda SBD icin $0.95 ve $1.05 arasinda bir alim satim araligi olmasini bekliyoruz.

## Öznel Katkilar

Öznel Proof of Work, mining gibi tümüyle *objektif* Proof of Work sistemlerinden daha iyisini yaparak, para birimi dagitma meselesine alternatif bir yaklasim sunmaktadir. *öznel* proof of work'u hayata geciren para birimlerinin uygulanmasi herhangi bir *objektif* proof of work sisteminden cok daha fazladir cünkü onlar amacini net bir sekilde tanimlamis herhangi bir kavram etrafinda topluluk yaratmak icin uygulanabilirdir. Bireyler bir topluluga katildiklarinda belirli fikirlere ragbet ederler ve topluluk degerlerini veya amaclarini güclendirmek icin oylama yapabilirler.

Fiiliyatta, work'un degerlendirildigi kriterler tümüyle özneldir ve ve onun tanimi kaynak kodunun disinda bulunur. Bir topluluk sanatcilari ödüllendirmeyi ister, bir digeri sairleri ve ötekisi ise komedyenleri. Diger topluluklar hayirseverligi ödüllendirir ya da politik hedeflere yardim eder.

Her bir para biriminin edindigi deger, spesifik bir topluluk icerisindeki etkiye duyulan talebe ve her toplulugun ne kadar piyasa güveni kazabilecegine baglidir. Önceki sistemlerden farkli olarak, öznel proof of work bir topluluga her neyi degerli buluyorlarsa onu fonlayabilme imkani tanir ve daha öncesinde parasallasitirilmasi mümkün olmayan zamanin parasallastirilmasina izin verir.

### Para Biriminin Dagitimi

Insanlarin kripto para birimi topluluguna dahil olabilecegi iki yol vardir: *satin alabilirler* ya da *üretiminde calisabilirler*. Her iki durumda da, kullanicilar para biriminin degerine katkida bulunurlar, ne var ki, insanlarin büyük cogunlugunun *harcayacak nakitten* cok *harcayacak vakti* vardir. Hic gercek *nakdi* olmayan fakat bolca *zamani* bir toplulukta bir para birimini yükseltmeye calistiginizi hayal edin. Eger insanar birbirleri icin calisarak para kazabilirlerse o zaman degeri, adil bir para birimi/ maliye sistemini kullanarak, karsilikli takas yoluyla yükseltirler.

Bir para birimini cogunlukla adilane oldugu düsünülecek sekilde, alabildigine fazla sayida insana dagitmak zorlu bir istir. Tümüyle objektif bilgisayar algoritmalari tarafindan degerlendirilecek görevler dogalari itibariyle sinirlidir ve genel anlamda sinirli dissal yararlari vardir. Bitcoin-tarzi miningde, bu özellestirilmis donanimlarin üretilmesine sebep olabilir ve insanlarin daha gelismis algoritmalar üretmek icin vakit harcamasina sebebiyet verebilir. Hatta bu asal sayilari bulmaya bile yardimci olabilir fakat bunlarin hicbirisi büyük planda topluma ya da para birimi bulunduran topluluga anlamli degerler katmaz. Daha da önemlisi, ölcek ekonomileri ve piyasa kosullari experler haricinde herkesin bu tarz bir paylasimdan dislanmasi sonucunu bile getirebilir. Nihayetinde bilgi-islem temelli mining *satin almanin* sadece baska bir yoludur. Cünkü o, elektrik faturasi icin ya da isi yapabilecek yetkinlikte donanimin gelistirilebilmesi icin para ödenmesini gerektirir.

Herkese dahil olabilme esitligi ve para birimi kazanabilme esitligi taniyabilmek adina insanlara calisma esitligi saglanmalidir. Zor olan, bireylerin ürettigi isin göreli niceliginin ve niteliginin nasil degerlendirilecegi ve bunun öyle bir yolla yapilmasidir ki milyonlarca üyeye ödülleri efektif bir sekilde dagitilsin. Bu da ölceklenebilir oylama sürecinin piyasaya sunulmasini gerektirir. Bilhassa bu, fonlari dagitacak olan otoritenin olabildigi kadar dagitik yapili ve merkezsiz olmasini gerektirir.

Milyonlarca insani ödüllendirmenin ilk adimi ne kadar isin yapildigindan ya da kullanicilarin nasil oyladigindan bagimsiz olarak belirli sayida para birimini insanlara dagitmaya kalkismaktir. Bu ise soruyu, *"Para ödememiz gerekiyor mu?"* dan *"kime ödememiz gerekiyor?"*a cevirir; ve piyasaya paranin dagitim asamasinda oldugunun ve kim daha fazla *is* teklif ediyorsa ona müzayede edildiginin sinyalini verir. Bitcoin'in kim en zor hashleri bulursa ona 50 BTC vaat ediyor olmasi buna benzerdir. Tipki Bitcoin gibi, tüm is ödeme öncesinde yapilmis olmalidir ve hicbir sey spekülatif bir sekilde gelecekte yapilacagi sözü verilen bir is üzerinden ödenmemelidir.

Bir sonraki adim *herhangi bir sey*den cok az bir miktar bile olsa daha olumlu bir edimde bulunan herkesin ödüllendirilmesidir. Bu yapilmis tüm isleri siralamak ve degerlerine oranla ödül dagitarak basarilmistir. Piyasa ne kadar rekabetci hale gelirse (düsük kalite ya da yüksek kalite) ödeme kazanmak bir o kadar zor hale gelir.

### Para Biriminin Dagilimi Üzerine Oylama

Dağıtılacak belli miktarda bir paranın olduğunu ve paranın gelecekteki değeri ve yararı konusunda uzun vadeli menfaatlere sahip olanların, onun nasıl tahsis edileceğine karar vermesi gerektiğini varsayalım. Her temlik sahibi kullanıcı, en iyi çalışmayı kimin yaptığına oy verir ve günün sonunda o gün elde edilen paralar oylarla orantılı olarak paylasilir ve böylelikle birer tane bile olsa arti oy kazanmis olan herkes bir şeyler alır.

Saf oylama süreci, büyük topluluk hedeflerinden vazgecmek pahasina, her üyeye kendisine oy vermeyi teşvik eden N-Person Prisoner’s Dilemma'yı[^5] oluşturur. Eğer oy hakki olan herkes kendisi icin oy kullanirsa bu durumda para birimi dagitilmis olmayacak ve bir bütün olarak ag etkisi yaratmak konusunda basarisiz olacaktir. Diger yandan, eğer oylayanlardan sadece bir tanesi kusurlu davranirsa, o kisi para biriminin genel değeri üzerinde minimum miktarda etkiye sahip olurken kendisine haksız kazanç da saglamis olur.

#### Oy Suistimali

Bir bireyin ne kadar parası olduğundan bagimsiz olarak, benzer refah seviyesinde bircok baska birey vardir. Hatta en zengin bireyler bile, nadiren, onlari takip eden zenginlerin birlesiminden çok daha fazlasına sahiptir. Ek olarak, toplulukta fazla yatirimi olanlar, oylama sisteminde kendi cikarlarina yönelik oynamaya calismalari durumunda en fazla kayebedecek olanlardir. Bu, bir sirketin CEO'sunun tüm kari cebe atabilmek adina maaslari ödemeyi kesmeye karar vermesi gibidir. Bu durumda, şirkette çalışan herkes ayrılip başka bir şirketler için çalışırdı ve sirket degersiz hale gelirken CEO'sunu da zengin degil iflas etmis halde birakirdi.

Neyse ki, büyük yogunlukta oy alan herhangi bir calisma aynı zamanda en çok denetimi de kazaniyor (aleniyet). *Aleyhte oylama*nin da eklenmesiyle, bircok kücük hisse sahibi icin gizli ittifak halinde bulunan gruplarin ya da kusurlu davranan büyük hisse sahiplerinin oylama gücünü etkisiz kilmak mümkün hale gelmistir. Buna ilaveten, büyük hissedarlar istismara bagli olarak para biriminin degerinin düsmesi durumunda kendilerine oy atarak kazanacaklarindan cok daha fazlasini kaybederler. Esasinda, dürüst büyük hissedarlarin kücük katkilarda bulunmak icin oylama yapmalarindansa; istismari denetlemeleri ve alehyte oy kullanmalari muhtemelen daha efektiftir.

Insanlari sistemi istirmar etmekten alikoymak icin kullanilan *Aleyhte oylama*, bir bireyin diger herkesin cikari pahasina kar ettigi fark edildigi zaman bir cok insanin gelistirdigi *yengec zihniyeti*ni kaldirac olarak kullanir. Yengec zihniyeti normalde iyi insanlari asagi cekmeye calisan dar görüslü insanlari tanimlamak icin kullaniliyor olsa da bu ayni zamanda iyi insanlarin kötüleri zaptetmesine de izin veren seydir. Yengec zihniyetiyle ilgili tek sorun, insanlarin, birinin diger herkesin cikari pahasina kar ediyor olduguna *yanlis bir sekilde inanmalari* durumundadir.

**Yengeç Kovasının Hikayesi**[^6]

Bir adam sahil boyunca yürüyordu ve yaninda duran bir yem kovasiyla birlikte kiyiya vuran dalgalarda balik tutmakta olan bir adam gördü. Yakinlastikca yem kovasinin kapaginin olmadigini ve kovanin icinde canli yengeclerin oldugunu gördü.

"Neden yem kovasinin üzerini örtmüyorsun bu sayede yengecler kacamaz?", dedi.

"Anlamiyorsun,", diye yanitladi adam, "Eger kovanin icinde tek bir yengec olursa, o kesinlikle hizlica disari kacar. Ne var ki, kovanin icinde fazla sayida yengec varsa, birisi disari kacmak icin tirmanmaya yeltendiginde bir digeri hemen onu kavrayip geri ceker ki bu sayede o da diger hepsiyle ayni kaderi paylassin."

Bu insanlarda da böyledir. Eger birisi farkli bir sey yapmaya calisirsa, daha iyi notlar alirsa, kendisni gelistirirse, vasatliktan kacarsa ya da büyük düsler kurarsa diger insanlar kendileriyle ayni kaderi paylassin diye hemen onu asagi cekeceklerdir.

"Istismarin" önüne gecmek mümkün degildir ve asla ana hedef olmamalidir. Sistemi "istismar" etmeye calisanlar bile hala bir is yapiyorlardir. Basarili istismar ya da hile girisimleri icin alacaklari herhangi bir mükafat bile, geleneksel bitcoin miningi ya da mining poollar tarafindan yapilan ittifakli miningde benimsenen angarya olarak para dagitmanin amacina uygundur. Gerekli olan tek sey ise, istismarin topluluk ve onun para birimi namina gercek isler yapmaya yönelik tesvigi bastiracak kadar yayginlasmamasini temin etmektir.

Topluluga ait bir para birimi üretmenin hedefi "kovaya daha fazla yengec" getirmektir. Tüm istismarin önüne gecmeye calismak icin asiri önlemler almaya varmak tipki yengeclerin kacmasini engellemek icin kovanin üstüne bir kapak koymak gibidir. Ve bu da kovaya yeni yengecler koymayi zorlastirmak pahasina olur. Kovanin kenarlarini kayganlastirmak ve diger yengeclere yeteri kadar güc vermek digerlerinin kacmasini engellemeye yeter.

### Sayi Sinirli Oylama

Suistimali asgariye indirmenin büyük bir kismi sayi-sinirli oylamadir. Bireysel kullanıcılar günde sadece belirli bir miktar çalışmayı okuyabilir ve degerlendirebilirler. Bu miktardan daha fazla oylama yapmak otomasyonun ve potansiyel suistimalin bir işaretidir. Sayı sinirlamasi ile, çok fazla oylama yapan hissedarların oyları onlara nazaran daha az oylama yapan hissedarlarinkine göre daha değersiz sayilir. Tokenlari cok sayida hesaba bölüstürmeye calismak ayni zamanda etkiyi de böler ve bu sebeple bu ne oylamaya konmus sayi sinirini atlatmaya yarar ne de etki gücünde net bir artisla sonuclanir.

Kullanıcılara sabit bir oylama gücü tahsis edilmektedir. Bir is parcasina ödül havuzundan ne kadar pay dagitilacagini belirlemek icin oylama gücü kullanicinin taahhüt altindaki tokenlariyla carpilir. Kullanılan her oy, oy gücü bakiyesinden belirli bir yüzde kullanir. Kullanıcılar fazla sayida paylasima icin oy kullanabilirler, fakat her oy bir öncekinden daha değersiz olacak ve tam oylama gücüne tekrar erismek icin daha fazla zaman gerektirecektir. Oylama gücü sabit bir şekilde günde 20% olarak geri dolmaktadır.

### Ödeme Dağılımı

Steem'in ödüllendirme sisteminin baslica amaclarindan birisi internet üzerindeki en iyi tartismalari üretmektir. Her yil, yillik enflasyonun %75'i icerik gönderen, icerikleri oylayan ve onlari tartisan üyelere dagitilir. Bitcoin'in büyüklügünde, bu baslica katki yapanlara günde birkac milyon dolar olarak verilebilir.

Nihai dagilim kullanicilarin oylama örüntülerine baglidir fakat, zannediyoruz ki ödüllerin büyük cogunlugu en popüler icerikler arasinda dagitilacaktir.

Zipf Kanunu[^7] gercek hayat görüngülerinin sasirtici menzilini cok güzel bir sekilde aciklayan ampirik kurallardan birisidir. Buna göre, bir toplami büyüklük ya da populerlige göre siralarsak, siralamadaki ikinci eleman birincinin yarisi büyüklükte olacaktir, ücüncü ise birincinin ücte biri oraninda vb. Genel olarak k'inci siradaki parca birincinin 1/k oraninda bir büyüklükte olacaktir.

![](\img_the_new_marketplace.png)

Populerligi degerin kabataslak bir ölcüsü olarak alirsak, bu durumda her bir tekil bilesenin degeri Zipf Kanununca bellidir. Ki bu da, bir milyon bilesenimiz varsa en populer 100 toplam degerin ücte birini sunmaktadir. Sonraki 10,000 diger ücte biri, ve kalan 989,900 de kalan ücte biri... N sayida bilesen toplaminin degeri log(n) ile orantilidir.

Bu oylama ve ödeme dagiliminin etkisi iyi iceriklere büyük cömertlik sunarken kücük oyunculari da dolayli katkilari icin hala ödüllendirmektedir.

Bunun ekonomik etkisi piyangoya benzer. Insanlar oylanma sanslarini oldugundan fazla gördüklerinden kazanmalari beklenen ödülden daha fazla is yaparlar ve bu sayede topluluga hizmetin icin yapilmis islerin sayisini azamiye cikartirlar. "Herkesin bir seyler kazaniyor olmasi" kumarhanelerin insanlari kumarda tutmak icin kullandigi ayni psikolojik etkidir. Bir baska ifadeyle, kücük ödüller daha büyüklerini de kazanmanin mümkün oldugu fikrini saglamlastirir.

### Ödemeler

Bir gönderi ödeme aldiginda bu 50% SBD ve 50% SP bicimindedir. Steem Power kullaniciya artirilmis oylama ve islem gücü verirken, SBD ise kullaniciya istikrarli bir para birimi üzerinden dogrudan bir kazanc sunar. Daha önce uzun bir sekilde acikladigimiz üzere, SP kisa vadeli satislar yerine uzun vadeli elde tutmalari tesvik etmek icin tasarlanmistir. Bu daha fazla kullaniciyi platformun uzun vadeli basarisinda menfaat sahibi olmak konusunda cesaretlendirir.

Kullanicilar ödemelerini 100% SP seklinde alma secenegi ile birlikte gönderilerine yapilacak ödemeleri reddedetme hakkina da sahiptir. Kullanici bir gönderi icin ödeme almayi reddettiginde, kendisine ödenecek olan para diger kullanicilar arasinda dagitilmak üzere ödül havuzunda kalir.

# Oydasma Algoritmasi

Oydasma, sayesinde bir toplulugun bir bilgi parcasi üzerinde belirsizlige mahal birakmayan ve evrensel bir sekilde taninan bir anlasmaya vardigi bir sürectir. Toplumun kimin neye sahip olacagi hakkinda bir oydasmaya varabilmek icin gelistirmis oldugu bircok algoritma vardir. Dünya üzerindeki her hükümet, kendisi vasitasiyla nüfusun anayasa tarafindan teminat altina alinan bir takim kurallar bütününe uymayi kabul ettigi ilkel bir oydasma algoritmasidir. Hükümetler, öznel olgulari yorumlamak ve haklarinda nihai bir karar verebilmek icin mahkemeler, hakimler ve jüriler tesis eder. Cogunlukla insanlar verilen karar yanlis olsa bile karara uyar.

Kripto para birimleri tarafindan kullanilan algoritmalar oydasmaya ulasabilmek icin cok daha iyi bir yol sunar. Tüm kullanicilar tarafindan kriptografik olarak imzalalanmis tanikliklar, mutlak küresel olaylar siralamasini kuran kamuya acik bir kayit defterine kaydedilir. Bunun üzerine, belirleyici bir bilgisayar algoritmasi evrensel olarak kabul edilecek bir sonuca varmak icin bu kayit defterini isler. Toplulugun üyeleri bu isleme algoritmasi üzerinde mütabik kaldigi müddetce algoritmanin buldugu sonuc itaate yönelticidir.

Ana düsünce, hangi tanikliklarin kamusal kayda gecirilmesine izin verileceginin belirlenmesidir. Sistemler muhtemel sansürleri en aza indirgeyecek sekilde tasarlanmalidir. Kamusal kayit defterinde uygulanan herhangi bir sansür, tipki birisinin secimlerde oy kullanmasinin önüne gecmek gibidir. Her iki durumda da bireyin küresel oydasmaya etki etmesinin önü kesilmistir.

## Steem'de Oydasma

Kavramsal olarak, Steem tarafindan benimsenmis olan oydasma algoritmasi dünyanin bircok yerindeki sirketler tarafindan kullanilan oydasma algoritmasina benzerdir. Steem'in gelecekteki degerinde taahhüt edilmis haklari bulunanlar, oylama yaparak, kamusal kayitlara tanikliklari kabul etmekle görevli kisileri secerler. Oylama her bir bireyin taahhütlü haklariyla orantili olarak agirliklandirilmistir.

Kripto para birimleri dünyasinda kamusal kayit cogunlukla *blockchain* olarak adlandirilir. Bir *block* imzalanmis bir islemler grubudur.

Steem'de blok üretimleri rauntlar halinde yapılır. Her rauntda 21 adet witness, islem bloklarini yaratmak ve imzalamak için seçilir. Bu witnesslarin yirmi (20) tanesi onay oyu ile secilir ve bir tanesi ise oylamada ilk 20'ye giremeyenler tarafindan, aldiklari oylarla orantili olarak, devremülk olarak paylasilir. Aktif haldeki 21 Witness, herhangi bir Witness'in kendisi tarafindan üretilmis ve yerlestirilmis herhangi bir blogu süreki olarak görmezden gelmesinin önüne gecmek icin her rauntta yeniden karilir. Herhangi bir blogu iskalayan ve son 24 saat icerisinde de üretimde bulunmamis olan herhangi bir Witness, Blok Imzalama Anahtari'ni güncelleyene dek engellenir.

Bu süreç -üst siralara cikacak kadar oylanabilmeye yetecek populerlige sahip olunmasindan bagimsiz olarak- herkese blok üretimine katilabilme potansiyeli temin ederken; en iyi güvenilirliği sağlamak üzere tasarlanmıştır. İnsanlar, seçilmiş ilk 20 Witness tarafindan uygulanan sansürü asmak için 3 ayrı yola sahiptir: Ilk 20'de bulunmayan herkesle birlikte sabirla beklemek ya da oy gücünü arttırmak için daha fazla SP satın almak. Genel olarak konuşursak, sansür uygulamak seçilmiş witnesslar acisindan işlerini kaybetmek icin iyi bir yoldur. Bu nedenle Steem ağında bunun gercek bir probleme dönüsmesi olması olası değildir.

Aktif witnesslar önceden bilindiği için, Steem Witnessları her 3 saniyede bir blok üretmeleri için zaman cizelgesine oturtabilmektedir. Witness'lar blok üretimlerini NTP protokolü araciligiyla senkronize eder. Bu algoritmanın bir benzeri bir yılı aşkın süredir BitShares ağında kullanılarak güvenilirliğini kanıtlamıştır.

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

Bir blokzinciri kullanıcıların sahip olması gereken minimum değeri, minimum bakiye gereksinimi ile zorlayabilir. Blokzincirine yeni bir kullanıcı kazandırmak isteyen herhangi bir şirket o kullanıcının hesabını daha önceden minimum bakiye ile doldurarak sistemi kullanmasını sağlar. Yeni kullanıcı kayıtları için nispeten yüksek bir harç bedeli (1 dolar) talep etmek, ücretsiz hesap hizmeti sunan birini, hesapları blockchain'e kaydetmeden önce, her bir hesabın niteliğini ve özgünlüğünü titiz bir şekilde denetlemeye zorlayacaktır ister istemez.

İşin aslı, minimum bakiye tutmak, kullanıcıların işlem harçlarını kazanmış oldukları ve kendi bakiyelerine kaydettikleri faizlerle ödemelerini sağlamaya denk düşer. Kısaca minimum bakiye, bir harcı oldukça kısa bir süre zarfında ödemeye yetecek kadar faizi kazanmak için gerekli olan bakiye şeklinde tanımlanabilir.

Bereket versin ki şart koşulan minimum bakiye 1 dolar kadar düşük bir meblağ olabilir; bu da kullanıcıların kabul edebileceği ve hoşnut olabileceği bir tutardır. Kaybedilen faizin fırsat maliyeti, bir mikro harcın bilişsel maliyetini karşılamaz. Bu ise kullanıcılar için çok daha makul olan bir durumdur.

Bir hesabı önceden fonlamak için kullanılan STEEM yeni hesapta aktive edilir, bir başka deyişle, Steem Power'a dönüştürülür. A portion of the SP used to fund a new account may be delegated from the creator of the account. Bir kullanıcı SP delege ettiğinde delege edilen kişi SP'yi oy verme ve trafik için kendilerininmiş gibi kullanabilir fakat SP'nin sahipliği delege eden kişide kalacaktır. Kullanıcı istediği herhangi bir zamanda delegasyonunu geri çekebilir. Delege ettikleri SP miktarı bir süre beklemenin ardından hesaplarına iade edilir.

### Harçların etkililiği

Hız limitlemeyi harçlarla kıyaslamak için, bu iki sistemin bir saldırıcı tarafından ağa yönelik olarak düzenlenen sel yönlendirmesine nasıl tepki verdiklerini göz önünde bulundurmamız gerekir. Bitcoin'de, 10 bin dolara sahip bir saldırgan, her bir bloku dosyalayarak hizmeti bütün bir gün boyunca akamete uğratabilir. Aynı saldırgan, "dinamik kısmi karşılık hız limitleme yaklaşımı" kapsamında, tek bir blok için bile hizmeti akamete uğratmayı başaramayacaktır.

Daha uç bir durum düşünüp de bir saldırganın tüm coinlerin %1'ini elinde bulundurduğunu varsayacak olursak, öylesi bir durumda saldırganın 60 milyon dolara sahip olacağını kabul etmemiz gerekir. Böyle bir saldırgan, madenciler harçları veya kapasiteyi artırmadıkça Bitcoin blockchain hizmetini 16 yıl boyunca devre dışı bırakabilir. Harçlar işlem başı 15 dolara yükseltilse dahi, sözkonusu saldırgan yine de ağı 16 gün boyunca sel yönlendirmesine (flooding) maruz bırakabilir.

Hız limitleme yaklaşımı kapsamında, tüm coinlerin %1'ini elinde tutan ve ağı sel yönlendirmesine maruz bırakmaya niyetlenen bir kişi, bu hedefine 30 saniyeden kısa bir sürede ulaşabilir.

### Kiralama - Satın Alma - Devre mülk

Bir evi kendi mülkiyetine alan bir kişi, bu evi ücretsiz kullanma hakkına sahip olmayı umar. Bir grup kişi birlikte bir ev satın alırsa, o zaman bu kişilerden her biri evdeki sahiplik yüzdesi ölçüsünde bu evi kullanma hakkına sahip olmayı umar. Harç temelli blockchain, bu evi sahiplerinden kiralamak gibidir; buna karşın hız limitleme, sahiplerin kendi aralarındaki devre mülk gibidir.

Eğer bir evin mülkiyeti birden çok kişiye ait olursa, o zaman bu kişiler evi nasıl devre mülk yapmak istediklerini kararlaştırmalıdır. Evin %50'sine sahip olan, bununla birlikte evi yılda yalnızca bir hafta kullanan bir kişi, kendi kullanmadığı zamanlarda evi kullanan kişilerin kendisine ödeme yapmasını bekleyebilir. Harç temelli sistemin işleyiş mantığı budur.

Diğer yandan, bir kişi evin %50'sine sahip olup eve yönelik talebin gelecekte artacağı ve kendi hissesini daha fazla bir meblağ karşılığı satabileceği yönünde spekülasyon yapıyor diyelim. Bir evin kullandığından daha fazlasına sahip olan herhangi bir mülk sahibi, emlak spekülasyoncusuna dönüşebilir. Bu kişi, kira tahsil etmek yerine bu mantığı işe koşarak değer tahsil eder.

Bir hissenin değeri, sahibine potansiyel olarak ne kadar süre bahşettiğine bağımlı olarak oluşur. Bir evin %1'ine sahip olup bu evi yılda bir hafta kullanmak, en düşük değerli hissedir. Yine de, hisse sahiplerinin yarısı evi bir haftalığına kullanma haklarını hiç kullanmazlarsa şayet, o zaman devremülk başı değer yılda iki haftaya yükselir. Eğer o faal olmayan kullanıcılar daha ziyade kullanmadıkları zamanı kiralamaya yönelirlerse, o zaman değer tekrar yılda bir haftaya düşer. Eğer o kullanılmamış devremülkler onları kullanabilecek olan insanlara satılsalardı, o zaman da bir devremülkün değeri %50 azalırdı. Tahsil edilen kira bedeli hisse değerindeki azalmadan daha büyük değilse, devremülk sahipleri ekonomik bir yanlış hesap yapıyorlar demektir.

Bu mantığı temel alarak diyebiliriz ki harç temelli bir sistem ya kullanıcıları için daha pahalı; ya da kolektif sahipleri için daha az kârlı bir sistem olacaktır. Küçük çaplı bir mülk sahibi kendi kısa zaman dilimini kiralayarak kâr edebilir; ne var ki bunu yalnızca diğer devremülk sahiplerinin zararına olacak şekilde yapabilir. Aslında, azalan devremülk değerinin maliyeti tüm mülk sahipleri arasında paylaşılır; buna karşılık kârlar, kendi payını kiralamayı kararlaştıran tek bir mülk sahibinin elinde toplanır.

Buradan şu sonuca varabiliriz ki en iyi blockchain hizmeti, kullanıcılara herhangi bir kullanım harcı ödetmeden verilir. Eğer bir kullanım harcı hız limitlemeye alternatif olarak ödenmek zorunda olsaydı, o zaman kullanım harcının yeteri kadar devre mülk satın almanın ve bunları kullanım hakkı elde etmeye yetecek kadar uzun süre elinde tutma taahhüdünde bulunmanın muadili olması gerekir.

Bir başka deyişle, bir işlem harcının, haftada bir kez işlem yapmak için gerekli olan minimum hesap bakiyesine eşit olması ve haftanın bitiminde geri ödenmesi gerekir. Minimum hesap bakiyesinin 1 dolar olduğunu ve bunun bir kişiye haftada bir kez işlem yapma izni tanıdığını varsayın. Eğer 1 dolar bakiyesi olan bir kişi bir kerede 5 adet işlem yapmak isterse, o kişi işlemlerden önce ya da sonra bakiyesini haftalık 5 dolara çıkarmak zorunda kalacaktır.

Kuramsal olarak, kullanıcıların yatıracak parayı başkalarından borç alabildiği yerde pazar kurulacaktır. Pratikte, kendi kullanıcı oranlarını karşılamaya yetecek kadar devremülkü satın alıp satmak, kullanıcılar için daha verimlidir. Başka bir deyişle, mikro düzeyde kredi müzakeresi yapmanın bedeli, haftalık maksimum kullanımınıza denk düşen bakiyeyi sağlamanın bedelinden daha yüksektir.

Yeni tür desantralize uygulamalar -kullanımı için küçük çaplı bir ödeme yapmak gerektiğinde etkili çalışmayan uygulamalar-, işlemler için desantralize hız limitlemesi sayesinde etkili bir şekilde çalışır hale gelebilirler. Bu yeni model uygulama geliştiricilerine, kullanıcıları yaptıkları işlemlerden ötürü ücretlendirip ücretlendirmemeyi, ücretlendirecekse de ne zaman ücretlendireceğini kararlaştırma olanağı tanır.

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

## İlk Paylasim & Arz

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

# Steem'in Gücü

Steem recognizes that the value of all user contributions (posts and votes) is greater than the sum of the parts. A single comment is worth next to nothing, but millions of curated posts is worth many millions (or possibly even billions) of dollars. A single vote provides little curation value, but billions of votes is very effective curation. Content without curation is of limited value. Given all the content of the Internet minus the links between it, Google would struggle to produce useful search results. It is the links between information that give it significant value.

Herkes yararlandığı için, herkes ödemeli. In other words, no individual user should be expected to pay for anything, but instead should be paid for everything they do that brings value to Steem. All we need to do is ascertain which user contributions bring a social network value and which ones don’t.

Collectively Reddit users vote 220 times per second and make 23 posts per second. Reddit is valued between $500 million[^18] and $4 billion[^19] which means that each and every upvote and post is worth between $0.06 and $0.50 assuming the value of Reddit is mostly within the past year’s worth of activity. One could argue that most of the value of Reddit is the near-real-time discussions that have occurred within the past week which would dramatically increase the value of new activity. People go where people are today, not where people were last year.

## No Micropayments, Tips Optional

Existing attempts at integrating a cryptocurrency into a social media platform have focused on enabling users to pay one another. Bir çok hizmet bahşiş vermeyi tanıtmaya çalıştı. The theory is that if we make tipping simple enough then more people will do it. Other services attempt to get people to pay to promote or boost their content’s ranking. Still others attempt to build small prediction markets on how many tips an article will receive.

Bu yaklaşımların hepsi mikroödemelere bağlanıyor. Değişen tek şey ise ödemeyi kimin yaptığı. They all suffer from insufficient engagement of people making the micropayments. In the search for incentivised content production entrepreneurs have been so focused on who should pay that they missed the obvious reality: everyone benefits from everyone’s actions so everyone should pay or no one should pay, depending on how you look at it.

Steem bypasses micropayments completely because when a user upvotes a post it is the community that pays the bill. The same amount of money will be spent whether the user upvotes a post or not and the funds will not come from the voter.

The mental energy associated with making an economic decision becomes a barrier to participation for most people.

*We already face a multitude of choices everyday with regards to what to access online in this digital era of the information explosion, and every additional decision that we must make simply adds on to the uncertainty and anxiety we face. Micropayment supporters believe that a simplified implementation can minimize the intrusiveness of micropayments and improve user experience, but their argument only creates double standards for the decision making process \[2\]. A transaction cannot simultaneously be worth enough to warrant a decision and worth so little that the decision is automatic. **The only transactions that users can approve without thought are ones that cost them nothing**, thus any micro-transaction of positive value will incur mental costs through its requiring a decision. Furthermore, mental transaction costs actually rise below a certain threshold value, a phenomenon that places micropayments at an even greater disadvantage. For instance, it is easy to think that a copy of today's newspapers costs $1, but readers face much more difficulty and anxiety in deciding on the value of each article or word. Such a dilemma will only be replicated and exacerbated if all online content were to be broken down into their components and individually valued within a micropayment system.*

-Mikro ödemeler: Sürdürülebilir bir Ticaret Modeli[^20]

Steem'de mikro ödemeler içerik üreticisine yapılır; buna karşılık içerik için oy verenler ödeme yapmazlar. Bunun yerine, ödülün bedeli yeni tokenlar aracılığıyla ödenir. Someone can join the system, vote to pay someone, and then exit the system with more money than they started with (assuming the market valuation of the Steem system remained constant). In other words, the micropayment solution provided by Steem provides a user-experience similar to many widely used websites that have user-moderated content.

Üstelik Steeem, kime ödeme yapmak gerektiğini saptamaları için insanlara ödeme yapar! Bu devrimci bir akı yürütmedir.

## Değer bağlantılarda

Eğer içerik bünyesindeki tüm bağlantılar kaldırılsaydı, İnternet değerinin çok büyük bir bölümünü yitirirdi. Google'a 16 milyon sonuç arasından en iyi elma turtası tarifini saptama imkanını veren şey web sayfaları arasındaki ilişkidir. Bağlantılar olmasaydı Google yalnızca sözcüklerin hangi sıklıkla kullanıldığının bilgisine sahip olabilirdi.

Bağlantılar birçok biçim alabilir; zaman içinde birçok farklı biçime de girmişlerdir zaten. Herhangi bir sosyal ağda herhangi bir içeriği oylayan kullanıcı, kendisiyle içerik arasında bir bağlantı oluşturur. Bu da içerik aracılığıyla müşteriyi üreticiye bağlar. Bir ağ ne kadar fazla bağlantıya sahipse sunduğu bilgi de o kadar değerlidir. Bir bilgiye değerini bahşeden, o bilginin göreli ve kasıtlı bağlantılılığıdır.

Bir sosyal ağ, bağlantıların niceliğini ve niteliğini maksimize ederek, bir içerik setinden süzülen değeri maksimize edebilir. İçerik düzenlemek pahalı ve zaman alıcıdır; bunun yanında, bağlantılar olmaksızın bilgisayarların iş görmesi neredeyse imkansızdır. Steem, yeni içerikleri bulup tespit eden ilk kullanıcıları ödüllendirir.

Steem ağı, içerik düzenlemeyi teşvik ederek, devasa bir içerik bütününden en değerli bilgiyi süzmek için otomatik algoritmalar kullanabilmektedir.

## Solving the Cryptocurrency Onboarding Problem

Kripto parayı kullanmayı öğrenmek kolay değildir [^21]. Bitcoin'den yeni haberdar olan ve onu bir denemek isteyen bir kişi çok geçmeden para bozdurarak kayıt olması ve hesabını bir kredi kartı veya banka havalesiyle fonlaması gerektiğini öğrenir. Eğer üyelik için para ödemek ve iki çeşit kimlik belgesi arz etmek zorunda kalsaydınız Facebook kullanım oranı ne seviyede olurdu?

Steem, herkese yaptığı basit ama değerli görevlerin parasal karşılığını alabilmenin imkanını sunarak bu sorunu çözmektedir. Bu STEEM tokenlarını kapsamlı bir şekilde dağıtmayı sağlayacaktır. Bu yararlı bir şeydir zira kripto paralar ağ etkisi yaparlar (yani, kullanıcı sayısı arttıkça kripto para daha kullanışlı hale gelir; aykırı bir örnek vermek gerekirse, Satoshi Bitcoin'in %100'ünü kendisine saklamak istediğini düşünün, bu durumda Bitcoin'in hiçbir değeri kalmazdı)

## Solving the Cryptocurrency Liquidation Problem

A currency that is difficult to use or impossible to sell has little value. Someone who comes across $1.00 worth of Bitcoin will discover that it costs more than $1.00 to sell that Bitcoin. Bir borsada hesap açmaları, KYC (Know Your Customer) onayını gerçekleştirmeleri ve ücret ödemeleri gerekir. Small amounts of cryptocurrency are like small change that people are unwilling to bend over to pick up.

Merchants give users a way to quickly convert their cryptocurrency into tangible goods and services. Merchants need a currency pegged to their unit of account, normally dollars. Accepting a volatile currency introduces significant accounting overhead.

Merchants will accept any currency if it increases their sales. Having a large user base with a stable currency such as SBD lowers the barrier to entry for merchants. The presence of merchants improves the system by creating an off-ramp for users to exit the system without going to the trouble of using an exchange.

Another way that people can liquidate the small amounts of cryptocurrency they receive from participating on the Steem platform is through *tipping* others. This is like leaving the small change as a tip for your waiter. When enough people leave small tips it adds up to a meaningful amount. You and the waiter each gain a benefit from the tip.

## Sansür

Steem, tüm dünyadaki yargı sistemlerindeki witnessler tarafından işletilen desantralize bir ağdır. Tüm kullanıcı faaliyetleri kamuya açık bir şekilde blockchain'e kaydedilir ve kamuya tarafından denetlenebilir. Bu da STEEM paydaşlarınca kendisine değer atfedilmiş olan içeriği sansürleyebilecek hiçbir entitenin olmadığı anlamına gelir.

Steemit.com gibi bireysel web siteleri kendi sitelerinde içerik sansürlemesi yapabilirler; buna karşın blockchain'de yayınlanan içerik doğası gereği trafik neşreder ve tüm dünyadaki aynalar da bu içeriği erişilebilir kılmayı sürdürebilirler.

İfade özgürlüğü diğer tüm özgürlüklerin temelidir; ifade özgürlüğüne yönelik herhangi bir ihlal, oydaşmayı tesis etmenin yegane barışçıl yolunun, yani tartışmanın temelini sarsar. Özgür tartışma olmaksızın, oy verenler tamamen bilgilendirilemez; bilgilendirilmemiş oy verenler de toplum için oy kullanma hakkını kaybedenlerden daha büyük bir tehdit oluştururlar. Sansür, kamusal söylemi kısıtlanması aracılığıyla oy çalmanın bir biçimidir. Steem, ifade özgürlüğünü tesis etme ve özgür bir toplum inşa etme amaçlarına kendini adamıştır.

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

Steem, kriptopara ve sosyal medya endüstrilerindeki güçlükleri her iki endüstrinin en iyi yönlerini bir araya getirerek irdelemek amacıyla tasarlanmış bir deneyimdir. Steem, içerik yaratıcılarına ve internet okuyucularına sosyal medya endüstrisi içinde daha önce hiç kullanılmamış yöntemlerle para kazanma fırsatları sunar. Steem dahilinde bireyler, kendi katkılarıyla doğrudan ilintili çevrimiçi gerçek ödüller kazanırlar. Bu ödüller, Steem'in pazar fiyatı keşfi ve likiditesi nedeniyle dolar değerine sahip olabilir; ellerinde Steem bulunduran insanlar ise bunu yapmayan insanlardan daha fazla kazanım gücüne sahip olabilirler.

[^1]: Reddit'in kriptoparası, Forbes, Erika Morphy, Ekim 2014 http://www.forbes.com/sites/erikamorphy/2014/10/01/reddits-cryptocurrency-could-have-many-uses/\#4e07b05332b9

[^2]: Alın teriyle oluşturulmuş sermaye, Investopedia http://www.investopedia.com/terms/s/sweatequity.asp

[^3]: Metamoderasyon, yorum moderasyonunun ikinci seviyesidir. Kullanıcılar, moderasyonu geliştirmek amacıyla moderatörlerin verdiği kararları oylamaya davet edilir. https://en.wikipedia.org/wiki/Meta-moderation\_system

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