# Urban Green Space and Mental Health Analysis

Bu proje, kentsel yeşil alanlara erişim ve yaşam tarzı değişkenleri kullanılarak bireylerin ruh sağlığı durumunu analiz etmek için hazırlanmıştır. Projede veri analizi, eksik veri inceleme, görselleştirme, özellik seçimi ve makine öğrenmesi modelleri yer almaktadır.

## Proje Amacı

Bu çalışmanın amacı, anket verilerinden yararlanarak bireylerin ruh sağlığı durumunu tahmin edebilecek sınıflandırma modelleri geliştirmek ve bu modellerin başarılarını karşılaştırmaktır. Projede özellikle kentsel yeşil alan erişimi, fiziksel aktivite, stres ve mutluluk gibi değişkenlerin ruh sağlığı üzerindeki etkisi incelenmektedir.

## Kullanılan Teknolojiler

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn
* Missingno

## Proje İçeriği

* Veri setinin okunması ve incelenmesi
* Eksik veri analizi
* Sayısal ve kategorik değişkenlerin ayrılması
* Aykırı değer analizi
* Normal dağılım testi
* Korelasyon analizi
* Veri ön işleme
* Özellik seçimi
* PCA ile boyut indirgeme
* Makine öğrenmesi modellerinin kurulması
* Model başarılarının karşılaştırılması
* Confusion Matrix ve ROC eğrisi analizi

## Kullanılan Modeller

Projede farklı sınıflandırma modelleri kullanılarak performans karşılaştırması yapılmıştır.

* K-Nearest Neighbors
* Random Forest
* Gaussian Naive Bayes

Modeller, çapraz doğrulama ve hiperparametre optimizasyonu ile değerlendirilmiştir. En başarılı model, test verisi üzerinde ayrıca analiz edilmiştir.

## Dosya Yapısı

```txt
urban-green-space-mental-health-analysis/
│
├── urban_green_space_mental_health.ipynb
├── README.md
```

## Çalışma Mantığı

Proje, veri setini okuyarak ilk olarak genel veri incelemesi yapar. Ardından eksik veriler, aykırı değerler ve değişkenler arasındaki ilişkiler analiz edilir. Modelleme aşamasında hedef değişken olarak ruh sağlığı durumu kullanılır. Veriler ön işleme adımlarından geçirildikten sonra farklı makine öğrenmesi modelleri eğitilir ve performansları karşılaştırılır.

## Değerlendirme Metrikleri

Model performansını ölçmek için aşağıdaki metrikler kullanılmıştır:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

## Geliştirilebilir Özellikler

* Daha büyük veri setleriyle model başarısı artırılabilir.
* Farklı makine öğrenmesi algoritmaları eklenebilir.
* Model sonuçları web arayüzüyle sunulabilir.
* Özellik önemleri daha detaylı yorumlanabilir.
* Tahmin sistemi gerçek zamanlı kullanılabilecek hale getirilebilir.

## Lisans

Bu proje eğitim ve veri analizi çalışmaları için hazırlanmıştır.
