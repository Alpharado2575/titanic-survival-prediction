# 🚢 Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-orange)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-red)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-lightblue)

## 📋 Daftar Isi
- [Deskripsi Proyek](#deskripsi-proyek)
- [Tujuan Proyek](#tujuan-proyek)
- [Dataset](#dataset)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)

## 📋 Deskripsi Proyek

Proyek ini bertujuan untuk memprediksi penumpang mana yang selamat dari tragedi Titanic menggunakan algoritma **Logistic Regression**. Dataset yang digunakan adalah dataset Titanic klasik yang berisi informasi penumpang seperti kelas tiket, jenis kelamin, usia, dan lain-lain.

**Akurasi Model: 81%**

## 🎯 Tujuan Proyek

1. Menerapkan **end-to-end machine learning pipeline**
2. Melakukan **Exploratory Data Analysis (EDA)** untuk memahami pola data
3. Mengimplementasikan **data preprocessing** (handling missing values, encoding, scaling)
4. Membangun model **Logistic Regression** untuk klasifikasi
5. Mengevaluasi performa model dengan berbagai metrics

## 📊 Dataset

Dataset diambil dari [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data) dengan total **891 sampel** dan **12 fitur**:

| Fitur | Deskripsi |
|-------|-----------|
| PassengerId | ID unik penumpang |
| Survived | Target variable (0 = Tidak Selamat, 1 = Selamat) |
| Pclass | Kelas tiket (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name | Nama penumpang |
| Sex | Jenis kelamin |
| Age | Usia dalam tahun |
| SibSp | Jumlah saudara/pasangan di kapal |
| Parch | Jumlah orang tua/anak di kapal |
| Ticket | Nomor tiket |
| Fare | Tarif tiket |
| Cabin | Nomor kabin |
| Embarked | Pelabuhan embarkasi (C = Cherbourg, Q = Queenstown, S = Southampton) |

## 🛠️ Teknologi yang Digunakan

- **Python 3.11** - Bahasa pemrograman utama
- **Pandas** - Manipulasi dan analisis data
- **NumPy** - Operasi numerik
- **Matplotlib & Seaborn** - Visualisasi data
- **Scikit-learn** - Machine learning library
