# Olasılık

**Olasılık (Probability)**, rastgele olayların ve belirsizliklerin matematiksel modellemesiyle ilgilenen bir matematiksel disiplindir. Olasılık teorisi, belirli bir olayın gerçekleşme olasılığını hesaplamak ve bu olaylarla ilgili genel kuralları ortaya koymak için kullanılan bir araçtır. Bu alan, istatistik, finans, mühendislik, bilgisayar bilimleri, yapay zeka ve pek çok diğer uygulama alanı için temel oluşturur.

### Olasılığın Temel Kavramları:

1. **Deney (Experiment):**

   * Deney, bir sonucun (ya da bir olayın) rastgele olarak gözlemlendiği bir süreçtir. Örneğin, bir zar atmak, bir kart çekmek ya da bir kumar oyunu oynamak gibi.

2. **Olay (Event):**

   * Olay, bir deneyin gerçekleşmesiyle elde edilen sonuçlardır. Olaylar, **genişletilmiş** bir olay (örneğin, çift sayı gelmesi) veya **basit bir olay** (örneğin, bir zar atıldığında 3 gelmesi) olabilir.

3. **Örneklem Uzayı (Sample Space):**

   * Örneklem uzayı, bir deneyde olabilecek tüm olası sonuçların kümesidir. Örneğin, bir zar atıldığında örneklem uzayı $\{1, 2, 3, 4, 5, 6\}$ olacaktır.

4. **Olasılık (Probability):**

   * Olasılık, bir olayın gerçekleşme olasılığını belirleyen bir sayıdır. Olasılık her zaman 0 ile 1 arasında bir değere sahiptir.

     * **0**: Olay kesinlikle gerçekleşmez.
     * **1**: Olay kesinlikle gerçekleşir.
     * **0 < P < 1**: Olayın gerçekleşme olasılığı kısmi olarak belirlenmiştir.

   Olasılık genellikle şu şekilde hesaplanır:

   $$
   P(A) = \frac{\text{A olayının başarılı olduğu durumlar}}{\text{Tüm olası durumlar}} 
   $$

   Burada, $A$ bir olaydır.

5. **Şartlı Olasılık (Conditional Probability):**

   * Şartlı olasılık, bir olayın gerçekleşmesinin, başka bir olayın gerçekleştiği bilindiği durumda hesaplanmasıdır.
   * Örneğin, bir zar atıldığında, "zarın üst yüzeyinde çift bir sayı bulunma olasılığı" şartlı bir olasılıktır, eğer zarın tek sayılardan biri olduğunu biliyorsanız.

6. **Bağımsız Olaylar (Independent Events):**

   * İki olay birbirinden bağımsızsa, bir olayın gerçekleşmesi, diğerinin olasılığını etkilemez. Yani, $P(A \cap B) = P(A) \cdot P(B)$.

7. **Birleşim ve Kesişim Olayları (Union and Intersection):**

   * **Birleşim** (Union): Birden fazla olayın gerçekleşmesi durumu. $A \cup B$ ifadesi, ya $A$ ya da $B$ olaylarının gerçekleşmesini ifade eder.
   * **Kesişim** (Intersection): Hem $A$ hem de $B$ olaylarının gerçekleşmesi durumu. $A \cap B$ ifadesi, her iki olayın da aynı anda gerçekleşmesi anlamına gelir.

8. **Mutlak ve Koşullu Olasılık Kuralları:**

   * **Total Probability Theorem (Toplam Olasılık Teoremi):** Şartlı olasılık kurallarına dayanarak, tüm olasılıklar arasında genel bir olasılık hesaplaması yapılabilir.
   * **Bayes Teoremi:** Şartlı olasılıkların birbirleriyle ilişkilendirilmesine olanak tanır ve özellikle **istatiksel modelleme**de kullanılır. Bayes teoremi, yeni gözlemler ışığında olayların olasılıklarını güncellemeye yardımcı olur.

### Olasılık Dağılımları:

1. **Diskret Olasılık Dağılımları:**

   * **Diskret dağılımlar**, sayılabilir bir sonlu ya da sonsuz sayıda olası sonuca sahip olaylar için kullanılır.
   * **Bernoulli Dağılımı**: İki sonuçlu bir deneyin olasılık dağılımıdır. Örneğin, bir madeni para atıldığında, yazı veya tura gelme olasılıkları.
   * **Binom Dağılımı**: Bir deneyin birden fazla tekrarı sonucunda belirli bir sonucun olma olasılığıdır. Örneğin, 10 kez madeni para atıldığında, yazı gelme olasılığı.
   * **Poisson Dağılımı**: Belirli bir süre diliminde nadir olayların gözlemlenme olasılığını modelleyen dağılımdır. Örneğin, bir çağrı merkezi için saatte alınan çağrı sayısı.

2. **Sürekli Olasılık Dağılımları:**

   * **Sürekli dağılımlar**, sayılabilir olmayan bir dizi olasılığı modelleyen dağılımlardır. Bu dağılımlar genellikle belirli bir aralıkta bir sayı alabilir.
   * **Normal Dağılım** (Gauss Dağılımı): Çoğu doğal ve sosyal fenomenin, örneğin boy uzunluğu ya da test puanları gibi, normallik gösterdiği bir dağılımdır. Bu dağılımda olayların çoğu ortada toplanır ve uçlarda nadiren görülür.
   * **Üstel Dağılım**: Süreklilik gösteren olayların zaman arasında gerçekleşme olasılıkları için kullanılan dağılımdır. Örneğin, bir cihazın arıza süresi.
   * **Uniform Dağılım**: Olasılık her değerde eşit olan bir dağılımdır. Örneğin, bir zarın her bir yüzeyinin eşit olasılıkla gelmesi.

### Olasılık Kuralları ve Teoremleri:

1. **Olasılık Aksiyomları:**

   * Olasılık teorisinin temeli **Kolmogorov'un aksiyomlarına** dayanır. Bu aksiyomlar şunlardır:

     1. $P(S) = 1$, yani örneklem uzayının (S) olasılığı 1’dir.
     2. $P(A) \geq 0$, yani herhangi bir olayın olasılığı sıfırdan küçük olamaz.
     3. Eğer $A$ ve $B$ iki bağımsız olaysa, o zaman $P(A \cup B) = P(A) + P(B)$.

2. **Bayes Teoremi:**

   * Bayes Teoremi, bir olayın olasılığını, diğer olaylar hakkında sahip olduğumuz bilgilere dayalı olarak güncellememizi sağlar. Matematiksel formülü şöyle ifade edilir:

   $$
   P(A|B) = \frac{P(B|A) P(A)}{P(B)}
   $$

   Burada, $P(A|B)$, $B$ olayının bilindiği durumda $A$ olayının olasılığıdır.

3. **Büyük Sayılar Kanunu:**

   * Bu kanun, çok sayıda bağımsız ve aynı dağılıma sahip rastgele değişkenlerin ortalamasının, gerçek ortalamaya yakınsayacağını belirtir. Örneğin, bir zarın sayısının ortalamasının 3.5'e yaklaşması.

4. **Merkezi Limit Teoremi (Central Limit Theorem):**

   * Bu teorem, bağımsız ve dağılımı bilinmeyen rastgele değişkenlerin ortalamalarının dağılımının, örneklem büyüklüğü arttıkça **normal dağılıma** yaklaşacağını belirtir.

### Olasılık ve İstatistik:

Olasılık teorisi, **istatistik** için temel bir altyapı sunar. İstatistik, olasılık modelleri üzerine çalışarak gerçek dünya verilerini analiz eder ve bu verilerden genelleme yapar. Olasılık teorisi, verilerin dağılımını anlamak, örneklem analizleri yapmak, modelleme ve tahminlerde bulunmak için kullanılır.

* **Tahmin ve Hipotez Testi:** Olasılık, bir hipotezin doğruluğunu test etmek veya gelecekteki olayları tahmin etmek için kullanılır.
* **Regresyon Analizi:** Olasılık, veriler arasındaki ilişkileri incelemek ve tahmin yapmak için kullanılır.
* **Monte Carlo Yöntemleri:** Olasılık, karmaşık problemlerin çözümünde, rastgele örneklemelerle sayısal çözümler elde etmek için de kullanılır.

### Olasılığın Uygulama Alanları:

1. **Sigorta ve Finans:** Olasılık, sigorta hesaplamaları, risk yönetimi ve yatırım stratejileri için kullanılır.
2. **Fizik ve Mühendislik:** Olasılık, **sistem teorisi**, **istatiksel mekanik**, **sinyal işleme** ve \*\*


gürültü analizinde\*\* kullanılır.
3\. **Yapay Zeka ve Makine Öğrenmesi:** Olasılık, **bayesyen ağlar**, **Markov zincirleri**, **gizli Markov modelleri** ve **doğal dil işleme** gibi alanlarda önemli bir rol oynar.
4\. **Biyoloji ve Tıp:** Olasılık, **epidemiyolojik modelleme**, genetik analizler ve **aşı geliştirme** gibi konularda kullanılır.

### Sonuç:

Olasılık teorisi, rastgele olayların ve belirsizliğin matematiksel bir çerçevede incelenmesiyle ilgilidir. Bu teori, günlük yaşamda karşılaşılan birçok rastgele durumu anlamamıza yardımcı olur ve çok geniş bir uygulama yelpazesinde kullanılır.
