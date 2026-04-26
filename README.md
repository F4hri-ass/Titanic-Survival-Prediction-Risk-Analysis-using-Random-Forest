# 🚢 Titanic Survival Prediction – Random Forest Classifier

## 📌 Project Overview
Proyek penelitian ini bertujuan untuk menganalisis dan memprediksi faktor-faktor yang mempengaruhi tingkat keselamatan penumpang kapal Titanic menggunakan algoritma **Random Forest Classifier**. Fokus utama proyek ini adalah menangani ketidakseimbangan data (*imbalanced data*) untuk meningkatkan presisi prediksi pada kelas minoritas (penumpang selamat).

## 📊 Dataset & Features
Dataset terdiri dari 891 data latih dan 418 data prediksi dengan fitur utama:
*   **Pclass**: Kelas tiket (1, 2, 3).
*   **Sex**: Jenis kelamin (Female, Male).
*   **Age**: Usia penumpang.
*   **Fare**: Tarif tiket (Indikator status ekonomi).
*   **Embarked**: Pelabuhan keberangkatan.

## 🛠️ Data Science Workflow
1.  **Exploratory Data Analysis (EDA)**: Menemukan bahwa penumpang perempuan dan pemegang tiket kelas atas memiliki peluang selamat yang jauh lebih tinggi.
2.  **Data Cleaning**: Menghapus variabel *noise* (Name, Ticket, Cabin) dan menangani *missing values* pada kolom Age dan Embarked.
3.  **Feature Engineering**: Menerapkan *One-Hot Encoding* untuk variabel kategorikal.
4.  **Handling Imbalanced Data**: Menggunakan teknik **RandomOverSampler** untuk menyeimbangkan distribusi kelas target.
5.  **Modeling**: Membangun model *Ensemble Learning* dengan algoritma **Random Forest**.

## 🚀 Key Results
*   **Model Performance**: Mencapai akurasi **91%** pada data uji.
*   **Metrics**: 
    *   F1-Score (Selamat): 0.91
    *   Precision (Tidak Selamat): 0.97
*   **Insights**: Tarif tiket (Fare) merupakan fitur numerik yang paling berpengaruh terhadap prediksi keselamatan.


**Developed by Muhammad Fahri Novarian**  
