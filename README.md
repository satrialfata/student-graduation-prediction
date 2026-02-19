# Prediksi Kelulusan Mahasiswa Menggunakan Logistic Regression

## Deskripsi Project

Project ini merupakan implementasi Machine Learning Classification menggunakan algoritma Logistic Regression untuk memprediksi kelulusan mahasiswa berdasarkan:

- Jam belajar
- Kehadiran
- Nilai tugas

Model akan mengklasifikasikan apakah mahasiswa Lulus (1) atau Tidak Lulus (0).

## 🧠 Algoritma yang Digunakan

- Logistic Regression
- Evaluasi menggunakan:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC Curve
  - AUC Score

Library:

- pandas
- numpy
- matplotlib
- scikit-learn

## Struktur Dataset

| Feature     | Deskripsi                           |
| ----------- | ----------------------------------- |
| jam_belajar | Jumlah jam belajar mahasiswa        |
| kehadiran   | Persentase kehadiran (%)            |
| nilai_tugas | Nilai tugas mahasiswa               |
| lulus       | Target (0 = Tidak Lulus, 1 = Lulus) |

Dataset dibuat secara manual untuk simulasi pembelajaran.

## Tahapan Proses

1. Membuat dataset menggunakan pandas
2. Memisahkan fitur (X) dan target (y)
3. Split data menjadi training dan testing (70:30)
4. Training model Logistic Regression
5. Evaluasi performa model
6. Prediksi data baru
7. Visualisasi hasil

## Evaluasi Model

### 1️⃣ Accuracy

Mengukur persentase prediksi yang benar.

### 2️⃣ Confusion Matrix

Menampilkan:

- True Positive
- True Negative
- False Positive
- False Negative

### 3️⃣ Classification Report

Berisi:

- Precision
- Recall
- F1-Score

### 4️⃣ ROC Curve & AUC

- ROC Curve menunjukkan trade-off antara TPR dan FPR
- AUC mengukur kualitas model klasifikasi

---

## 📊 Visualisasi

Project ini menghasilkan beberapa visualisasi:

- Scatter plot distribusi mahasiswa berdasarkan kelulusan
- Confusion Matrix
- ROC Curve
- Histogram probabilitas prediksi

---

## 🔮 Contoh Prediksi

```python
data_baru = np.array([[4, 80, 78]])
```

Output:

- Prediksi Lulus / Tidak Lulus
- Koefisien model
- Intercept model

---

## 🚀 Cara Menjalankan Project

1. Clone repository:

git clone https://github.com/satrialfata/student-graduation-prediction.git

2. Install dependencies:

pip install pandas numpy matplotlib scikit-learn

3. Jalankan notebook atau script Python.

---

## 📌 Tujuan Project

- Pembelajaran dasar klasifikasi
- Memahami Logistic Regression
- Memahami evaluasi model Machine Learning
- Implementasi visualisasi ROC dan AUC

---

## Author

Satrialfata
Data Science Enthusiast
