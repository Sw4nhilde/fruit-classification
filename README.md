# 🍊 Orange vs Grapefruit Classification

## 📌 Deskripsi
Project ini bertujuan untuk mengklasifikasikan buah apakah termasuk **orange (jeruk)** atau **grapefruit (anggur)** berdasarkan fitur fisik seperti diameter, berat, dan warna.

Dataset diambil dari Kaggle:
https://www.kaggle.com/datasets/joshmcadams/oranges-vs-grapefruit

---

## 🎯 Tujuan
Membandingkan performa 3 algoritma machine learning:
- Decision Tree
- Naive Bayes
- Support Vector Machine (SVM)

---

## 🔄 Tahapan Pengerjaan

### 1. Data Collection
Dataset diunduh dari Kaggle dan dimuat menggunakan pandas.

---

### 2. Data Understanding (EDA)
- Mengecek struktur data (`info()`)
- Statistik data (`describe()`)
- Mengecek missing value
- Visualisasi distribusi data

---

### 3. Data Preprocessing
- Label encoding pada kolom target (`name`)
- Memisahkan fitur (X) dan target (y)
- Train-test split (80:20)
- Normalisasi menggunakan StandardScaler

---

### 4. Model Training
Tiga model yang digunakan:
- Decision Tree
- Naive Bayes (GaussianNB)
- Support Vector Machine (SVM)

---

### 5. Evaluation
Model dievaluasi menggunakan:
- Accuracy
- Classification Report
- Confusion Matrix

---

## 📊 Hasil

| Model | Accuracy |
|------|--------|
| Decision Tree | 0.944 |
| Naive Bayes | 0.920 |
| SVM | 0.937 |

---

## 🏆 Kesimpulan
Berdasarkan hasil pengujian, model dengan performa terbaik adalah:
👉 **Decission Tree**

Karena memiliki akurasi tertinggi dalam mengklasifikasikan data.

---

## ⚙️ Tools & Library
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## 🚀 Cara Menjalankan

1. Install dependency:
```pip install pandas numpy scikit-learn matplotlib seaborn```
2. Jalankan program:
```modelUTS.py```

---

## 👤 Author
Nama: Muhammad Eka Mandiri Sujanto
