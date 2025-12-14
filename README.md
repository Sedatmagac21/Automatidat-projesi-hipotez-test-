# 🚕 New York City TLC Projesi: Ücret Tahmini, İstatistiksel İnceleme ve A/B Testi

![Proje Akışı Görevler](https://i.imgur.com/example-of-project-flow.png)

### 📌 Giriş

[cite_start]Bu proje, New York City Taksi ve Limuzin Komisyonu (TLC) verilerini analiz ederek, taksi ücretlerini etkileyen faktörleri derinlemesine incelemektedir[cite: 14]. [cite_start]Projenin temel amacı, her yolculuktan önce taksi ücretlerini tahmin etmek ve taksi şoförleri için **daha fazla gelir elde etmenin yollarını bulmaktır**[cite: 41, 42].

[cite_start]Bu çalışma, veri odaklı içgörüler sağlamak amacıyla tanımlayıcı istatistikleri ve hipotez testlerini (özellikle ödeme türünün toplam ücret üzerindeki etkisini inceleyen bir A/B testi) kapsamaktadır[cite: 6, 7].

### 🎯 Projenin Amacı ve Araştırma Sorusu

[cite_start]Bu projenin temel hedefleri şunlardır[cite: 3, 4, 5, 6, 7, 8]:

* [cite_start]Ders 4 PACE strateji belgesindeki soruları tamamlamak[cite: 4].
* [cite_start]Jupyter Notebook proje dosyasındaki soruları yanıtlamak[cite: 5].
* [cite_start]Tanımlayıcı istatistikleri hesaplamak[cite: 6].
* [cite_start]Bir hipotez testi yapmak[cite: 7].
* [cite_start]Harici paydaşlar için bir yönetici özeti oluşturmak[cite: 8].

**Araştırma Sorusu:**
[cite_start]Taksi ücretlerini etkileyen faktörler nelerdir ve bu faktörler arasında istatistiksel olarak anlamlı bir ilişki var mıdır? [cite: 16]

### 🧪 İstatistiksel Metodoloji

[cite_start]Projenin istatistiksel kısmı, toplam ücret tutarı ile ödeme türü arasındaki ilişkiye odaklanmıştır[cite: 43].

#### A/B Testi Uygulaması

[cite_start]Automatidata ekibi, kredi kartı ödemesi ile toplam ücret tutarı arasındaki ilişkiyi analiz etmek için bir A/B testi yürüttü[cite: 45].

1.  [cite_start]**Örnekleme:** Müşteriler rastgele seçilip iki gruba ayrıldı (Kredi kartı/Nakit)[cite: 48, 49, 50]. [cite_start]Rastgele örnekleme, verinin tüm popülasyonu temsil etmesini ve önyargıyı azaltmasını sağladı[cite: 18].
2.  [cite_start]**Tanımlayıcı İstatistikler:** Her ödeme yöntemi için ortalama toplam ücret tutarını daha iyi anlamak amacıyla tanımlayıcı istatistikler hesaplandı[cite: 51].
3.  [cite_start]**Hipotez Testi:** Kredi kartı kullanan müşteriler ile nakit kullanan müşteriler arasında ortalama toplam ücrette istatistiksel olarak anlamlı bir fark olup olmadığını belirlemek için **iki örneklemli $t$-testi** uygulandı[cite: 52].
    * [cite_start]**Sıfır Hipotezi ($H_0$):** Fark veya ilişkinin olmadığını savunur[cite: 28].
    * **Alternatif Hipotez ($H_1$):** Bir fark veya ilişkinin olduğunu iddia eder[cite: 28].

#### Rastgele Örnekleme Yanlılığı

Projede, rastgele örnekleme kullanılmadığında ortaya çıkabilecek örnekleme yanlılığına dikkat çekilmiştir. [cite_start]Örneğin, sadece yoğun saatlerde yapılan yolculukları analiz etmek, tüm günün yolculuklarını temsil etmediği için ücretlerin olduğundan daha yüksek görünmesine neden olabilir[cite: 20, 21].

### 🔁 Proje Akışı (Görevi)

[cite_start]Proje, dört görev üzerinden yürütülmüştür ve PACE aşamaları bu görevlere dahildir[cite: 10]:

* **Task 1:** Imports & data loading (Veri yükleme) [cite: 10]
* [cite_start]**Task 2:** Data exploration (Veri keşfi) [cite: 10]
* [cite_start]**Task 3:** Statistical test(s) (İstatistiksel testler) [cite: 10]
* **Task 4:** Communicate insights with stakeholders (Paydaşlarla içgörülerin iletişimini sağlama) [cite: 10]

### ✅ Anahtar Bulgular ve Öneriler

#### A/B Testi Sonuçları

* [cite_start]Kredi kartı kullanan müşteriler ile nakit kullanan müşteriler arasında ortalama toplam ücrette **istatistiksel olarak anlamlı bir fark** vardır[cite: 54].
* [cite_start]Kredi kartı kullanan müşteriler nakite kıyasla daha yüksek bir toplam tutar gösterdi[cite: 55].
* **Temel İş Anlayışı:** Müşterileri kredi kartlarıyla ödeme yapmaya teşvik etmek, taksi şoförleri için **muhtemelen daha fazla gelir yaratacağıdır**[cite: 46].

#### Yönetici Özeti Önerileri

Sonuçlara dayanarak, Automatidata veri ekibi aşağıdaki önerilerde bulunmaktadır[cite: 56, 57]:

1.  **Kredi Kartı Teşviki:** New York City TLC'nin müşterileri kredi kartlarıyla ödeme yapmaya teşvik etmesi ve kredi kartı ödemelerini teşvik etmek için stratejiler oluşturması[cite: 56].
2.  **Uygulama Stratejileri:** Taksilere "Kredi kartı ödemeleri tercih edilir" yazan tabelalar yerleştirmek ve taksi şoförlerinin müşterilere kredi kartı ödemelerinin tercih edildiğini sözlü olarak bildirmelerini gerektiren bir protokol uygulamak[cite: 57].
3.  **Model Geliştirme:** Taksi ücretlerini daha doğru tahmin edebilmek için yolculuk süresi ve diğer faktörleri dikkate alacak bir model önerilmesi[cite: 38].

### 🛠️ Kullanılan Teknolojiler

* **Diller:** Python (Varsayılmıştır)
* **Ortam:** Jupyter Notebook (Analiz ve hesaplamalar için) [cite: 5]
* **Kütüphaneler:** NumPy, Pandas, SciPy (İstatistiksel testler için) (Varsayılmıştır)

### 🚀 Çalıştırma

Tüm istatistiksel analiz ve hesaplamaların yer aldığı Jupyter Notebook dosyasını (örneğin `C3W4_Assignment.ipynb`) inceleyerek projenin adımlarını takip edebilirsiniz.

```bash
# Gerekli kütüphaneleri yükleyin (Örnek)
pip install pandas numpy scipy

# Jupyter Notebook'u başlatın
jupyter notebook
