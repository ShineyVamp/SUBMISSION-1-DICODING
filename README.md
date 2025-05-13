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

Sumber data: (https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv)

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
imabalnced-learn - untuk mengatasi data tidak seimban

2. Visualisasi Bisnis
Platform: Google Looker Studio

3. Penyimpanan Data
Dataset awal dalam format .csv
Dataset dibersihkan dan diproses di Google Colab, lalu di convert ke csv untuk digunakan di Looker Studio
```

## Business Dashboard

saya membuat dashboard ini untuk membantu mengidentifikasi kelompok karyawan yang lebih mudah keluar, sehingga perusahaan dapat mengambil langkah strategis untuk mengurangi tingkat karyawan yang resign dan kesejahteraan kerja.
berikut link untuk menuju dashboard saya: https://lookerstudio.google.com/reporting/32c8bae8-104d-45c2-91ee-b7d7f5cb2cfe 

## Conclusion

Setelah analisis yang dilakukan saya menemukan bahwa beberapa penyebab dari meningkatnya attrition pada perusahaan tersebut ialah OverTime, MaritalStatus_Single, JobRole_Sales Representative, JobRole_Laboratory Technician, BusinessTravel_Travel_Frequently, memiliki tingkat korelasi dengan Attrition yang tinggi dan menjadi penyebab mengapa karyawan banyak yang mengundurkan diri.

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

-Evaluasi sistem lembur: Adakan program monitoring stres kerja dan keseimbangan kerja-hidup.

-Evaluasi untuk posisi Sales: Evaluasi beban kerja, target, dan insentif pada divisi Sales.

-Strategi untuk Single: Jalur Karier yang Jelas, Fleksibilitas Kerja, Manfaat Personal yang Fleksibel.

-Perjalanan Dinas: Berikan opsi untuk hybrid atau manfaat tambahan untuk kompensasi fatigue dari frequent travel.

