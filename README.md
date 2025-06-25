# Sleep Health & Lifestyle - Machine Learning Project  
**Uyku Sağlığı ve Yaşam Tarzı - Makine Öğrenmesi Projesi**

This machine learning project uses the **Sleep Health and Lifestyle** dataset from Kaggle to explore the relationship between lifestyle factors and sleep disorders. It aims to analyze health patterns and predict the presence of sleep disorders.

Bu makine öğrenmesi projesi, Kaggle'dan alınan **Uyku Sağlığı ve Yaşam Tarzı** veri seti ile yaşam tarzı faktörleri ile uyku bozuklukları arasındaki ilişkiyi inceler. Sağlık örüntülerini analiz etmeyi ve uyku bozukluklarını tahmin etmeyi amaçlar.

---

## 📁 Dataset

- **Source / Kaynak**: [Kaggle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)
- **Number of Records / Kayıt Sayısı**: 374
- **Features / Özellikler**:  
  `Age`, `Gender`, `Occupation`, `Sleep Duration`, `Physical Activity Level`, `Stress Level`, `Heart Rate`, `Blood Pressure`, `BMI Category`, `Sleep Disorder` (Target)

---

## 🎯 Project Objectives / Proje Amaçları

- Analyze the correlation between lifestyle factors and sleep disorders  
- Classify types of sleep disorders  
- Visualize health behaviors and physiological metrics  

- Yaşam tarzı faktörleri ile uyku bozuklukları arasındaki ilişkiyi analiz etmek  
- Uyku bozukluğu türlerini sınıflandırmak  
- Sağlık davranışlarını ve fizyolojik metrikleri görselleştirmek

---

## ⚙️ Methods Used / Kullanılan Yöntemler

- Data Cleaning and Preprocessing: Label Encoding, Scaling  
- Feature Engineering: Extracting systolic/diastolic values from Blood Pressure  
- Classification Models:  
  - Decision Tree  
  - Random Forest  
  - Support Vector Machine (SVM)  
- Model Evaluation Metrics: Accuracy, Precision, Recall, F1-Score  

- Veri Temizleme ve Ön İşleme: Etiketleme (Label Encoding), Ölçekleme  
- Özellik Mühendisliği: Kan basıncının sistolik/diastolik olarak ayrılması  
- Sınıflandırma Modelleri:  
  - Karar Ağacı  
  - Rastgele Orman  
  - Destek Vektör Makineleri (SVM)  
- Değerlendirme Metrikleri: Doğruluk, Kesinlik, Duyarlılık, F1 Skoru

---

## 📊 Visualizations / Görselleştirmeler

- Correlation Heatmap  
- Sleep Duration by Gender  
- Stress Level by Sleep Disorder  
- Sleep Duration Distribution  
- Physical Activity vs. Sleep Duration  

- Korelasyon Isı Haritası  
- Cinsiyete Göre Uyku Süresi  
- Uyku Bozukluğuna Göre Stres Seviyesi  
- Uyku Süresi Dağılımı  
- Fiziksel Aktivite ile Uyku Süresi Arasındaki İlişki

---

## 📈 Model Performance / Model Performansı

| Model                         | Accuracy | Precision | Recall | F1-Score |
|------------------------------|----------|-----------|--------|----------|
| Decision Tree / Karar Ağacı  | 0.91     | 0.89      | 0.85   | 0.87     |
| Random Forest / Rastgele Orman | 0.88   | 0.84      | 0.83   | 0.83     |
| SVM                           | 0.64     | 0.64      | 0.44   | 0.42     |

---

## 📌 Notes / Notlar

- This project was conducted on a small dataset, so results may not generalize well to larger populations.  
- Bu proje küçük boyutlu bir veri seti ile gerçekleştirildiği için, sonuçlar geniş popülasyonlara genellenemez.

- Further improvements can be made by tuning hyperparameters and using cross-validation.  
- Model iyileştirmeleri hiperparametre ayarlamaları ve çapraz doğrulama ile yapılabilir.

---



