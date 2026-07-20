# 🤖 Machine Learning Fundamentals & Applied Projects

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

Bu depo; Regresyon (Regression), Sınıflandırma (Classification), Kümeleme (Clustering), Doğal Dil İşleme (NLP), Boyut İndirgeme (PCA) ve Tavsiye Sistemleri (Recommendation Systems) gibi temel Makine Öğrenmesi konularını modüler bir sırayla ele alan uygulamalı Jupyter Notebook rehberidir.

---

## 📓 Notebook İçerikleri (Sırasıyla)

Depoda yer alan 19 adımlık ders/uygulama notebook'ları ve kapsadıkları temel konular:

1. **`1-Linear_Regression.ipynb`**: Tek değişkenli doğrusal regresyon teorisi, modelin kurulması ve veri üzerindeki regresyon çizgisinin fit edilmesi.
2. **`2-Multiple_Linear_Regression.ipynb`**: Birden fazla bağımsız değişken içeren regresyon problemleri ve katsayıların analiz edilmesi.
3. **`3-Polynomial_Linear_Regression.ipynb`**: Doğrusal olmayan (lineer olmayan) veri kümelerini modellemek için polinom derecelerinin kullanılması.
4. **`4-Decision_Tree_Regression.ipynb`**: Karar ağaçları algoritmasının sürekli değer tahmini (regresyon) için uygulanması.
5. **`5-Random_Forest_Regression.ipynb`**: Çok sayıda karar ağacının birleşimiyle (Ensemble Learning) daha güçlü regresyon modelleri oluşturulması.
6. **`6-Evaluation Regression Models.ipynb`**: Regresyon modellerinin başarımını ölçen metrikler ($R^2$, adjusted $R^2$, MSE, MAE, RMSE) ve modellerin kıyaslanması.
7. **`7-Logistic Regression Models.ipynb`**: İki sınıflı (binary) sınıflandırma problemleri için lojistik regresyon ve sigmoid fonksiyonu uygulaması.
8. **`8-K-Nearest-Neighbour Classification.ipynb`**: Mesafe tabanlı K-En Yakın Komşu (KNN) algoritması ile sınıflandırma.
9. **`9- Support Vector Machine Classification.ipynb`**: Destek Vektör Makineleri (SVM) ve hiper-düzlemler (hyperplanes) ile veri ayrıştırma.
10. **`10- Naive Bayes Classification.ipynb`**: Olasılıksal Bayes teorisine dayalı sınıflandırma yaklaşımı.
11. **`11- Decison Tree Classification.ipynb`**: Karar ağaçlarının sınıflandırma problemlerinde kullanımı ve bilgi kazancı (Information Gain / Gini) konsepti.
12. **`12- Random Forest Classification.ipynb`**: Topluluk öğrenmesi metoduyla sınıflandırma doğruluğunun artırılması.
13. **`13-Evaluation classification Models.ipynb`**: Sınıflandırma modellerinin performans metrikleri (Confusion Matrix, Precision, Recall, F1-Score, ROC/AUC).
14. **`14-K-Means Clustering.ipynb`**: Gözetimsiz öğrenme yöntemlerinden K-Means ile verilerin gruplanması ve Elbow yöntemi.
15. **`15-Hierarchical Clustering.ipynb`**: Hiyerarşik kümeleme analizi ve Dendrogram grafikleri üzerinden küme sayısına karar verme.
16. **`16-Natural_Language_Process(NLP).ipynb`**: Metin temizleme, Stop-words ayıklama, Stemming/Lemmatization ve CountVectorizer/TF-IDF ile metin sınıflandırma.
17. **`17-Principal Component Analysis (PCA).ipynb`**: Yüksek boyutlu verileri temsil yeteneğini kaybetmeden düşük boyutlara indirgeme.
18. **`18-Model_Selection.ipynb`**: K-Fold Cross Validation ve Grid Search / Random Search ile hiperparametre optimizasyonu.
19. **`19-Recommendation Systems.ipynb`**: Kullanıcı veya içerik tabanlı (Content-Based / Collaborative Filtering) öneri sistemlerinin simülasyonu.

---

## 📊 Kullanılan Veri Setleri (Datasets)

Notebook çalışmalarında kullanılan veri setleri repoda `.csv` formatında yer almaktadır:

* **`linear_regression_dataset.csv`**: Tek değişkenli regresyon testleri için deneyim-maaş gibi temel veriler.
* **`multiple_linear_regression_dataset.csv`**: Çoklu regresyon için birden fazla öznitelik içeren veri seti.
* **`polynomial_regression.csv`**: Üstel / kavisli ilişki gösteren non-linear veriler.
* **`decision+tree+regression+dataset.csv`**: Karar ağacı regresyon modelleri için seviye/fiyat gibi veriler.
* **`random_forest_regression_dataset.csv`**: Rastgele orman regresyonu için deneme verileri.
* **`gender_classifier.csv`**: Cinsiyet tahmini / sınıflandırma modelleri için kullanılan öznitelik verileri.
* **`movie.csv`**: NLP veya Öneri Sistemleri (Recommendation Systems) notebook'larında film önerileri/değerlendirmeleri için kullanılan veri seti.
* **`data.csv`**: Genel sınıflandırma ve kümeleme adımlarında kullanılan ham veri seti.

---

## 🚀 Çalıştırma

1. Depoyu klonlayın:
   ```bash
   git clone [https://github.com/Rasittekin18/4-Machine_Learning.git](https://github.com/Rasittekin18/4-Machine_Learning.git)
   cd 4-Machine_Learning
