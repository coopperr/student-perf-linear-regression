# 🎓 student-perf-linear-regression

Portuguese **Student Performance** veri seti üzerinde öğrencilerin **final notu (G3)** değerini tahmin etmek için yapılan bir **Lineer Regresyon** projesidir.  
Bu proje, öğrencilerin sosyal, demografik ve akademik değişkenlerinden yola çıkarak **G3 (target)** değerini tahmin etmeyi amaçlar.

---

## 🎯 Amaç

- **Hedef (Target):** `G3` — öğrencinin final notu  
- Öğrenci özellikleri (`G1`, `G2`, `studytime`, `failures`, `absences`, vb.) ile G3 notunu modellemek  
- Basit bir lineer regresyon modeli ile öğrenci başarısı tahmini yapmak  
- Veri ön işleme → Görselleştirme → Modelleme → Metrik değerlendirme adımlarını kapsayan uçtan uca bir akış oluşturmak  

---

## 📊 Veri Künyesi

**Veri seti:** `student-por.csv`  
**Kaynak:** UCI Machine Learning Repository – *Student Performance Data Set*  
**Bağımsız Değişkenler (Features):**
- `school`, `sex`, `age`, `address`, `famsize`, `Pstatus`, `studytime`, `failures`, `schoolsup`, `famsup`, `paid`, `activities`, `higher`, `internet`, `romantic`, `goout`, `health`, `absences`, `G1`, `G2`
  
**Bağımlı Değişken (Target):**
- `G3` → öğrencinin final notu  

---

## ⚙️ Model Bilgisi

- **Model:** `LinearRegression()`  
- **Kütüphane:** `scikit-learn`  
- **Train/Test oranı:** `80/20`  
- **Random State:** `42`  
- **Değerlendirme metrikleri:**  
  - MAE (Mean Absolute Error)  
  - MSE (Mean Squared Error)  
  - RMSE (Root Mean Squared Error)  
  - R² (Determination Coefficient)  
  - MAPE, MedianAE, Explained Variance Score (EVS)

---

## 📁 Proje Yapısı

