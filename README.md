# fifth-week-homework

# iOS

[4. Hafta](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/fourth-week-homework-ozturkomerfaruk) ödevine ek olarak geliştirilen bu proje kapsamında, The Breaking Bad dizisine ek olarak, her bir bölüme özel olarak not ekleme, çıkarma ve güncelleme işlemleri eklenmiştir. Bu notların listeleneceği bir tab sekmesi eklenmiştir. Sağ alt köşeye bir Floating Button eklenmiştir. Bu eklenme ile, listeye ekleme yapılabilmektedir.

Ayrıca listede herhangi bir bölüme tıklama gerçekleştiğinde, o bölüm hakkında yazılan notlar hakkında detay sayfası açılmaktadır.

Proje kapsamında, CoreData üzerinde temel CRUD işlemleri gerçekleşmiştir. Bu kapsamda gerçekleştirilen projenin ekran videosu şu şekildedir:

https://user-images.githubusercontent.com/56068905/205486285-8e764300-6808-4da7-9ea3-f2ddd51c7014.mov

## Listeme Sayfası

<img width="200" src= "https://user-images.githubusercontent.com/56068905/205374367-7429b33b-0bb6-45b7-88a8-44b942603719.png" />

* Programatik olarak Floating Button
* Table View with Custom Cell

## Ekleme / Güncelleme Sayfası

<img width="200" src= "https://user-images.githubusercontent.com/56068905/205486239-b1bafec0-9baf-419f-bcda-6c3adbdeab61.png" />

Eğer listeden giriş yapılırsa *Güncelleme Sayfası, eğer kaydet butonu ile oluşturulursa *Kaydet Sayfası olmaktadır.

* Listeme Sayfası ile Delegate Pattern ile iletişim kurması
* Animasyonlu Button Collection kullanımı
* TextView kullanımı
* ImageView kullanımı
* ImagePicker kullanımı (Galeriden ya da Kameradan Fotoğraf Getirme)

## Bölüm Seçme Ekranı

<img width="200" src= "https://user-images.githubusercontent.com/56068905/205486253-999b2d7f-6e7c-4e30-a0d9-ea8c4e6c695b.png" />

Bir Pop Up olarak açılmaktadır. Amacı bölümü seçip, not ekleme / güncelleme sayfasında kullanılmasını sağlamaktadır. Bu sebeple delegate pattern olacak şekilde kullanılmıştır.

## CoreData Kullanımı

<img width="500" alt="image" src="https://user-images.githubusercontent.com/56068905/205377149-afe152d2-1153-4796-affe-44291c8c4ab2.png">

Image olarak CoreData'ya CRUD işlemleri de eklenmiştir. Yani: Create, Read, Update, Delete

# LeetCode

<img width="700" alt="image" src="https://user-images.githubusercontent.com/56068905/205395589-96561bd7-ae0d-429c-afea-6697b78b0443.png">

LeetCode profilime gitmek için [tıklayabilirsiniz.](https://leetcode.com/omerfarukozturk026/) Hedefim şubat ayına kadar en az 50 soru çözmüş olmak.

# CleanCode

Kitap özetini kendi repomda düzenli olarak çıkarmaktayım. Commit tarihleri düzenli olarak orada gözükmektedir.

# Ödev Hakkında Birkaç Söz

Öncelikle ödevleri kendi repomda yapmaktayım ve kendi repomda düzenli olarak commit atarak ilerlemekteyim. Kendi repoma gitmek için [tıklayabilirsiniz.](https://github.com/ozturkomerfaruk/Patika-Vakifbank-iOS-Bootcamp/tree/master/Ödevler/5.%20Hafta)

Bu ödev kapsamında, ödeve ek olarak gerçekleştirmek istediğim: Image dosyası tutmak olmuştur. Bu kapsamda, CoreData'ya kameradan ya da galeriden Image kullanımı kullanımını gerçekleştirmeyi ve bunu veri tabanına kaydetmeyi dersten harici olarak öğrendim. Elimden geldiğince yine animasyonları kullanmaya çalıştım. Tasarım konusunda gerçekten çok iyi şeyler yapmaya çalışmaya çalışsam da olmuyor. Ben de teknik olarak işlem yapmaya, yeni şeyler öğrenmeye çaba sarfettim ödev kapsamında. Delegate Pattern kullanımına ağırlık vermeye çalıştım ve gerçek manada Delegate Pattern'in mantığını kafamda oturtmaya çalıştım.

Sıkıntı olarak ödev hakkında söyleyebileceğim tek şey, MVC mimarisinde geliştirilen bu ödevde, View Controller sayfaları yazılırken, bütün işlemlerin tek sayfada gerçekleşiyor oluşu kod okunurluğunu gerçek manada azalttığını farkettim. 6. Hafta kapsamında artık Bootcamp sürecinde, MVVM ve VIPER mimarilerine giriş yapılıyor olacak ve kendimi orada geliştirmeye çalışacağım. Eğer fırsatım olursa ilerleyen zamanlarda, bu projeleri MVVM mimarisine geçmeyi isterim ya da bundan sonra ki süreçlerde MVVM yada VIPER olarak kullanabilmeyi isterim.

iOS gerçek manada bir derya ve ben gerçek manada bu alanda öğrendiğim her şeye hayran olarak yaklaşıyorum. Eylül 2022 ayında tanıştım daha yeni tanıştım sayılır iOS ile ve çok zevk aldığımı hissediyorum.

Son olarak, ödev olarak LeetCode ödev verilmesine çok sevindim açıkcası. Düzenli olarak çözmeye çalıştığım bir platform. LeetCode ve Hackerrank güzel siteler 👍
