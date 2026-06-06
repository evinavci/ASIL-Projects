# ASIL-Projects
# ASIL Lab Projeleri: Veri Analizi ve Derin Öğrenme

Bu depo, veri bilimi, makine öğrenmesi ve tıbbi görüntü işleme alanlarında geliştirilmiş çeşitli analiz ve sınıflandırma projelerini içermektedir. Projeler, veriyi anlamlandırmaktan karmaşık derin öğrenme modelleri kurmaya kadar farklı seviyelerdeki uygulamaları barındırır.

##  Projeler

### 1. Dünya Mutluluk Raporu Analizi (`world-happiness-report-data-analysis.ipynb`)
Dünya Mutluluk Raporu verileri üzerinden detaylı bir Keşifçi Veri Analizi (EDA) çalışması.
* **Kullanılan Yöntemler:** İstatistiksel Analiz, Veri Görselleştirme.
* **Öne Çıkanlar:** Ülkelerin mutluluk skorlarını etkileyen temel faktörlerin (gelir, sağlık, özgürlük vb.) grafiklerle analizi ve korelasyonların incelenmesi.

### 2. Kredi Kartı Sahtekarlık Tespiti (`fraud_detection_hw.ipynb`)
Kredi kartı işlem verileri üzerinden anomali tespiti yapılarak sahte (fraud) ve yasal işlemlerin birbirinden ayrılması.
* **Kullanılan Yöntemler:** Makine Öğrenmesi, Veri Ön İşleme, Dengesiz Veri Seti Yönetimi.
* **Öne Çıkanlar:** Anomali tespiti için özellik mühendisliği (feature engineering) ve model performansının hassasiyet (precision) ile değerlendirilmesi.

### 3. Meme Kanseri Tespiti (`breastcancer.ipynb`)
Bu proje, BreaKHis veri seti kullanılarak tıbbi görüntüleme üzerinden meme kanseri tespiti yapmayı amaçlamaktadır. 
* **Kullanılan Yöntemler:** Evrişimli Sinir Ağları (CNN), Derin Öğrenme, Görüntü Sınıflandırma.
* **Performans:** Geliştirilen model ile histopatolojik görüntüler üzerinde **%80'in üzerinde sınıflandırma doğruluğu (accuracy)** elde edilmiştir.
* **Öne Çıkanlar:** Görüntülerin modele uygun hale getirilmesi, veri artırma (data augmentation) teknikleri ve yüksek doğruluklu derin öğrenme modelinin eğitilmesi.

## Kullanılan Teknolojiler ve Araçlar
* **Programlama Dili:** Python
* **Ortam:** Jupyter Notebook
* **Temel Kütüphaneler:** Pandas, NumPy, Matplotlib, Seaborn
* **Makine & Derin Öğrenme:** Scikit-Learn, TensorFlow / Keras
