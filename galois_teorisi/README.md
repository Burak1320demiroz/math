# Galois Teorisi

**Galois teorisi**, soyut cebir ve grup teorisi ile bağlantılı bir alandır ve özellikle denklemlerin çözülebilirliği ve köklerinin simetrileri hakkında derin sonuçlar sağlar. Adını **Évariste Galois**’tan alır ve 19. yüzyılın başlarında geliştirilmiştir. Galois teorisi, polinom denklemlerinin kökleri arasındaki ilişkileri anlamamıza yardımcı olur ve cebirsel denklemlerin çözülebilirliği ile ilgilenir.

Galois teorisinin temel amacı, bir polinomun köklerinin belirli bir grup içindeki simetrik yapılarını incelemektir. Bu, polinomların çözülebilirlik koşullarını, özellikle çözümün **elemanlarının radikal (karekök, küpbölünme vb.) formunda** bulunup bulunamayacağını belirler.

### Temel Kavramlar:

1. **Cebirsel Kapanış (Algebraic Closure):**

   * Bir vektör uzayında bir polinomun köklerini içeren bir uzay **algebraik kapanış** sağlar. Örneğin, reel sayılar üzerinde tanımlanan bir polinom, karmaşık sayılar üzerinde çözülür. **Cebirsel kapanış**, bütün cebirsel denklemlerin köklerini içeren en küçük gövdeyi ifade eder.
   * **Örnek:** Gerçek sayılar (ℝ) algebraik olarak kapanmış değildir, çünkü reel sayılarda, örneğin $x^2 + 1 = 0$ denkleminin çözümü yoktur. Bu denklemi karmaşık sayılar ($\mathbb{C}$) çözebilir.

2. **Galois Grubu:**

   * **Galois grubu**, bir polinomun kökleri üzerindeki **özdeşliklerin simetrilerini** belirten bir grup yapısıdır. Bir polinomun kökleri arasındaki bir dönüşüm, bu köklerin birbirlerine nasıl dönüştüğünü tanımlar.
   * Galois grubunun elemanları, polinomun köklerini birbirine dönüştüren **otomorfizm** (özdeşlik) fonksiyonlarıdır.
   * **Örnek:** $f(x) = x^2 - 2$ polinomu için Galois grubu, $\sqrt{2}$ ile $-\sqrt{2}$ arasındaki simetrik dönüşümleri içerir.

3. **Kökleme ve Çözülme:**

   * Galois teorisi, bir polinomun köklerinin, **radikal çözüm** ile çözülebilip çözülemeyeceğini belirler. Bir polinom **radikal çözüm** ile çözülebiliyorsa, bu, köklerinin belirli bir grup yapısına sahip olduğu anlamına gelir.
   * **Küp denklem**, genellikle klasik çözümlerle çözülmesi imkansız olan denklemlerle ilgilidir. Galois teorisi, bu tür denklemlerin çözülebilirliğini ve köklerinin yapısını anlamamıza yardımcı olur.

4. **Field Extensions (Alan Uzantıları):**

   * Bir polinomun köklerini bulduğumuzda, genellikle polinomun köklerini içeren bir **alan uzantısı** oluştururuz. Örneğin, $x^2 - 2 = 0$ denkleminin kökleri $\pm \sqrt{2}$ olduğunda, bu kökleri içeren bir alan, **$\mathbb{Q}(\sqrt{2})$** şeklinde tanımlanır, burada **$\mathbb{Q}$**, rasyonel sayılar kümesidir.
   * Galois teorisi, alan uzantılarındaki **otomorfizmlerin** nasıl çalıştığını ve bu uzantıların Galois gruplarıyla nasıl bağlantılı olduğunu inceler.

5. **Kökenin Çözülmesi ve Grubun Yapısı:**

   * Bir polinomun köklerinin çözülmesi, kökler arasındaki simetrik ilişkilerin, Galois grubunun yapısıyla yakından ilişkilidir. Eğer polinom, **radikal olarak çözülebiliyorsa**, bu, onun Galois grubunun belirli özelliklere sahip olduğu anlamına gelir.
   * **Galois grubu**, genellikle **abel grubu** ya da **sönük grup** olabilir ve bu da polinomun çözülebilirliğine dair önemli bilgi sağlar.

### Galois Teorisinin Temel Sonuçları:

1. **Ekvivalans ve Kökler Arasındaki Simetri:**

   * Galois teorisi, bir polinomun köklerinin, belirli bir grup yapısına sahip olan simetrik bir yapı içerdiğini belirtir. Bu, **rasyonel kökler** ve **radikal çözümler** arasındaki ilişkiyi anlamamıza olanak tanır.

2. **Çözülme ve Galois Grubu:**

   * Eğer bir polinomun Galois grubu **abel** (komütatif) bir grup ise, polinomun kökleri **radikal olarak** çözülebilir. Eğer Galois grubu **non-abel** (komütatif olmayan) bir grup ise, polinomun kökleri **radikal olarak çözülemez**. Örneğin, **5. dereceden bir denklemin çözülemezliği** Galois grubunun yapısıyla ilişkilidir.

3. **İçsel ve Dışsal Yapılar:**

   * Galois teorisi, denklemler üzerinde yapılan dönüşümlerin, genellikle **dışsal (grup teorisi)** ve **içsel (alan teorisi)** yapılarla nasıl ilişkilendirilebileceğini gösterir. Bu, cebirsel denklemlerle çalışma açısından çok güçlü bir yöntem sunar.

4. **Karmaşık Köklerin Çözülebilirliği:**

   * **Dördüncü derece ve daha yüksek dereceden denklemlerin çözülebilirliği**, Galois teorisi ile incelenebilir. Galois grubu yapısı, bu denklemlerin **radikal çözümle çözülemeyeceğini** gösterir.

5. **Kökenlerin ve Alan Uzantılarının İncelenmesi:**

   * Galois teorisi, bir polinomun köklerinin oluşturduğu **alan uzantıları** üzerinde çalışan önemli bir araçtır. Bu uzantıların yapıları ve otomorfizmleri, polinomların köklerinin çözülebilirliğini belirler.

### Örnek: 5. Dereceden Denklemlerin Çözülemezliği

Galois teorisi, **5. dereceden ve daha yüksek dereceden cebirsel denklemlerin** genel çözümünün **radikal bir formda** bulunamayacağını gösteren çok önemli bir sonuca sahiptir. Bu, **Abel-Ruffini teoremi** olarak bilinir ve Galois teorisinin temel sonuçlarından biridir. Bu teorem, 5. dereceden ve daha yüksek dereceli cebirsel denklemler için radikal bir çözüm bulunamayacağını ifade eder. Bunun nedeni, bu denklemlerin Galois grubunun **sönük (non-abel)** bir grup olmasıdır.

### Galois Teorisinin Uygulama Alanları:

* **Cebirsel Denklemler:** Polinomların köklerinin bulunabilirliğini analiz etmek.
* **Şifreleme Teorisi:** **Cebirsel yapılar** ve **gizli anahtarlar** kullanılarak güvenli iletişim sağlanabilir.
* **Kökler ve Alan Uzantıları:** Modern matematik ve fizik problemlerinde köklerin ve alan uzantılarının anlaşılması için kullanılır.
* **Kriptografi:** **RSA şifreleme** gibi sistemlerde, cebirsel denklemlerin çözümleri ve simetrik yapılarla güvenlik sağlanır.

### Özet:

Galois teorisi, cebirsel denklemlerin çözülebilirliği ile ilgili çok güçlü bir teoridir. Bu teori, bir polinomun köklerinin ve bunlar arasındaki simetrik yapıların analizini yaparak, polinomların radikal olarak çözülebilirliğini belirler. Ayrıca, Galois gruplarının yapısı, daha yüksek dereceden denklemlerin çözümünün imkansız olup olmadığını anlamamıza yardımcı olur.
