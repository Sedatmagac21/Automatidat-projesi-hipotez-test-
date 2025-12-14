# 🚕 New York City TLC Projesi: Ücret Tahmini, İstatistiksel İnceleme ve A/B Testi

### 📌 Giriş

Bu proje, New York City Taksi ve Limuzin Komisyonu (TLC) verilerini analiz ederek, taksi ücretlerini etkileyen faktörleri derinlemesine incelemektedir. Projenin temel amacı, her yolculuktan önce taksi ücretlerini tahmin etmek ve taksi şoförleri için **daha fazla gelir elde etmenin yollarını bulmaktır**.

Bu çalışma, veri odaklı içgörüler sağlamak amacıyla tanımlayıcı istatistikleri ve hipotez testlerini (özellikle ödeme türünün toplam ücret üzerindeki etkisini inceleyen bir A/B testi) kapsamaktadır.

### 🎯 Projenin Amacı ve Araştırma Sorusu

Bu projenin temel hedefleri şunlardır:

* Ders 4 PACE strateji belgesindeki soruları tamamlamak.
* Jupyter Notebook proje dosyasındaki soruları yanıtlamak.
* Tanımlayıcı istatistikleri hesaplamak.
* Bir hipotez testi yapmak.
* Harici paydaşlar için bir yönetici özeti oluşturmak.

**Araştırma Sorusu:**
Taksi ücretlerini etkileyen faktörler nelerdir ve bu faktörler arasında istatistiksel olarak anlamlı bir ilişki var mıdır?

### 🧪 İstatistiksel Metodoloji

Projenin istatistiksel kısmı, toplam ücret tutarı ile ödeme türü arasındaki ilişkiye odaklanmıştır.

#### A/B Testi Uygulaması

Automatidata ekibi, kredi kartı ödemesi ile toplam ücret tutarı arasındaki ilişkiyi analiz etmek için bir A/B testi yürüttü.

1.  **Örnekleme:** Müşteriler rastgele seçilip iki gruba ayrıldı (Kredi kartı/Nakit). Rastgele örnekleme, verinin tüm popülasyonu temsil etmesini ve önyargıyı azaltmasını sağladı.
2.  **Tanımlayıcı İstatistikler:** Her ödeme yöntemi için ortalama toplam ücret tutarını daha iyi anlamak amacıyla tanımlayıcı istatistikler hesaplandı.
3.  **Hipotez Testi:** Kredi kartı kullanan müşteriler ile nakit kullanan müşteriler arasında ortalama toplam ücrette istatistiksel olarak anlamlı bir fark olup olmadığını belirlemek için **iki örneklemli $t$-testi** uygulandı.
    * **Sıfır Hipotezi ($H_0$):** Fark veya ilişkinin olmadığını savunur.
    * **Alternatif Hipotez ($H_1$):** Bir fark veya ilişkinin olduğunu iddia eder.

#### Rastgele Örnekleme Yanlılığı

Projede, rastgele örnekleme kullanılmadığında ortaya çıkabilecek örnekleme yanlılığına dikkat çekilmiştir. Örneğin, sadece yoğun saatlerde yapılan yolculukları analiz etmek, tüm günün yolculuklarını temsil etmediği için ücretlerin olduğundan daha yüksek görünmesine neden olabilir.

### 🔁 Proje Akışı (Görevi)

Proje, dört görev üzerinden yürütülmüştür ve PACE aşamaları bu görevlere dahildir:

* **Task 1:** Imports & data loading (Veri yükleme)
* **Task 2:** Data exploration (Veri keşfi)
* **Task 3:** Statistical test(s) (İstatistiksel testler)
* **Task 4:** Communicate insights with stakeholders (Paydaşlarla içgörülerin iletişimini sağlama)

### ✅ Anahtar Bulgular ve Öneriler

#### A/B Testi Sonuçları

* Kredi kartı kullanan müşteriler ile nakit kullanan müşteriler arasında ortalama toplam ücrette **istatistiksel olarak anlamlı bir fark** vardır.
* Kredi kartı kullanan müşteriler nakite kıyasla daha yüksek bir toplam tutar gösterdi.
* **Temel İş Anlayışı:** Müşterileri kredi kartlarıyla ödeme yapmaya teşvik etmek, taksi şoförleri için **muhtemelen daha fazla gelir yaratacağıdır**.

#### Yönetici Özeti Önerileri

Sonuçlara dayanarak, Automatidata veri ekibi aşağıdaki önerilerde bulunmaktadır:

1.  **Kredi Kartı Teşviki:** New York City TLC'nin müşterileri kredi kartlarıyla ödeme yapmaya teşvik etmesi ve kredi kartı ödemelerini teşvik etmek için stratejiler oluşturması.
2.  **Uygulama Stratejileri:** Taksilere "Kredi kartı ödemeleri tercih edilir" yazan tabelalar yerleştirmek ve taksi şoförlerinin müşterilere kredi kartı ödemelerinin tercih edildiğini sözlü olarak bildirmelerini gerektiren bir protokol uygulamak.
3.  **Model Geliştirme:** Taksi ücretlerini daha doğru tahmin edebilmek için yolculuk süresi ve diğer faktörleri dikkate alacak bir model önerilmesi.

### 🛠️ Kullanılan Teknolojiler

* **Diller:** Python (Varsayılmıştır)
* **Ortam:** Jupyter Notebook (Analiz ve hesaplamalar için)
* **Kütüphaneler:** NumPy, Pandas, SciPy (İstatistiksel testler için) (Varsayılmıştır)

### 🚀 Çalıştırma

Tüm istatistiksel analiz ve hesaplamaların yer aldığı Jupyter Notebook dosyasını (örneğin `C3W4_Assignment.ipynb`) inceleyerek projenin adımlarını takip edebilirsiniz.

```bash
# Gerekli kütüphaneleri yükleyin (Örnek)
pip install pandas numpy scipy

# Jupyter Notebook'u başlatın
jupyter notebook
