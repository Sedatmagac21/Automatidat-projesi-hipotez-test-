# 🚕 New York City TLC Verileri: Ücret Tahmini ve İstatistiksel Analiz

### 📌 Giriş

[cite_start]Bu proje, New York City Taksi ve Limuzin Komisyonu (TLC) verilerini analiz ederek, taksi ücretlerini etkileyen temel faktörleri belirlemeyi ve bu faktörler arasındaki ilişkileri istatistiksel hipotez testleri ile doğrulamayı amaçlamaktadır[cite: 14]. [cite_start]Temel amaç, her yolculuktan önce ücretleri tahmin edebilen veri odaklı içgörüler üretmektir[cite: 41].

[cite_start]Proje, özellikle ödeme türünün toplam ücret üzerindeki etkisini inceleyen bir A/B testi dahil olmak üzere hipotez testleri kullanarak [cite: 45, 43][cite_start], taksi şoförleri için **daha fazla gelir elde etmenin yollarını bulmaya** odaklanmıştır[cite: 42].

### 🎯 Projenin Amacı ve Araştırma Sorusu

Bu çalışmanın temel amaçları ve araştırma soruları şunlardır:

* [cite_start]**Temel Amaç:** TLC verilerini analiz ederek taksi ücretlerini etkileyen faktörleri belirlemek ve hipotez testleriyle veri odaklı içgörüler elde etmektir[cite: 14].
* [cite_start]**Araştırma Sorusu:** Taksi ücretlerini etkileyen faktörler nelerdir ve bu faktörler arasında istatistiksel olarak anlamlı bir ilişki var mıdır?[cite: 16].
* **Hedefler:**
    * [cite_start]Tanımlayıcı istatistikleri hesaplamak[cite: 6].
    * [cite_start]Bir hipotez testi yapmak[cite: 7].
    * [cite_start]Harici paydaşlar için bir yönetici özeti oluşturmak[cite: 8].

### 🧪 İstatistiksel Arka Plan

#### 1. Hipotez Testi (Ödeme Türü ve Ücret İlişkisi)

[cite_start]Projenin kritik bir bölümü, toplam ücret tutarı ile ödeme türü arasındaki ilişkiyi incelemek ve kredi kartıyla ödeme yapan müşterilerin nakit ödeme yapanlara göre daha fazla toplam ücret ödeme eğiliminde olup olmadığını keşfetmekti[cite: 44].

* [cite_start]**Uygulanan Test:** Kredi kartı kullanan müşteriler ile nakit kullanan müşteriler arasında ortalama toplam ücrette istatistiksel olarak anlamlı bir fark olup olmadığını belirlemek için **iki örneklemli t-testi** uygulandı[cite: 52].
* [cite_start]**Sıfır Hipotezi ($H_0$):** Taksi ücretleri, yolculuk süresinden bağımsızdır[cite: 30].
* [cite_start]**Alternatif Hipotez ($H_1$):** Taksi ücretleri, yolculuk süresiyle anlamlı bir ilişkiye sahiptir[cite: 31].

#### 2. Tanımlayıcı İstatistikler

[cite_start]Tanımlayıcı istatistikler, veriyi özetleyerek eğilimleri, dağılımları ve aykırı değerleri hızlıca görmeyi sağlayarak analiz için temel bir anlayış oluşturmuştur[cite: 24]. [cite_start]Bu istatistikler; ortalama, medyan ve varyans gibi değerleri göstererek değişkenlerin genel eğilimlerini anlamayı sağlamıştır[cite: 26].

### 🔁 Proje Akışı ve Yöntemi (PACE Çerçevesi)

[cite_start]Proje, aşağıdaki dört görev ve PACE (Plan, Analyze, Construct, Execute) strateji aşamaları kullanılarak yürütülmüştür[cite: 10]:

| Görev | PACE Aşaması | Odak Noktası |
| :--- | :--- | :--- |
| **Task 1** | Plan (Planlama) | [cite_start]İçe aktarmalar ve veri yükleme[cite: 10]. |
| **Task 2** | Analyze (Analiz) | [cite_start]Veri keşfi[cite: 10]. [cite_start]Rastgele örneklemenin önemi ve yanlılık hususları ele alındı[cite: 17, 19]. |
| **Task 3** | Construct (Oluşturma) | [cite_start]İstatistiksel testlerin yapılması[cite: 10]. [cite_start]Sıfır ve alternatif hipotezler formüle edildi[cite: 29]. |
| **Task 4** | Execute (Uygulama) | [cite_start]İçgörülerin paydaşlarla paylaşılması ve yönetici özetinin oluşturulması[cite: 10, 8]. |

![Proje Akışı Görevler](https://i.imgur.com/example-of-project-flow.png)

### ✅ Anahtar Bulgular ve Öneriler

#### A/B Testi Sonuçları

* [cite_start]Kredi kartı kullanan müşteriler ile nakit kullanan müşteriler arasında ortalama toplam ücrette **istatistiksel olarak anlamlı bir fark** vardır[cite: 54].
* [cite_start]Kredi kartı kullanan müşteriler, nakite kıyasla **daha yüksek bir toplam tutar** gösterdi[cite: 55].
* [cite_start]**Temel İş Anlayışı:** Müşterileri kredi kartlarıyla ödeme yapmaya teşvik etmenin taksi şoförleri için **muhtemelen daha fazla gelir yaratacağıdır**[cite: 46].

#### Öneriler

Elde edilen sonuçlara dayanarak, ücret yapısının optimize edilmesi ve gelirin artırılması için aşağıdaki öneriler sunulmuştur:

1.  [cite_start]**Kredi Kartı Teşviki:** TLC'nin müşterileri kredi kartlarıyla ödeme yapmaya teşvik etmesi ve kredi kartı ödemelerini teşvik etmek için stratejiler oluşturması önerilmektedir[cite: 56].
2.  [cite_start]**Uygulama Stratejileri:** Taksilere "Kredi kartı ödemeleri tercih edilir" yazan tabelalar yerleştirmek ve şoförlerin müşterilere bu tercihi sözlü olarak bildirmelerini gerektiren bir protokol uygulanması[cite: 57].
3.  [cite_start]**Model Optimizasyonu:** Taksi ücretlerini daha doğru tahmin edebilmek için yolculuk süresi ve diğer faktörleri dikkate alacak bir model önerilmektedir[cite: 38].

### 🛠️ Kullanılan Teknolojiler

* **Diller:** Python
* **Ortam:** Jupyter Notebook
* **Kütüphaneler:** NumPy, Pandas, SciPy (veya istatistiksel analiz için kullanılan kütüphaneler)

### 🚀 Çalıştırma

Gerekli kütüphaneler:

pip install numpy scipy

### Unit testleri çalıştırmak için:

python w4_unittest.py
