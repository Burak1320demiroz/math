# Lineer Programlama

**Lineer Programlama (LP)**, doğrusal ilişkilerle modellenmiş bir optimizasyon problemidir. Amaç, bir hedef fonksiyonunun (genellikle kâr veya maliyet gibi) doğrusal kısıtlar altında en iyi değerini (maksimum veya minimum) bulmaktır. Lineer programlama, matematiksel modelleme ve karar verme süreçlerinde, özellikle kaynakların sınırlı olduğu durumlarda, optimal çözümler elde etmek için yaygın olarak kullanılır.

### Temel Kavramlar ve Bileşenler:

1. **Hedef Fonksiyonu (Objective Function):**

   * Lineer programlama problemi, bir hedef fonksiyonunun optimize edilmesini (maksimize veya minimize edilmesini) içerir. Hedef fonksiyonu doğrusal bir denklemle ifade edilir.
   * Örnek bir hedef fonksiyonu:

     $$
     Z = c_1x_1 + c_2x_2 + \cdots + c_nx_n
     $$

     Burada $c_1, c_2, \dots, c_n$ sabit katsayılardır ve $x_1, x_2, \dots, x_n$ ise değişkenlerdir.

2. **Kısıtlar (Constraints):**

   * Problemdeki kısıtlar, genellikle doğrusal eşitsizlikler veya denklemler olarak ifade edilir ve kaynakların sınırlı olduğu durumları modeller.
   * Her bir kısıt, şu şekilde yazılabilir:

     $$
     a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n \leq b_1
     $$

     $$
     a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n \leq b_2
     $$

     Burada $a_{ij}$ katsayılar ve $b_1, b_2, \dots, b_m$ sabitlerdir.

3. **Karar Değişkenleri (Decision Variables):**

   * Bu değişkenler, problemde optimize edilmesi gereken öğelerdir. Örneğin, üretim miktarları, taşımacılık mesafeleri, iş gücü ihtiyaçları gibi.
   * Karar değişkenleri genellikle $x_1, x_2, \dots, x_n$ ile temsil edilir ve genellikle pozitif veya sıfır olurlar.

4. **Non-Negativity Kısıtları (Non-Negativity Constraints):**

   * Karar değişkenlerinin genellikle sıfırdan küçük olamayacağı varsayılır. Yani, $x_i \geq 0$ olmalıdır.

5. **Tipik Lineer Programlama Modeli:**

   * **Hedef Fonksiyonu:**

     $$
     \text{Maksimize} \quad Z = c_1x_1 + c_2x_2 + \cdots + c_nx_n
     $$
   * **Kısıtlar:**

     $$
     a_{11}x_1 + a_{12}x_2 + \cdots + a_{1n}x_n \leq b_1
     $$

     $$
     a_{21}x_1 + a_{22}x_2 + \cdots + a_{2n}x_n \leq b_2
     $$

     $$
     x_1, x_2, \dots, x_n \geq 0
     $$

### Lineer Programlamanın Türleri:

1. **Maksimizasyon Problemleri:**

   * Hedef fonksiyonunun bir değeri (örneğin, kâr) maksimize edilmek istenir. Örneğin, bir şirketin üretim kârını artırmak amacıyla üretim miktarlarını belirlemek.
2. **Minimizasyon Problemleri:**

   * Hedef fonksiyonu, bir maliyetin en aza indirilmesi amacını taşır. Örneğin, bir lojistik firmasının taşıma maliyetlerini minimize etmek.

### Lineer Programlamanın Çözüm Yöntemleri:

1. **Simplex Yöntemi:**

   * Simplex, lineer programlamada en yaygın kullanılan çözüm yöntemlerinden biridir. Simplex algoritması, çözümü adım adım geliştirerek optimal çözümü bulur.
   * Her adımda, hedef fonksiyonun daha iyi bir değerine ulaşılacak şekilde karar değişkenlerinin değerlerini günceller.

2. **İç Nokta Yöntemleri (Interior Point Methods):**

   * İç nokta yöntemleri, özellikle büyük ve karmaşık LP problemlerinde tercih edilir. Bu yöntemler, çözüm uzayının iç kısmında hareket ederek optimal çözümü bulmaya çalışır.
   * İç nokta yöntemleri, Simplex’e göre daha hızlı olabilir ve genellikle çok büyük problemler için tercih edilir.

3. **Grafiksel Yöntem (İki Değişkenli Problemler İçin):**

   * Eğer lineer programlama problemi iki karar değişkeni ile sınırlıysa, çözüm grafikte görselleştirilebilir. Bu yöntem, küçük ölçekli problemler için kullanılır ve kısıtlar ve hedef fonksiyon bir düzlem üzerinde çizilir.
   * Optimum çözüm, kısıtlar kümesinin kesişim noktalarında bulunur.

4. **Dualite ve Çift Yönlü Problem:**

   * Her lineer programlama probleminin bir **çift** problemi vardır. Çift problemi, orijinal problemle ilişkili olan ve genellikle daha kolay çözülebilen bir problemdir.
   * **Çiftlik teoremi**: Bir primal problem ile çift problemi arasındaki ilişkiyi belirler. Eğer primal problemde bir çözüm varsa, dual problemde de bir çözüm vardır.

### Lineer Programlamanın Uygulama Alanları:

1. **Üretim Planlaması ve Kaynak Tahsisi:**

   * Bir fabrikada kaynakların (iş gücü, malzeme, makine zamanı gibi) nasıl tahsis edileceği ve üretim miktarlarının nasıl planlanacağı konusunda karar vermek.

2. **Taşıma ve Dağıtım Problemleri:**

   * Malzeme taşıma, lojistik ve dağıtım alanlarında, taşıma maliyetlerini minimize etmek veya teslimat sürelerini optimize etmek.

3. **Finansal Optimizasyon:**

   * Portföy optimizasyonu, bütçe tahsisi ve diğer finansal kararlar için en uygun stratejiyi bulmak.

4. **Zaman Planlaması ve Çalışma Akışı:**

   * İşlerin belirli bir zaman çerçevesinde nasıl sıralanacağı, kaynakların nasıl kullanılacağı, belirli hedeflere en hızlı şekilde ulaşılması için zaman çizelgesi oluşturmak.

5. **Ekipman Seçimi ve Yatırım Kararları:**

   * Bir şirketin en uygun ekipman ve makine yatırımlarını yapmak, aynı zamanda maliyetleri minimize etmek.

6. **Enerji ve Çevre Yönetimi:**

   * Enerji üretimi ve dağıtımı, çevre dostu teknolojilerin kullanımı, maliyetleri minimize etmek ve sürdürülebilir enerji çözümleri bulmak.

### Çözüm Örneği:

Bir şirketin üretim planlamasını ele alalım:

* Şirketin 2 ürünü vardır: **Ürün A** ve **Ürün B**.
* Ürün A üretmek 3 saat iş gücü ve 2 birim hammadde gerektiriyor.
* Ürün B üretmek 2 saat iş gücü ve 4 birim hammadde gerektiriyor.
* Şirketin haftada 120 saat iş gücü ve 160 birim hammadde sınırlaması vardır.
* Her ürün A'dan 5 birim kar sağlanıyor ve her ürün B'den 4 birim kar sağlanıyor.

Bu problemi çözmek için lineer programlama modeli şöyle yazılabilir:

* **Hedef Fonksiyonu (Maksimizasyon):**

  $$
  Z = 5x_1 + 4x_2
  $$

  Burada $x_1$ Ürün A'nın üretim miktarı, $x_2$ Ürün B'nin üretim miktarıdır.

* **Kısıtlar:**

  $$
  3x_1 + 2x_2 \leq 120 \quad \text{(iş gücü kısıtlaması)}
  $$

  $$
  2x_1 + 4x_2 \leq 160 \quad \text{(ham madde kısıtlaması)}
  $$

  $$
  x_1, x_2 \geq 0 \quad \text{(negatif üretim mümkün değildir)}
  $$

Bu model, Simplex veya iç nokta yöntemi gibi çözümlerle çözülerek optimal üretim miktarları ve maksimum kâr bulunabilir.

### Özet:

Lineer programlama, kaynakların sınırlı olduğu durumlarda optimum çözümler bulmak için kullanılan güçlü bir matematiksel tekniktir. Hedef fonksiyonu, doğrusal kısıtlar ve karar değişkenleri ile formüle edilir. Üretim planlaması, taşıma, finansal optimizasyon, zaman planlaması gibi
