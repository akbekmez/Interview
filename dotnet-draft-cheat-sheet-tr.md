# Draft Cheat Sheet
## Değişkenler
Belirli bir veri tipine sahip olan bellekteki saklama alanlar.
## Veri tipleri, 
ne tür veri tutulabilecegi.
## Değer tipleri
Değerleri doğrudan saklar.
Bellekte tutulan veri tipi.
Küçük veya sabit boyutlu.
## Referans tipleri
Verinin bellekteki adresini tutar. Bellekteki bir noktayı işaret eder.
String, class, array
Daha büyük veri yapıları, nesne ve diziler.
Bellekte daha fazla yer kaplar. Çünkü sadece referansları tutulur.
## If
Bir durumu kontrol etmek için.
Tek bir koşul üzerindeki işlemlerde.
Koşullar çok ve karmaşık olduğunda.
## Switch
Tek bir değişkenin farklı sabit değerlerine bakarak işlem yapmak için.
Okunabilir ve verimlidir.
## While
Şartlar doğru olduğu sürece.
Koşulu başta kontrol et.
Koşulun ne kadar süre geçerli olduğu belli olmayan durumlarda.
## DoWhile, en az birkez çalış, koşulu sonra kontrol et.
## For
Döngü.
Sayaçlı, başı sonu belli.
Başlangıcı, koşulu, artış işlemi belirtilen.
Belirli sayıda iteration yapmak gerektiğinde.
## Foreach
Collection üzerinde gezinmek istenildiğinde.
## Array
Sabit boyutlu veri yapısı.
Bellekte ardışık olarak saklanır.
Boyutu değişmez.
Performans ve bellek optimizasyonu gerektiğinde.
Veri boyutu sabit olduğunda.
## List<>
Dynamic boyutta, sıralı, genellikle kolleksiyonlar üzerinde işlem gerektiren durumlarda.
Dinamik veri yapısı.
Ekleme, silme gibi işlemler kolaydır.
## Collection
Dictionary, Queque, Stack vb.
Daha karmaşık veri yapısı.
Belirli düzende saklanır.
Arama, sıralama gibi işlemler performanslıdır.
## IEnumerable
Sırasıyla her öğe üzerinde işlem yapmak için.
Belleğe tüm öğeleri yükledikten sonra işlem yapar.
## IQueryble
Genellikle veri kaynaklarından veri çekmek için uygundur. 
Verimlidir.
Sorgu gönderilmeden önce veriler filtrelenir ve sonuç yanlızca gerekli öğeleri içerir.
## Class
Nesnenin yapısını ve davranışını tanımlar.
Nesnenin özelliklerini ve özellikleri değiştirebilecek methodlar içerir.
## Object
Sınıfın bir örneğidir.
Nesne(class) bir şablon iken, gerçek varlıktır. 
## Constructure
Sınıfın yeni bir örneği oluşturulduğunda çalışır. 
Genellikle başlangıçta durumları belirlemek için.
## Property
Sınıf içinde tanımlanan veri elemanı.
## Encapsulation
Propertylerin doğrudan erişime kapalı olması.
Sadece methodlar üzerinden gerekli olanların değiştirilebilir olması. 
Property private, method public. 
Veri güvenliği ve bütünlüğü korumak için.
## İnheritance
Bir sınıfa, özellik ve methodlarının devredilmesi
Kod tekrarı azaltır.
Kullanılabilirliği artırır.
## Polymorphizm
Aynı isimli methodların farklı şekilde çalışması. Get() Get(int ID) vb..
Bir sınıfın methodu, türemiş sınıflarda farklı şekilde çalışması (virtual, override)
## İnterface
Method ve özellik tanımı. 
Birden fazla olabilir.
Nasıl çalıştığı sınıflarda belirlenir.
## Static Member
Sınıfın örneği olmadan doğrudan sınıfa ait üyeler.
Sınıf adı ile erişilir.
## İnstance Member
Sınıfın örneği üzerinden erişilir.
Her nesnede farklı değerler taşıyabilir.
## Abstract
Türeyen sınıflar için temel yapı.
Soyut ve somut methodlar.
Miras verir.
Doğrudan örneği oluşturulamaz. 
## Methodlar
Belirli bir işlevi yerine getiren.
Tekrar kullanılabilirliği sağlayan yapı.
Property, methodlara veri iletmek için. 
## Pass-by-Value, 
Gönderilen değerlerin kopyasını iletir.
Method içinde değişse bile dışarıyı etkilenmez.
Değişken değerinin değişmemesi istendiğinde.
## Pass-by-Reference
REF yada OUT kullanılır. 
Method içerisindeki değişiklik dışarıyı etkiler.
Değişken değerinin doğrudan değişmesi istenildiğinde.
## LinQ
Collection üzerinde sorgulama yapma.
## Async
Asenkron programlama sağlar.
Uygulama kilitlenmeden arka planda yürütür.
Await, işlemin tamamlanmasını bekler, thread blocklanmaz.
Deadlock, sync çağrıların async işlemleri bloklaması. Await kullan.
## Delegates
Bir methodu temsil etmek için kullanılan tür. 
## Func/Action
Blog tanımlı delege türleri.
Func, değer döndüren delege.
Action, dönüş değeri olmayan delege.
## Events
Bir olay gerçekleştiğinde tetiklenen mekanizma.
Genellikle etkileşim ve değişiklikler yanıt olarak kullanılır.
Ben ata bindim. Sende bin.
Ben ata bindiğimde… 
## Extension Method
Var olan türe yeni bir method eklemek.
## EfCore
Nesne yönelimli orm aracı.
Migration, değişiklikleri kod üzerinde yönetme.
## Web API
Http ile veri alışverişi.
Restful servisler geliştirilir.
Get, veri alır. URL üzerinden taşınır.
Post, veri gönderir. Body üzerinden taşınır.
Güvenlik ve veri boyutu acısından get ve post farklıdır.
## Katmanlı mimari
Sorumlulukları ayırmak.
Sürdürülebilir ve test edilebilir bir yapı.
## Repository Patern
İşlemleri soyutlayan bir desen.
Db’ye doğrudan erişmek yerine aracı desen.
Test edilebilirliği artırmak.
## Git
Sürüm kontrol sistemi.
## Clean Code
Okunabilir, anlaşılabilir, sürdürülebilir kod yazma yaklaşımı.
Yorum gerektirmeyen, anlamlı isimlendirme, tek sorumluluk(single responsibility) prensibine dayalı yaklaşım.
## DTO
Data transfer object
Veri taşıma modeli
Sadece gerekli propertyler yer alır.
Güvenlik ve performans sağlar.

## Swagger
Apilerin test ve dokümantasyon aracı.
Anlaşılmayı ve testi kolaylaştırır.
## SOLID
### Dependency inversion
Soyutlama detaylara değil, detaylar soyutlama ya bağlıdır.
### Open/Closed
Sınıfın gelişime açık, değişmeye kapalı olması.
A sınıfına x,y,z interfacelerinin kalıtım yolu ile uygulanması.
## Middleware
Http pipeline da isteği karşılayan ara katman.
## CQRS
Command Query Responsibility Segregation
Command(veri yazma) ve Query(okuma) işlemini ayırıp performans ve ölceklenebilirlik sağlar.
## Tests
### Unit
Tek bir konuyu test eder.
Dış bağımlılık barındırmaz.
Hızlıdır.
