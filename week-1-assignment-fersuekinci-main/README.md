# JAVA 11 İLE GELEN YENİLİKLER
* Java dosyasını tek bir komut ile çalıştırma özelliği gelmiştir.
* Yeni string methodları gelmiştir.
  * isBlank() : Boolean methodtur. String'in dolu olup olmadığını kontrol eder.
  * lines() : String ifadesindeki satır sonlandırıcına göre Stream API değeri verir.
  * repeat() : İçine verilen parametre değeri kadar stringi tekrar eder.
  * stripLeading() : Bu method string objesinin içerisindeki ilk whitespace olmayan karakter öncesindeki whitespace karakterlerini kaldırırır.
  * stripTrailing() : Bu method string objesinin içerisindeki son whitespace olmayan karakter sonrasındaki whitespace karakterlerini kaldırırır.
  * strip() : Bu method string objesinin içerisindeki whitespace karakterlerini kaldırırır. trim() methodundan farkı Unicode desteği olmasıdır.
* Yeni dosya methodları eklenmiştir.
  * writeString() : Dosyaya yazma işlemi gerçekleştirir.
  * readString() : Dosyadan okuma işlemi geröekleştirir.
  * isSameFile() : Boolean methodtur. İki dosyanın aynı olup olmadığını kontrol eder.
* Java 10 ile gelen var ifadesinin kapsamı genişletilerek lambda expressions ile kullanma imkanı gelmiştir.
* Sınıf içerisinde yer alan alt sınıfların derlenmesinde değişiklik yapılarak nest olarak adlandırılan bir yapı kurulmuştur.
* Nest-based yapısına göre derlenen sınıflar ile ilgili detaylı bilgi almak için Class sınıfına getNestHost(), getNestMembers(), isNestmateOf() metotları eklenmiştir.
* Dosya/Dizin yolunu ifade etmek için kullanılan Path arayüzüne of metotları eklenmiştir.
* Koleksiyonları dizilere çevirmek için toArray(IntFunction) metodu eklenmiştir.
* Java ile Input/Output işlemlerinde kullanılan java.io paketine yeni nullInputStream(), nullOutputStream(), nullReader(), nullWriter(), readNBytes() metotları eklenmiştir.

# JAVA 17 İLE GELEN YENİLİKLER
* Restore Always-Strict Floating-Point Semantics : Floating-point operasyonlarını sürekli katı hale getirir. Bu da her platformda floating-point hesaplamalarından aynı sonuçların alınmasını sağlar.
* Enhanced pseudo-Random Number Generators : Sözde Rastgele Sayı Üreticileri (PRNG) için yeni arayüzler ve uygulamalar sağlar.
* Strongly Encapsulated JDK Internals : JDK'nın tüm kritik olmayan dahili öğelerini güçlü bir şekilde kapsar.
* Sealed Classes : Java programlama dilini sealed sınıflar ve arayüzlerle geliştirir. Sealed sınıflar ve arayüzler, diğer sınıfların veya arayüzlerin bunları genişletebileceğini veya uygulayabileceğini kısıtlar.
* Foreign Functions & memory API(Incubator) : Java programlarının, Java çalışma zamanının dışındaki kod ve verileri yorumlayabileceği bir API sunar.
* Vector API(Second Incubator) : Çalışma zamanında en uygun vektör talimatlarına güvenilir bir şekilde derlenen vektör hesaplamalarını ifade etmek için bir API sunar.
* Context-Specific Deserialization Filters : Uygulamaların bağlama özel ve dinamik olarak seçilen seri durumdan çıkarma filtrelerini yapılandırmasına olanak tanır.
 
