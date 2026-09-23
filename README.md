# Machine Learning for Data Analyst

Repository ini berisi script dan contoh praktik Machine Learning menggunakan Python yang dirancang untuk mendukung pembelajaran **Machine Learning for Data Analyst**.

Contoh kasus menggunakan permasalahan pada sektor **kelautan dan perikanan**, khususnya klasifikasi data nelayan untuk mengidentifikasi data yang **perlu dilakukan verifikasi**.

## 🎯 Learning Objectives

Melalui repository ini, peserta dapat memahami alur dasar Machine Learning:

1. Memahami business problem
2. Menyiapkan data
3. Menentukan feature dan target
4. Melakukan train-test split
5. Melakukan preprocessing
6. Melatih model Machine Learning
7. Melakukan prediction
8. Mengevaluasi model
9. Membandingkan performa model
10. Menggunakan model untuk memprediksi data baru

## 🤖 Machine Learning Algorithms

Repository ini mencakup beberapa algoritma klasifikasi:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- Gradient Boosting

## 🌊 Case Study

Contoh permasalahan:

> **Apakah suatu data nelayan perlu dilakukan verifikasi?**

Model menggunakan karakteristik data nelayan sebagai input, kemudian menghasilkan:

- Prediksi: Perlu / Tidak Perlu Verifikasi
- Probability: probabilitas perlu verifikasi
- Prioritas: indikasi prioritas verifikasi

Contoh alur:

Data Nelayan  
↓  
Data Preparation  
↓  
Train-Test Split  
↓  
Machine Learning Model  
↓  
Prediction  
↓  
Model Evaluation  
↓  
Prediction pada Data Baru

## 📊 Model Evaluation

Model dievaluasi menggunakan beberapa metrik:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

Penekanan utama bukan hanya pada:

> "Berapa accuracy model?"

tetapi juga:

> **"Kesalahan apa yang dibuat model?"**

## 🔮 Prediction on New Data

Setelah model dilatih dan dievaluasi, model dapat digunakan untuk melakukan prediction terhadap data nelayan baru yang belum memiliki label.

Contoh:

```text
Data Nelayan Baru
        ↓
Model Terlatih
        ↓
Prediction
        +
Probability
        ↓
Perlu Verifikasi?
