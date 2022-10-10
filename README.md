# NKÜ Bilgisayar Mühendisliği BMB315 Web Programlama Dersi Laboratuvar Not ve Duyuruları

## Projeler

* Derste goreceginiz konulari pekistirmeniz 
amaciyla Web teknolojilerini kullanmanizi gerektirecek 
bazi projeler belirlenmistir. 
* Bu projelerden en az birini basari ile kodlamaniz beklenmektedir.
* Projelerde 6 kisiyi gecmeyecek gruplar halinde calisilabilir.
* BMB315 Github reposunda (bu repo) Discussions bolumunde 
acilacak ilgili tartisma basligi altinda her grup (veya birey)
uzerinde calismak istedigi projeyi, bu projenin uyelerini, 
her uyenin projeye hangi yonlerden katki saglamasinin planlandigini 
ve bu projeye ait Github repository linkini belirtilmelidir.
* Projeye ait Github repository'nizi duzenli olarak guncellemek 
projede hangi asamada oldugunuz gorebilmemiz ve kodlariniz ve 
tasariminizla ilgili geri donuslerde bulunabilmemiz adina onemlidir. 
* Projenizde takildiginiz yerlerde yasadiginiz sorunu bu Github
sayfasindaki Discussion bolumune yazabilirsiniz. Ogrencilerin
bu bolumde aktif olmasi ve eger bilgileri varsa sorun yasayan
arkadaslarina yardimci olmalari beklenmektedir. 
Disccussion sayfasinin lokal bir 
[Stack Overflow](https://stackoverflow.com/) benzeri bir islevi 
yerine getirmesi beklenmektedir.
* Projesini basariyla tamamlayanlarin uygulama 
ders saatinde projelerini tanitacaklari bir sunum yapmalari istenebilir.
* Proje konulari gercek sorunlardan turetilmistir.
* Laboratuvar derslerinde projelerinizde yasadiginiz sorunlar ve projelerinizde size kolaylik saglayabilecek konular uzerinde konusulmasi planlanmaktadir. Bunlara ek olarak laboratuvar derslerinde basariyla tamamlanan projelerinin sunumlarinin yapilmasi planlamaktadir.

### Konu 1: JBST Web Sitesinin Gorselliginin Iyilestirilmesi

Journal of Balkan Sciences and Technology universitemizin Fen Bilimleri
Enstitusu tarafindan yayinlanan bir akademik dergidir. Bu dergide 
yayinlanan makalelere [https://jbst-nku.github.io/](https://jbst-nku.github.io/)
adresinden erisilebilmektedir. Ilgili web sayfasindaki HTML etiketleri,
tanimlanan class ve id'lerde mumkun olan en az degisiklikle web sayfasini
gorsel olarak daha iyi gorunmesini saglayacak degisiklikleri yapiniz.

Sayfanin gorunumu iyilestirmek icin mevcut CSS dosyalarinda degisiklikler yapmaniz,
yeni CSS dosyalari tanimlamaniz ve JavaScript kullanmaniz gerekebilir.
Yapacaginiz degisiklikler sonrasi bu web sayfasi mobil cihazlarda da duzgun
gorunsun, bir diger deyisle web sitesinde gerekli degisiklik ve eklemeleri yaparken
responsive bir web sitesi yapmaya calisiniz.

Referans akademik dergi sayfasi olarak 
[https://dergipark.org.tr/tr/pub/abad](https://dergipark.org.tr/tr/pub/abad)
incelenebilir. Ayrica Journal of Balkan Sciences and Technology dergisinin
ana sayfasi [http://jbst.nku.edu.tr/](http://jbst.nku.edu.tr/)'dir.
[https://jbst-nku.github.io/](https://jbst-nku.github.io/) sayfasinin
bu sayfadaki bilgilerinde yer alacagi sekilde icerik olarak zenginlestirilmesi 
uzerinde de calisilabilinir [https://jbst-nku.github.io/](https://jbst-nku.github.io/)
sayfasinin gorselligi iyilestirildikten sonra. 

***Kullanilabilecek teknolojiler: HTML, CSS, JS***

### Konu 2: JBST CSV Generator

[jbst-website-generator](https://github.com/jbst-nku/jbst-website-generator) programi makale PDF'leri ve derginin 
her sayisi hakkinda bir takim bilgiler iceren CSV dosyalari kullanarak dergi web sitesi icin gerekli kodlari 
uretebilmektedir. 
Bu sistemde CSV dosyasinin doldurulmasi sorunlar olusturabilmektedir. Bu nedenle CSV dosyasindaki bilgilerin 
gorsel olarak guzel gozukecek bir web sitesindeki bir forma girildigi ve bu forma girilen verilere gore bir CSV dosyasinin
uretebilecegi bir web sitesi tasarlayiniz. Formdaki abstract bolumu duz metin yerine matematiksel sembollerin de 
girilebildigi zengin metin girisini desteklerse daha iyi olacaktir.

Ayrica bu web sitesinden daha once forma girilen bilgilere erisilebilmesi girilen bilgilerde ufak degisiklik, duzeltme 
yapma ihtiyaci dogdugunda faydali olacaktir. Bu amacla cookies, server side programming (PHP, nodeJS, Go vb.),
Web Storage API gibi tekniklerden biri kullanilabilir. Ya da web sitesi kullanicidan CSV dosyasi girisini destekleyebilir.
Bu sayede eski versiyon CSV dosyasi web sitesine yuklenerek eski veriler ilgili formda gozukebilir ve kullanici bu veriler
uzerinde gerekli ekleme ve degisiklikleri yapabilir. 

***Kullanilabilecek teknolojiler: HTML, CSS, JS, Server Side Programming (.net, PHP, nodeJS...), Bootstrap, Cookies, Local Storage API***

### Konu 3: Laboratuvar Ariza Kaydi Uygulamasi

Bu web sitesi
* laboratuvardaki bilgisayarda bildirilen yazilimsal ve donanimsal sorunlari hizli bir sekilde kayit altina 
almayi, 
* mevcut arizalarin kolay bir sekilde listelenebilmesini
* cozulen arizalarin kolay bir sekilde sisteme islenebilmesini
saglar. 

Bu web sitesini laboratuvar sorumlulari (Laboratuvar komisyonu uyeleri) kullanacaktir. Sorumlu sisteme giris yaptiktan sonta
bilgisayar ismini girerek ya da bilgisayara ait kare kodu okutarak ilgili bilgisayar icin kolay bir sekilde ariza kaydi 
olusturabilmelidir. Sorumlu ayni sekilde mevcut arizalari ariza tarihlerini de gorebilecek sekilde bu web sitesinde 
listeyebilmeli ve cozdugu arizalari web sitesinden ariza cozumlendi olarak isaretleyebilmelidir. Bu web sitesi mobil 
cihazlarda da duzgun goruntulenebilecek sekilde tasarlanmalidir. 

***Kullanilabilecek teknolojiler: HTML, CSS, JS, Server Side Programming (.net, PHP, nodeJS...), Bootstrap, Cookies, Responsive Design***

### Konu 4: Is gunu hesaplama Uygulamasi

Stajlariniz degerlendirilmesinde staj komisyonun ilk yaptigi islerden biri staj yaptiginiz tarihler arasinda toplam kac
is gunu oldugunu tespit etmektir. Bu is icin [https://is-gunu.hesaplama.net/hesaplama.do](https://is-gunu.hesaplama.net/hesaplama.do)
sitesi kullanilmaktadir. Ne var ki bu web sitesi gorsel olarak bu is icin oldukca karisiktir ve kullanci dostu bir arayuzu yoktur. 
Ornegin bu web sitesinde tarihleri klavyeden hizli bir sekilde girmek mumkun degildir. Sitede garip bir sekilde
haftaici gunler tatil gunu olarak secilebilmektedie. Ayni sekilde iki tarih arasi is gunlerinin ve resmi tatillerin 
tarihleri gunleri ile beraber sirali bir sekilde listelenmemektedir. Bu sitenin daha islevsel, kullanici dostu versiyonunu
tasarlayiniz. Bu web sitesini tasarladiktan sonra iki tarih arasindaki is gunlerini dondurecek bir web servis de tasarlayabilirsiniz. 

***Kullanilabilecek teknolojiler: HTML, CSS, JS, Bootstrap, Responsive Design, Web Services***

... Devami Gelecek ...
