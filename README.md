# Proyek Akhir: Menyelesaikan Permasalahan Attrition Perusahaan Jaya Jaya Maju

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
Distribusi data attrition
Korelasi fitur terhadap Attrition
Korelasi antara fitur yang memiliki korelasi tertinggi dengan attrition dengan fitur pilihan

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

Sumber data yang kita dapatkan kali ini adalah data karyawan dari perusahaan jaya jaya maju yang mengundurkan diri dan yang tidak mengundurkan diri sesuai dengan nilai yang ada pada dataset,dataset ini memiliki banyak kolom yang dapat membantu kita menganalisis tinggi nya tingkat attrition pada perusahaan jaya jaya maju
berikut link dataset yang kita gunakan : (https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv)

Setup environment - Shell/Terminal (Download File):

```
1.Analysis and Modelling 
cd SUBMISSION-1-DICODING
pipenv install
pipenv shell
pip install -r requirements.txt
```
```
2.Prediksi (Membuat Notebook baru)
ketik %run /path_dari_file.py
isi data sesuai petunjuk
hasil prediksi akan muncul
```
```
2.Prediksi (Lewat Terminal)
ketik python nama_file.py
isi data sesuai petunjuk
hasil prediksi akan muncul
```

## Business Dashboard

saya membuat dashboard ini untuk membantu mengidentifikasi kelompok karyawan yang lebih mudah keluar, sehingga perusahaan dapat mengambil langkah strategis untuk mengurangi tingkat karyawan yang resign dan kesejahteraan kerja.
berikut link untuk menuju dashboard saya: https://lookerstudio.google.com/reporting/32c8bae8-104d-45c2-91ee-b7d7f5cb2cfe 

## Conclusion

Setelah analisis yang dilakukan saya menemukan bahwa beberapa penyebab dari meningkatnya attrition pada perusahaan tersebut ialah OverTime, MaritalStatus_Single, JobRole_Sales Representative, JobRole_Laboratory Technician, BusinessTravel_Travel_Frequently, memiliki tingkat korelasi dengan Attrition yang tinggi dan menjadi penyebab mengapa karyawan banyak yang mengundurkan diri.

### Rekomendasi Action Items (Optional)

Berikut rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka:

-Evaluasi sistem lembur: Adakan program monitoring stres kerja dan work-life balance.

-Evaluasi untuk posisi Sales: Evaluasi beban kerja, target, dan insentif pada divisi Sales.

-Strategi untuk Single: Jalur Karier yang Jelas, Fleksibilitas Kerja, Manfaat Personal yang Fleksibel.

-Perjalanan Dinas: Berikan opsi untuk hybrid atau manfaat tambahan untuk kompensasi fatigue dari frequent travel.

## Cara Menggunakan Model 
1.Buka file prediksi.py yang telah didownload 

2.Masukkan data sesuai dengan template didalam file prediksi.py dengan ketentuan:

OverTime: Masukan 1 untuk ya 0 untuk tidak

MaritalStatus_Single: Masukan 1 untuk ya 0 untuk tidak

JobRole_Sales Representative: Masukan 1 untuk ya 0 untuk tidak

JobRole_Laboratory Technician: Masukan 1 untuk ya 0 untuk tidak

BusinessTravel_Travel_Frequently: Masukan 1 untuk ya 0 untuk tidak

EnvironmentSatisfaction: 1-Low, 2-Medium, 3-High, 4-Very High

YearsAtCompany: berapa tahun

JobInvolvement: 1-Low, 2-Medium, 3-High, 4-Very High

YearsWithCurrManager: berapa tahun

YearsInCurrentRole: berapa tahun

MonthlyIncome: masukkan gaji

StockOptionLevel: Stock Option Level

JobLevel: Level of job (1 to 5)

Age: Age

TotalWorkingYears: berapa tahun


