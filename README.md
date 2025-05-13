# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

Untuk mencegah hal ini semakin parah, manajer departemen HR ingin meminta bantuan Anda mengidentifikasi berbagai faktor yang mempengaruhi tingginya attrition rate tersebut. Selain itu, ia juga meminta Anda untuk membuat business dashboard untuk membantunya memonitori berbagai faktor tersebut.

### Permasalahan Bisnis

Masalah dalam pengelolaan karyawan dikarekan angka attrition rate lebih dari 10%

### Cakupan Proyek

#### Analisis dan Prediksi Employee Attrition dengan Python dan Google Looker Studio

##### Tujuan:
Membangun sistem analisis menyeluruh untuk memahami faktor-faktor yang memengaruhi attrition karyawan dan membuat model prediksi apakah seorang karyawan berisiko mengundurkan diri (attrition) atau tidak. Hasil akhir divisualisasikan dalam dashboard interaktif menggunakan Google Looker Studio.

##### Cakupan Proyek:
1.Data Preparation & Cleaning (Jupyter Notebook / .ipynb)
Membaca dataset employee.csv

Membersihkan data:
Menangani nilai null
Encoding variabel kategorikal (One-hot encoding / Label encoding)
Feature selection dan engineering

Eksplorasi data awal (EDA):
Korelasi fitur terhadap Attrition

2.Feature Analysis (Statistik & Korelasi)
Visualisasi heatmap korelasi fitur terhadap Attrition
Analisis fitur penting seperti:
OverTime, JobRole, MaritalStatus, BussinesTravel, dll

3.Modeling: Predictive Machine Learning
Menentukan target: Attrition (Yes/No)

Model yang digunakan:
Random Forest

Splitting data: 
Train-Test split

Evaluasi model:
Accuracy, Precision, Recall, F1-score
Confusion Matrix
ROC Curve / AUC

4.Dashboard Visualisasi (Google Looker Studio)
Menyambungkan Google Sheets hasil preprocessing ke Looker Studio

Menampilkan:
KPI utama (Total Karyawan, Attrition Rate, Jumlah Atrition)
Visualisasi fitur terhadap attrition (histogram)

### Persiapan

Sumber data: ....

Setup environment:

```
1. Notebook & Data Processing
Platform: Google Colaboratory (Google Colab)

Bahasa Pemrograman: Python

Library yang Digunakan:
pandas – untuk manipulasi data
numpy – untuk perhitungan numerik
matplotlib, seaborn – untuk visualisasi eksploratif (EDA)
scikit-learn – untuk preprocessing data dan membuat model machine learning

2. Visualisasi Bisnis
Platform: Google Looker Studio

3. Penyimpanan Data
Dataset awal dalam format .csv
Dataset dibersihkan dan diproses di Google Colab, lalu di convert ke csv untuk digunakan di Looker Studio
```

## Business Dashboard

Jelaskan tentang business dashboard yang telah dibuat. Jika ada, sertakan juga link untuk mengakses dashboard tersebut.

## Conclusion

Jelaskan konklusi dari proyek yang dikerjakan.

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- action item 1
- action item 2
