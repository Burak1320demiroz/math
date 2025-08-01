# Kriptografi

**Kriptografi**, bilgilerin güvenliğini sağlamak amacıyla kullanılan matematiksel teknikler ve algoritmalar bütünüdür. Kriptografi, verilerin gizliliğini, bütünlüğünü, doğruluğunu, kimlik doğrulamasını ve erişim kontrolünü sağlamaya yönelik bir disiplindir. Kriptografi, özellikle dijital iletişimde ve veri güvenliğinde kritik bir rol oynar.

Kriptografi, genellikle **şifreleme (encryption)**, **şifre çözme (decryption)**, **karma (hashing)**, **imza (digital signature)** gibi işlemlerle ilişkilidir ve veri iletiminde çeşitli güvenlik tehditlerine karşı koruma sağlar.

### Kriptografinin Temel Kavramları:

1. **Şifreleme ve Şifre Çözme (Encryption and Decryption):**

   * **Şifreleme (Encryption)**: Açık (düz metin) veriyi gizli (şifreli) bir hale getirme işlemidir. Bu işlem, bir şifreleme algoritması ve bir anahtar kullanılarak yapılır.
   * **Şifre Çözme (Decryption)**: Şifreli veriyi tekrar açık metne dönüştürme işlemidir. Şifre çözme işlemi, şifreleme işlemiyle kullanılan algoritma ve anahtar ile gerçekleştirilir.

   Şifreleme genellikle iki türde yapılır:

   * **Simetrik Şifreleme (Symmetric Encryption)**: Aynı anahtar hem şifreleme hem de şifre çözme için kullanılır. Bu tür şifrelemede, anahtarın gizliliği kritik öneme sahiptir. Örnekler: AES, DES, RC4.
   * **Asimetrik Şifreleme (Asymmetric Encryption)**: Farklı anahtarlar kullanılır. Bir anahtar şifreleme için (genellikle **açık anahtar**), diğer anahtar ise şifre çözme için (genellikle **özel anahtar**) kullanılır. Örnekler: RSA, ElGamal.

2. **Anahtarlar (Keys):**

   * **Açık Anahtar (Public Key)**: Asimetrik şifrelemede kullanılan anahtardır ve herkesle paylaşılabilir. Veriyi şifrelerken kullanılır, ancak yalnızca ilgili **özel anahtar** ile çözülebilir.
   * **Özel Anahtar (Private Key)**: Asimetrik şifrelemede yalnızca sahibinin bildiği anahtardır. Veriyi yalnızca bu anahtar ile çözebilirsiniz.
   * **Simetrik Anahtar (Symmetric Key)**: Simetrik şifrelemede kullanılan ve yalnızca veriyi şifreleyen ve çözen tarafların bildiği anahtardır.

3. **Karma Fonksiyonu (Hash Function):**

   * **Karma işlevi**, herhangi bir uzunluktaki veriyi (mesaj) sabit uzunluktaki bir değere (genellikle hash kodu) dönüştüren bir matematiksel fonksiyondur. Bu işlem geri dönüşümsüzdür, yani hash kodundan orijinal veriyi geri almak mümkün değildir.

   * Karma işlevi, verilerin **bütünlüğünü** sağlamak için kullanılır; yani, bir verinin iletildikten sonra değiştirilip değiştirilmediğini kontrol etmek için kullanılır.

   * **Örnekler**: MD5, SHA-1, SHA-256, SHA-3

4. **Dijital İmza (Digital Signature):**

   * Dijital imza, bir mesajın kimden geldiğini doğrulamak ve mesajın içeriğinin değiştirilmediğini garanti etmek için kullanılır.
   * Dijital imza, asimetrik şifreleme kullanarak, mesajın hash değeri üzerinde imzalama işlemi yaparak oluşturulur. Mesajın alıcısı, göndericinin açık anahtarını kullanarak bu imzayı doğrulayabilir.

5. **Anahtar Yönetimi:**

   * Kriptografik sistemlerin güvenliği, anahtarların güvenli bir şekilde saklanmasına ve yönetilmesine bağlıdır. Anahtarlar genellikle bir **Anahtar Yönetim Sistemi (KMS)** ile güvenli bir şekilde oluşturulur, dağıtılır ve saklanır.

### Kriptografinin Temel Uygulama Alanları:

1. **Veri Gizliliği (Confidentiality):**

   * Verilerin sadece yetkili kişiler tarafından erişilebilir olmasını sağlamak için şifreleme kullanılır. Bu, e-posta, dosyalar ve diğer hassas bilgilerin gizliliğini korumak için yaygın olarak kullanılır.

2. **Veri Bütünlüğü (Integrity):**

   * Verinin, iletildiği veya depolandığı süre boyunca değiştirilmediğini garanti altına almak için karma işlevleri ve dijital imzalar kullanılır. Bu, mesajın iletim sırasında bozulmamasını sağlar.

3. **Kimlik Doğrulama (Authentication):**

   * Kriptografi, kullanıcının kimliğini doğrulamak için kullanılır. Dijital imzalar, parolalar ve dijital sertifikalar bu amaçla kullanılır. Bu, özellikle internet üzerindeki oturum açma işlemlerinde ve online bankacılıkta önemlidir.

4. **Erişim Kontrolü (Access Control):**

   * Kriptografi, belirli kaynaklara erişimi sınırlamak için kullanılır. Şifreleme, sadece yetkili kişilerin belirli verilere erişmesini sağlar.

5. **Dijital Para Birimleri (Cryptocurrencies):**

   * Kriptografi, **Bitcoin** ve **Ethereum** gibi dijital para birimlerinin temelini oluşturur. Bu tür sistemlerde, asimetrik şifreleme ve hash fonksiyonları kullanılarak işlemler doğrulanır ve güvenli hale getirilir.

6. **SSL/TLS (Secure Sockets Layer / Transport Layer Security):**

   * İnternet üzerindeki güvenli iletişim protokolleridir. SSL/TLS, verilerin şifrelenmesini, kimlik doğrulamasını ve veri bütünlüğünü sağlamak için kullanılır. Web tarayıcıları ve sunucular arasındaki HTTPS bağlantıları bu protokolleri kullanır.

7. **VPN (Virtual Private Network):**

   * VPN'ler, internet üzerindeki verileri şifreleyerek, kullanıcının internet trafiğini güvenli hale getirir. VPN, genellikle halka açık ağlar üzerinden güvenli iletişim sağlamak için kullanılır.

### Kriptografi Türleri:

1. **Simetrik Şifreleme:**

   * **AES (Advanced Encryption Standard)**: Modern simetrik şifreleme algoritmalarından biridir. 128 bit, 192 bit ve 256 bit anahtar uzunlukları kullanır.
   * **DES (Data Encryption Standard)**: Eskiden yaygın olarak kullanılan bir simetrik şifreleme algoritmasıdır, ancak kısa anahtar uzunluğu nedeniyle güvenlik açıkları vardır.

2. **Asimetrik Şifreleme:**

   * **RSA**: En yaygın kullanılan asimetrik şifreleme algoritmalarından biridir. Hem şifreleme hem de dijital imza için kullanılabilir.
   * **ECC (Elliptic Curve Cryptography)**: Daha kısa anahtarlarla güçlü güvenlik sağlamak için eliptik eğri matematiği kullanır. Özellikle mobil cihazlar ve IoT uygulamalarında tercih edilir.

3. **Hibrit Sistemler:**

   * **Hibrit kriptografi**, simetrik ve asimetrik şifreleme yöntemlerinin birleşimidir. Genellikle asimetrik şifreleme, simetrik anahtarları güvenli bir şekilde iletmek için kullanılır, ardından simetrik şifreleme veri iletimi için kullanılır. Örneğin, **TLS** protokolü.

### Kriptografi ve Güvenlik Tehditleri:

1. **Brute Force (Kaba Kuvvet) Saldırıları:**

   * Şifreyi çözmek için tüm olasılıkları sırayla deneyen saldırı türüdür. Güçlü şifreleme yöntemleri ve uzun anahtarlar, bu tür saldırılara karşı savunma sağlar.

2. **Man-in-the-Middle (MITM) Saldırıları:**

   * Bu tür saldırılar, iletişimdeki iki taraf arasında üçüncü bir kişinin gizlice veri iletmesi veya almasıdır. SSL/TLS ve dijital imzalar bu tür saldırılara karşı koruma sağlar.

3. **Hash Çakışması (Hash Collision):**

   * İki farklı veri parçasının aynı hash değerini üretmesi durumudur. SHA-1 gibi eski hash algoritmaları, çakışma olasılıkları nedeniyle kırılgan kabul edilir.

4. **Karma (Hash) Tabanlı Saldırılar:**

   * Karma fonksiyonları kırmaya yönelik saldırılar, özellikle eski ve zayıf hash algoritmaları kullanıldığında etkili olabilir.

### Özet:

Kriptografi, dijital dünyadaki güvenliği sağlamak için temel bir araçtır. Verilerin şifrelenmesi, kimlik doğrulama, veri bütünlüğü, dijital imzalar ve diğer güvenlik önlemleri, kişisel verilerden ticari sırlar ve dijital para birimlerine kadar geniş bir yelpazede uygulanmaktadır. Kriptografi, modern internet güvenliğinin temel yapı taşlarından biridir ve dijital dünyada güvenli iletişim sağlamak için
