# Titanic Explorer Predicting Survival with Classificaion using KNN Algorithm

## Descripton
Titanic Explorer: Menelusuri Kekelamatan Hidup dengan Pendekatan Analisis Prediktif KNN. Memanfaatkan Dataset Titanic, kami menerapkan analisis klasifikasi untuk memprediksi nasib penumpang berdasarkan beragam fitur. Metode KNN digunakan untuk membimbing model prediktif ini, menawarkan wawasan mendalam tentang faktor-faktor yang memengaruhi kemungkinan seseorang selamat. Dengan mengeksplorasi keterkaitan antara karakteristik penumpang dan kelangsungan hidup, proyek ini memberikan perspektif yang lebih dalam tentang peristiwa bersejarah tersebut. Melalui visualisasi yang kuat dan hasil evaluasi model, Titanic Explorer mengajak untuk memahami lebih baik dinamika di balik tragedi kapal Titanic melalui lensa analisis data modern.

## Data Collecting 
Dataset ini berisi data dari penumpang kapal titanic. Peristiwa tenggelamnya kapal titanic ini pada tanggal 15 April 1912. Dataset diperoleh langsung dari Kaggle melalui sumber berikut: [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## Bahasa 
**Bahasa Pemrograman**: Python

## Analisis Data
### 1. Data Preparation
- **Data Cleaning**: Menggunakan metode menghapus null value karena hanya sedikit data yang bernilai null.
- **Data Transformation**: Melakukan perubahan tipe data dan menghapus kolom yang tidak digunakan.

### 2. Splitting data
Pemisahan antara data test dan data train menggunakan rasio 70:30.

### 3. Modelling 
Penerapan metode klasifikasi menggunakan algoritma K-Nearest Neighbors (KNN).

### 5. Hasil Modelling dan Evaluasi Model
#### Decision Tree
Evaluasi menunjukkan TN (True Negative) sebanyak 142 dan TP (True Positive) sebanyak 52.
Berdasarkan Classification Report algoritma KNN dianggap lebih baik dengan hasil evaluasi sebagai berikut:
- **Accuracy**: 71%
- **Precision**: 71%
- **Recall**: 71%
- **F1-Score**: 71%

### 6. Identifikasi Variable yang Berpengaruh Terhadap Customer Churn
Feature Importance menggunakan K-Nearest Neighbors (KNN) menunjukkan bahwa variabel yang paling berpengaruh adalah Fare. Kesimpulan: Penumpang yang membayar lebih mahal lebih berpotensi untuk selamat karena mendapatkan fasilitas yang lebih baik.

