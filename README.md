# Pima Indians Diabetes – Machine Learning Project

Bu proje, Pima Indians Diabetes veri seti kullanılarak makine öğrenmesi yöntemleriyle diyabet tahmini yapılmasını amaçlamaktadır. Çalışma, keşifçi veri analizi (EDA), doğrusal ilişki incelemesi ve çeşitli sınıflandırma modellerinin karşılaştırılmasını içermektedir.

## Kullanılan Veri Seti
- **Veri Seti Adı:** Pima Indians Diabetes Dataset  
- **Kaynak:** Kaggle  
- **Gözlem Sayısı:** 768  
- **Değişken Sayısı:** 9  
- **Hedef Değişken:** Outcome (0: Diyabet yok, 1: Diyabet var)

## Proje İçeriği
Bu repository aşağıdaki dosyalardan oluşmaktadır:

- **analysis.ipynb:**  
  Veri seti üzerinde yapılan tüm analizleri, grafikleri, model kurulumlarını ve yorumları içeren Jupyter Notebook dosyası.
  
- **Proje_Raporu.pdf:**  
  Koddan bağımsız olarak akademik bir dille yazılmış proje raporu. Problem tanımı, yöntem, bulgular ve sonuç bölümlerini içermektedir.
  
- **requirements.txt:**  
  Projede kullanılan Python kütüphanelerinin listesi.

## Yapılan Analizler

### 1. Keşifçi Veri Analizi (EDA) ve Lineer Regresyon
- Eksik veri ve aykırı değer analizi
- Histogram, boxplot ve korelasyon heatmap görselleştirmeleri
- BMI ve Glucose değişkenleri arasındaki ilişkinin Linear Regression ile incelenmesi
- R² skoru ve regresyon doğrusunun çizilmesi

### 2. Sınıflandırma Modelleri
Diyabet tahmini için aşağıdaki modeller kurulmuş ve karşılaştırılmıştır:
- Logistic Regression
- K-Nearest Neighbors (en iyi k değeri döngü ile belirlenmiştir)
- Support Vector Machines (SVM)
- Decision Tree

### Değerlendirme Metrikleri
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Nasıl Çalıştırılır?

1. Repository’i klonlayın:
```bash
git clone https://github.com/kullanici_adi/repo_adi.git
