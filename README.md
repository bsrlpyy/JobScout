# Gerçek / Sahte İş İlanı Tahmini 👩‍💻⛳

## Açıklama
Bu proje, iş tanımlarının sahte olup olmadığını tahmin etmek amacıyla geliştirilmiş bir makine öğrenmesi modelini içerir. Veri seti, yaklaşık 800 sahte iş tanımı ve toplamda 18 bin iş tanımı içermektedir.

## 🔗 Görev
Elimizdeki veri seti üzerinden minimum hata ile iş ilanının gerçek mi sahte mi olduğunu tahmin eden bir makine öğrenmesi modeli geliştireceğiz.

### 🎯 Değişkenler

- job_id: İş tanımı için benzersiz bir kimlik
- title: İş unvanı
- location: İşin konumu
- department: İşin ait olduğu departman
- salary_range: Maaş aralığı
- company_profile: Şirket profili hakkında bilgi
- description: İş tanımı metni
- requirements: İş için gerekli nitelikler
- benefits: İşin sunduğu avantajlar
- telecommuting: Uzaktan çalışma seçeneği
- has_company_logo: Şirket logosunun olup olmadığı
- has_questions: İş tanımında soruların olup olmadığı
- employment_type: Çalışma türü
- required_experience: Gereken deneyim seviyesi
- required_education: Gereken eğitim seviyesi
- industry: İşin ait olduğu sektör
- function: İşin ait olduğu fonksiyon
- fraudulent: İş tanımının sahte olup olmadığı (hedef değişken)

### Veri Setimiz
Veri setimin Kaggle bağlantısı :
[Veri Seti](https://www.kaggle.com/code/busraalpay/jobscout)

##  Kullanılan Algoritmalar ve Teknikler

 ### 🪂 Keşifsel Veri Analizi (EDA - Exploratory Data Analysis)
- Veri setinin özelliklerini ve dağılımını anlamak amacıyla keşifsel veri analizi yapılmıştır.
- Eksik Değer Analizi: Eksik bilgi içeren sütunlar ve bunların hedef değişkenle ilişkisi incelenmiştir.
- Kategorik Değişken Analizi: Kategorik değişkenlerin analizi yapılmıştır.
- Sayısal Değişken Analizi: Sayısal değişkenlerin analizi yapılmıştır.
- Kardinal Değişken Analizi: Kardinal değişkenlerin analizi yapılmıştır.
- Hedef Değişken Analizi: Hedef değişkenin analizi yapılmıştır.

### 📊 Çapraz Tablo Analizi (Crosstab)
Kategorik değişkenler ile hedef değişkenin ilişkisini incelemek için çapraz tablo analizi yapılmıştır.

### 💠 Gözetimli Öğrenme Algoritmaları
- Lojistik Regresyon (Logistic Regression): İş tanımlarını sahte veya gerçek olarak sınıflandırmak için kullanılmıştır.
- Rastgele Orman (Random Forest): Birden fazla karar ağacını birleştirerek daha doğru sınıflandırma sonuçları elde etmek için kullanılmıştır.

### 🚀 Gözetimsiz Öğrenme Algoritmaları
- DBSCAN (Density-Based Spatial Clustering of Applications with Noise): Veriyi yoğunluk bazlı kümelere ayırmak için kullanılmıştır.

### 🌀 Rastgele Arama (Randomized Search)
- Hiperparametre Optimizasyonu: Model performansını artırmak için rastgele arama yöntemiyle hiperparametre optimizasyonu yapılmıştır.

### 🌼 Diğer
- Validation Curve (Doğrulama Eğrisi): Modelin performansını değerlendirmek için doğrulama eğrisi grafiği oluşturulmuştur.
- Karışıklık Matrisi ve Performans Ölçütleri: Model üzerinde karışıklık matrisi ve MAE, MSE gibi performans ölçütleri uygulanmıştır.

## Katkıda Bulunma
Katkıda bulunmak isterseniz, lütfen bir pull request oluşturun.

## İletişim
Sorularınız için  iletişime geçebilirsiniz.

---
