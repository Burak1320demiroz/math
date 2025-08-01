# Topoloji

**Topoloji**, matematiksel bir dal olup, şekillerin ve uzayların özelliklerini, genellikle *uzayın* "şekil değiştirme" işlemlerinden bağımsız olarak inceleyen bir teoridir. Topoloji, "uzayın yapısını" ve onun üzerinde tanımlı olan *yakınlık*, *bağlantılılık* ve *süreklilik* gibi özellikleri ele alır. Özellikle, şekillerin boyutları ve benzeri özellikleri değiştirilebilecek bir şekilde ele alınır. Başka bir deyişle, iki şeklin topolojik olarak birbirine dönüşüp dönüşemeyeceğini inceleyen bir teoridir.

### Topolojinin Temel Kavramları:

1. **Topolojik Uzay:**

   * Bir topolojik uzay, genellikle bir *küme* ve bu küme üzerindeki *topoloji*dan oluşur. Bir topoloji, kümeler üzerinde belirli bir kurallar bütünü ile tanımlanır ve her bir alt küme ile ilgili *açık kümeler* (open sets) belirler.
   * Topolojik uzay, temel olarak bir uzay üzerinde *yakınlık* ve *süreklilik* gibi kavramları ele almak için kullanılır.

2. **Açık Küme (Open Set):**

   * Bir küme, üzerinde tanımlanan topolojide açık küme olarak kabul edilir, eğer herhangi bir noktayı içeren bir "küçük" komşuluk seti bu küme içinde yer alıyorsa. Matematiksel olarak, bir topolojik uzayda $U$ kümesi, eğer her eleman $x \in U$ için bir komşuluk kümesi varsa, $U$ açık küme olarak kabul edilir.

3. **Kapalı Küme (Closed Set):**

   * Bir küme, açık kümelerin tamamlayanı olarak *kapalı* bir küme olur. Yani bir küme, eğer kendi içerisinde limit noktaları içeriyorsa ve dışındaki herhangi bir noktayı dışarıda bırakıyorsa, bu küme kapalı küme olarak kabul edilir.
   * Örneğin, $\mathbb{R}$ üzerinde bir sayı kümesi, tüm limit noktaları da içeriyorsa kapalı küme olur.

4. **Açık ve Kapalı Kümeler Arasındaki İlişki:**

   * Topolojide açık küme ve kapalı küme tanımları tersine bağlıdır. Yani, bir küme açık ise, tamamlayanı kapalıdır ve bir küme kapalı ise, tamamlayanı açıktır.

5. **Süreklilik (Continuity):**

   * Bir fonksiyon, topolojik uzaylar arasında tanımlandığında, bu fonksiyon sürekli olarak kabul edilir, eğer küçük değişiklikler fonksiyonun sonucunda küçük değişikliklere yol açıyorsa. Başka bir deyişle, sürekli bir fonksiyon, bir noktadan komşuluklar üzerinden giden fonksiyonlar için araya herhangi bir "kopukluk" veya "kesilme" koymaz.

6. **Bağlantılılık (Connectedness):**

   * Bir uzay, bağlantılı olarak kabul edilir, eğer bu uzayı, ara kesmede iki parçaya ayıramıyorsanız. Yani, bir topolojik uzayda her iki nokta arasında bir yol bulabiliyorsanız, bu uzay bağlantılıdır.
   * Örneğin, bir çember, bağlantılı bir uzaydır çünkü her iki nokta arasında sürekli bir yol bulunabilir.

7. **Kompaktlık (Compactness):**

   * Bir topolojik uzay, eğer her açıktaki açık kümelerin sonsuz sayıda alt kümelerinden seçilebilen bir sayıda sonlu kümeyi kapsıyorsa, bu uzay kompakt olarak kabul edilir.
   * Bu özellik, uzayın "kapanma" özellikleriyle ilgilidir. Yani bir uzay, içindeki her açık kümeyi sonlu alt kümelerle "kapalı" yapabiliyorsa kompakt kabul edilir.
   * **Heine-Borel Teoremi:** Euklid uzayında, kompaktlık, her açık örtüsünün sonsuz sayıda alt kümesinin sonlu bir alt kümesini içerecek şekilde sağlanabilir.

8. **Yalnızca Bağımsız Değişiklikler:**

   * Topoloji, şeklinin değiştirilmeden özelliklerini inceleyen bir alandır. Örneğin, bir daireyi büküp bir üçgen haline getirmek topolojik bir değişiklik değildir; ancak bir daireyi kesmek, topolojik bir değişiklik sayılabilir.

### Topoloji Türleri:

1. **Genel Topoloji (Point-Set Topology):**

   * Genel topoloji, topolojik uzayların temel yapısını ve bunlar arasındaki ilişkileri inceler. Temel kavramlar burada ele alınan kavramlardır: açık kümeler, kapalı kümeler, süreklilik, kompaktlık, bağlantılılık, ayrılabilirlik gibi.

2. **Algebraik Topoloji:**

   * Bu dal, topolojik uzayların algebraik yapılarını inceler. En temel örneklerinden biri **homoloji** ve **kohomoloji** teorileridir. Ayrıca **temel grup** (fundamental group) gibi kavramlar da algebraik topolojinin incelenen konularıdır.

3. **Diferansiyel Topoloji:**

   * Diferansiyel topoloji, özellikle **diferansiyel geometrinin** ve **diferansiyel denklemlerin** kullanıldığı alanlardır. Bu dal, diferansiyel yapıların topolojik özellikleriyle ilgilenir.

4. **Geometrik Topoloji:**

   * Geometrik topoloji, topolojik uzayların geometri açısından özelliklerini inceler. Örneğin, manifoldlar ve düzensizlikler, bu dalda ele alınır.

### Önemli Teoremler ve Kavramlar:

1. **Brouwer Sabit Nokta Teoremi:**

   * Bu teorem, sürekli bir fonksiyonun bir topolojik uzayda en az bir sabit noktası olduğunu belirtir. Yani, bir fonksiyon $f$ için, $f(x) = x$ koşulunu sağlayan bir $x$ noktası her zaman bulunur.

2. **Jordan Eğri Teoremi:**

   * Bu teorem, düzlemde kapalı bir eğrinin iki bölgeye (iç ve dış) ayırdığını belirtir. Bu, topolojik düzlemde çok önemli bir özelliktir.

3. **Uygulamalar:**

   * **Kümeler Arasındaki İlişkiler:** Topolojik uzayların incelenmesi, veri kümelerinin birbirine olan mesafesini belirlemek, veri analizlerinde, özellikle çok değişkenli veri analizi ve kümeleme algoritmalarında kullanılır.
   * **Manifoldlar ve Eğriler:** Geometrik ve fiziksel problemler için topolojik kavramlar sıklıkla kullanılır. Örneğin, **diferansiyel geometri** ve **kuramsal fizik** alanlarında manifoldlar ve eğriler önemli bir yer tutar.
   * **Karmaşık Sayılar ve Fonksiyonlar:** Analizle ilgili alanlarda topolojik yapılar, karmaşık fonksiyonlar, diferansiyasyon ve entegrasyon teorilerinin temellerini oluşturur.

### Örnekler ve Uygulamalar:

1. **Sürekli Fonksiyonlar:**

   * $f: \mathbb{R} \to \mathbb{R}$ fonksiyonu sürekli ise, bu fonksiyonun tanım kümesindeki herhangi bir açık küme, görüntüsündeki açık kümeyle ilişkilidir.

2. **Manifoldlar:**

   * $\mathbb{R}^n$'deki her nokta, bir manifold olabilir. Özellikle, uzayda daha karmaşık yapıların, eğrilerin ve yüzeylerin analizi yapılabilir.

3. **Çok Boyutlu Veri:**

   * Topolojik veriler, çok boyutlu verilerin üzerinde yapılan analizlerde faydalıdır. Örneğin, **topolojik veri analizi** (TDA), kümeler ve çoklu boyutlu uzaylar arasındaki ilişkileri inceleyen bir alandır.

### Özet:

Topoloji, geometrinin daha soyut bir biçimi olarak, şekillerin ve uzayların özelliklerini, özellikle de *süreklilik*, *bağlantılılık*, *kompaktlık* ve *yakınlık* gibi kavramları ele alır. Genellikle "şekil değiştirme" ve *deforme etme* gibi süreçlere karşı korunabilen özellikleri inceler. Matematiksel teorilerin yanı sıra, topoloji çeşitli mühendislik, fizik, bilgisayar bilimleri ve veri analizi gibi alanlarda da geniş bir uygulama yelpazesi bulur.
