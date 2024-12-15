# Regresyon Modeli ile Kredi Risk Puanı Hesaplama

<p align="center">
  <a href="https://pandas.pydata.org/">
    <img src="https://img.shields.io/badge/Pandas-1.x-blue?logo=pandas&logoColor=white" alt="Pandas">
  </a>
  <a href="https://scikit-learn.org/">
    <img src="https://img.shields.io/badge/Scikit--Learn-0.24-green?logo=scikit-learn&logoColor=white" alt="Scikit-Learn">
  </a>
  <a href="https://matplotlib.org/">
    <img src="https://img.shields.io/badge/Matplotlib-3.x-orange?logo=matplotlib&logoColor=white" alt="Matplotlib">
  </a>
  <a href="https://docs.python.org/3/library/tkinter.html">
    <img src="https://img.shields.io/badge/Tkinter-Built--in-yellow?logo=tkinter&logoColor=white" alt="Tkinter">
  </a>
</p>


<p align="center">
  <a href="README.md">
    <img src="https://img.shields.io/badge/lang-English-blue.svg" alt="English">
  </a>
  <a href="README_TR.md">
    <img src="https://img.shields.io/badge/lang-Türkçe-red.svg" alt="Turkish">
  </a>
</p>

## Proje Hakkında

Bu proje, banka müşterilerinin finansal verilerini analiz ederek kredi risk puanlarını hesaplamak için bir regresyon modeli geliştirmeyi amaçlamaktadır. Müşterilerin maaşı, kredi limitleri ve hesaplarındaki bakiye gibi verileri kullanarak tahminler yapılır ve bankaların kredi değerlendirme süreçleri optimize edilir.

---

## Hedefler 📋

1. **Doğru Kredi Risk Puanı Hesaplama**: Müşterilerin finansal verilerini kullanarak risk puanlarını tahmin etmek.
2. **Optimizasyon**: Bankaların kredi değerlendirme süreçlerini iyileştirmek.
3. **Makine Öğrenimi Modelleri**: **RandomForest** ve **LinearRegression** gibi regresyon modellerini kullanmak.

---

## Çalışma Süreci

### 1. **Veri Ön İşleme**
- Kaggle'dan alınan `Loan.csv` veri setini kullanarak:
  - Veri okuma
  - Veri istatistiklerinin çıkarılması
  - Null değerlerin tespiti
  - Veri türlerinin belirlenmesi
  - Eşsiz değer tespiti
  - Gereksiz kolonların silinmesi
  - Object değerlere `LabelEncoder` uygulanması
  - Hedef değişkenin ayrılması

### 2. **Model Eğitimi**
- **RandomForestRegressor** ve **LinearRegression** ile modeli eğitme.
- **R² skoru** ve **Ortalama Kare Hatası (MSE)** gibi metriklerle model değerlendirme.

### 3. **Metriklerin Oluşturulması**
- İki nodel üzerindeki çalışmalar sonucu RandomForestRegressor modeli tercih edilmiştir. İlgili metriklerin görselleri aşağıdadır.
### RandomForest:
<img src="images/RandomForest.png" alt="RandomForest">
<img src="images/RandomMetric.png" alt="RandomMetric">

### Linear:

<img src="images/Linear.png" alt="Linear">
<img src="images/LinearMetric.png" alt="LinearMetric">

### 4. **Arayüz Geliştirme ve Sonuç**
- **Tkinter** kullanarak müşteri verilerini girebileceğiniz ve tahmin sonuçlarını görebileceğiniz bir arayüz oluşturma.
- Model ile tahmin testleri yapılması
- Yapılan testlerde kullanılan değerler train datasetinden ayrı tutulan değerlerdir.
### Birinci test:
<img src="images/Pred1.jpg" alt="Pred1">
<img src="images/Pred1_1.jpg" alt="Pred1_1">

### İkinci test:

<img src="images/Pred2.jpg" alt="Pred2">
<img src="images/Pred2_2.jpg" alt="Pred2_2">


## Veri Seti 📂

Veri seti Kaggle'da mevcuttur:  

<p align="left">
  <a href="https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval">
    <img src="klogo.png" alt="Kaggle link" width="50">
  </a>
</p>

`Loan.csv` dosyası `dataset/` klasöründe mevcut.

---

## Kullanılan Teknolojiler 🛠️
- **Python** - Ana programlama dili
- **Pandas** - Veri manipülasyonu
- **Scikit-Learn** - Makine öğrenimi
- **Matplotlib** - Görselleştirme
- **Tkinter** - Arayüz geliştirme

---

## Geliştiriciler 👨‍💻

- **Furkan Hamza BOLAT**  
  **Email:** [furkanhamzabolat@gmail.com](mailto:furkanhamzabolat@gmail.com)  

- **Furkan DAYI**  
  **Email:** [furkan.dyi@hotmail.com](mailto:furkan.dyi@hotmail.com)

