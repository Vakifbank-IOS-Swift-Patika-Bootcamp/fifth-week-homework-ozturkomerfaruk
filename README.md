# fifth-week-homework

**4. hafta** ödevine ek olarak geliştirilen bu proje kapsamında, The Breaking Bad dizisine ek olarak, her bir bölüme özel olarak not ekleme, çıkarma ve güncelleme işlemleri eklenmiştir. Bu notların listeleneceği bir tab sekmesi eklenmiştir. Sağ alt köşeye bir Floating Button eklenmiştir. Bu eklenme ile, listeye ekleme yapılabilmektedir.

Ayrıca listede herhangi bir bölüme tıklama gerçekleştiğinde, o bölüm hakkında yazılan notlar hakkında detay sayfası açılmaktadır.

Proje kapsamında, CoreData üzerinde temel CRUD işlemleri gerçekleşmiştir. Bu kapsamda gerçekleştirilen projenin ekran videosu şu şekildedir:

https://user-images.githubusercontent.com/56068905/205379514-bf97ac4e-f5c5-4f76-9f95-a8996cab891f.mov

## Listeme Sayfası

<img width="200" src= "https://user-images.githubusercontent.com/56068905/205374367-7429b33b-0bb6-45b7-88a8-44b942603719.png" />

* Programatik olarak Floating Button
* Table View with Custom Cell

## Ekleme / Güncelleme Sayfası

<img width="200" src= "https://user-images.githubusercontent.com/56068905/205374679-8ea9cc32-ca03-4ec0-a09a-11b3bbb66d7c.png" />

Eğer listeden giriş yapılırsa *Güncelleme Sayfası, eğer kaydet butonu ile oluşturulursa *Kaydet Sayfası olmaktadır.

* Listeme Sayfası ile Delegate Pattern ile iletişim kurması
* Animasyonlu Button Collection kullanımı
* TextView kullanımı
* ImageView kullanımı
* ImagePicker kullanımı (Galeriden ya da Kameradan Fotoğraf Getirme)

## Bölüm Seçme Ekranı

<img width="200" src= "https://user-images.githubusercontent.com/56068905/205376526-1fa1797e-89d8-47f2-87d0-4889d075dc3c.png" />

Bir Pop Up olarak açılmaktadır. Amacı bölümü seçip, not ekleme / güncelleme sayfasında kullanılmasını sağlamaktadır. Bu sebeple delegate pattern olacak şekilde kullanılmıştır.

## CoreData Kullanımı

<img width="500" alt="image" src="https://user-images.githubusercontent.com/56068905/205377149-afe152d2-1153-4796-affe-44291c8c4ab2.png">

Image olarak CoreData'ya CRUD işlemleri de eklenmiştir. Yani: Create, Read, Update, Delete



### 2- Clean Code - 5, 6, 7, 8 chapterlar özetlenmelidir.

### 3- Crack the Interviews - 1, 2, 3 Çalışılacak.
 
### 4- Leet Code üzerinden seçilmiş 3 soru çözülecek ve soruya ait görseller repoya eklenecek. 
Soru çözüldükten sonra submission kısmından görseli alabilirsiniz. Örn:

<img width="584" alt="image" src="https://user-images.githubusercontent.com/65663370/204152185-1f073bb2-4e0d-4466-b29f-61adcbe15a8f.png">

# Ödev Hakkında Birkaç Söz

Öncelikle ödevleri kendi repomda yapmaktayım ve kendi repomda düzenli olarak commit atarak ilerlemekteyim. Kendi repoma gitmek için [tıklayabilirsiniz.](https://github.com/ozturkomerfaruk/Patika-Vakifbank-iOS-Bootcamp/tree/master/Ödevler/5.%20Hafta)

Bu ödev kapsamında, ödeve ek olarak gerçekleştirmek istediğim: Image dosyası tutmak olmuştur. Bu kapsamda, CoreData'ya kameradan ya da galeriden Image kullanımı kullanımını gerçekleştirmeyi ve bunu veri tabanına kaydetmeyi dersten harici olarak öğrendim. Elimden geldiğince yine animasyonları kullanmaya çalıştım. Tasarım konusunda gerçekten çok iyi şeyler yapmaya çalışmaya çalışsam da olmuyor. Ben de teknik olarak işlem yapmaya, yeni şeyler öğrenmeye çaba sarfettim ödev kapsamında. Delegate Pattern kullanımına ağırlık vermeye çalıştım ve gerçek manada Delegate Pattern'in mantığını kafamda oturtmaya çalıştım.

Sıkıntı olarak ödev hakkında söyleyebileceğim tek şey, MVC mimarisinde geliştirilen bu ödevde, View Controller sayfaları yazılırken, bütün işlemlerin tek sayfada gerçekleşiyor oluşu kod okunurluğunu gerçek manada azalttığını farkettim. 6. Hafta kapsamında artık Bootcamp sürecinde, MVVM ve VIPER mimarilerine giriş yapılıyor olacak ve kendimi orada geliştirmeye çalışacağım. Eğer fırsatım olursa ilerleyen zamanlarda, bu projeleri MVVM mimarisine geçmeyi isterim ya da bundan sonra ki süreçlerde MVVM yada VIPER olarak kullanabilmeyi isterim.

iOS gerçek manada bir derya ve ben gerçek manada bu alanda öğrendiğim her şeye hayran olarak yaklaşıyorum. Eylül 2022 ayında tanıştım daha yeni tanıştım sayılır iOS ile ve çok zevk aldığımı hissediyorum.

Son olarak, ödev olarak LeetCode ödev verilmesine çok sevindim açıkcası. Düzenli olarak çözmeye çalıştığım bir platform. LeetCode ve Hackerrank güzel siteler 👍
