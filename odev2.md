- Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?

  - GNU
  - MIT
  - Apache
  - Creative Commons
  
Bu lisans türlerininin hepsinin ortak özelliği olarak

    - Ticari olarak dağıtılabilirler
    - Değiştirilebilirler
    - Dağıtılabilirler
  
Farklı olarak GNU'da 

    - Lisanslanamaz
    - Orjinali bulundurulmalıdır
   
MIT'te

    - Lisanslanabilir
    - Hususi olarak kullanılabilir
    - Telif ve lisansı bulundurmalısınız
  
Apache'de 

    - Lisanslanabilir
    - Hususi kullanılabilir
    - Telif ve lisansı bulundurmalısınız
    - Değişiklikleri belirtmeli ve bildirmelisiniz

  
- Merge - Squash-Rebase arasındaki farklar nelerdir?

  - Merge Commit
  
  Branchdan gelen tüm commitler Base Branch e eklenir. Yapılan birleştirmede yeni bir commit oluşturulur. Yeni Branch'taki tüm history tarafı korunarak birleştirme işlemi gerçekleşir.
  
  - Squash and Merge
  
  Bu Branchtan iki commits Base Branch ın içinde bir committe birleşir. Squash ile geçmişte atılan commitleri düzenlemek, birleştirmek için kullanılır. Bu işlemden sonra force push kullanılmalıdır.
  
  - Rebase and Merge
  
  Bu Branch tan gelen iki commit yeniden oluşturulacak ve Base Branch a eklenir. Rebase ile branch'taki commitler tek tek alınarak istediğimiz branch üzerine eklenir. Böylece tek bir history olur, istenmeyen history ortadan kalkar.
  
- Agile-Scrum-Kanban kavramlarını araştırınız

  - Agile yazılım geliştirme sürecinde karşılaşılan problemleri çözmek üzere, tekrarlanan yazılım geliştirme modeli taban alınarak geliştirilmiş, sık aralıklarla parça yazılım teslimatını ve değişikliği teşvik eden bir yazılım geliştirme modeli.
  - Scrum agile proje yönetme metodolojilerinden biridir. İnsanların mümkün olan en yüksek değere sahip ürünleri üretken ve yaratıcı bir şekilde geliştirirken, karmaşık ve adaptasyona açık sorunları ele alabildikleri bir çerçevedir. Yazılım süreçlerinin detaylı ve ihtiyaca yönelik ortaya çıkan gereksinimlerine göre esnek olabilen bir çözüm yöntemidir. Karmaşık görev listesi belirli koşullar ile küçük iş gruplarına ayrılır. Sprint denilen belirli aralıklarda ve süreleri belirli olarak bu işler  tamamlanır.
  - Kanban, talepleri kapasite ile tartarak işi yönetmenin bir yoludur. Az sayıda görevi akıcı ve eş zamanlı bir şekilde yönetebilmenizi sağlar. Kanban Board denilen görsel bir planlama aracı kullanılır. Aşamaları temsil eden sütunlarda kartların üzerine yazılmış işler listelenir. İşler ile ilgili çalışıldıkça durumları bu sütunlar arasında yerleri değiştirilerek güncellenir.

- Github Flow'un alternatifleri nelerdir? 


- Gang of Four(GOF) araştırınız.

  Tasarım desenleri(Design Patterns)  ilk defa Dörtlü Çete (GoF- Gang of Four) olarak bilinen, Eric Gamma, Richard Helm, Ralph Johnson ve John Vlissides tarafından yazılan “Design Patterns: Elements of Reusable Object-Oriented Software” kitabıyla Yazılım Mühendisliği literatüründe yerini almıştır. Design pattern kavramı bir kurallar topluluğundan ziyade bir işi nasıl ve en güzel ne şekilde yapabileceğimiz gösteren yöntemler topluluğudur. Tasarım desenleri tecrübe ile oluşturulan yapılardır. Bazıları olmazsa olmaz yapılar olmasına rağmen bazıları tamamen yazılımın sanatsal yönünü göstermek için tasarlanmıştır. Kitapta 23 kalıp yer almaktadır. Bunlardan 15 tanesi daha yoğun kullanılmaktadır. GoF Kalıpları üçe ayrılır.
  - Creational Patterns: Singleton, Factory, Abstract Factory, Builder, and Prototype
  - Structural Patterns: Composite, Decorator, Proxy, Façade, Adaptor, Flyweight, and Bridge
  - Behavioral Patterns: Strategy, Command, Observer, State, Visitor, Iterator, and Mediator, Template Method, Chain of Responsibility, and Memento


- Interface ve Abstract sınıflar arasındaki farklar nelerdir?
  
  - Abstract Sınıflar
  
  Abstract sınıf örneği alınamayan özel bir sınıf türüdür. Abstract sınıf yöntemlerini uygulayan veya geçersiz kılan alt sınıflar tarafından devralınacak şekilde tasarlanmıştır. Başka bir deyişle abstract sınıflar ya kısmen uygulanır ya da hiç uygulanamaz. Abstract sınıfta işlevselliğe sahip olunabilir. - Abstract sınıftaki yöntemler hem abstract hem concrete olabilir.  Abstract sınıf bir kurucuya sahip olabilir. - Bu abstract sınıf  ve interface arasındaki önemli bir farktır. Bileşenleri tasarlamak ve türetilmiş sınıflar tarafından uygulanması gereken bazı ortak işlevsellik düzeyini belirtmek için  abstract sınıflardan yararlanabiliriz.

  
  - Interface
  
  Interface temelde bir sözleşmedir. Herhangi bir uygulaması yoktur. Interface yalnızca yöntem bildirimlerini içerebilir, yöntem tanımlarını içermez. Ayrıca bir interface'de herhangi bir üye verisine sahip olamazsınız. Abstract sınıf tanımları alanlar ve kurucular içerebilirken, interface yalnızca olayların, yöntemlerin ve özelliklerin bildirimlerine sahip olabilir. Interface'de bildirilen yöntemler interface'i uygulayan sınıflar tarafından uygulanmalıdır. Bir sınıf birden fazla interface kullanabilir ancak yalnızca bir sınıfı genişletebilir. Interface uygulayan sınıf tüm üyelerini uygulamalıdır. Interface abstract sınıf gibi örnek oluşturamaz.
