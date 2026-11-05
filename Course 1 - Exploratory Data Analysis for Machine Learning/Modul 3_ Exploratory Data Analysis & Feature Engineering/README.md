# Modul 3: Analisis Data Eksplorasi (EDA) dan Rekayasa Fitur

## 🎯 Fokus Pembelajaran
Modul ini berfokus pada dua tahapan analitik inti sebelum membangun model: memahami karakteristik bawaan dari data melalui **Exploratory Data Analysis (EDA)**, dan memanipulasi data mentah menjadi variabel yang lebih informatif untuk algoritma Machine Learning melalui **Feature Engineering** (Rekayasa Fitur).

## 📝 Rangkuman Materi
- **Exploratory Data Analysis (EDA):**
  - Menggunakan statistik deskriptif (mean, median, standar deviasi) untuk merangkum data.
  - Memvisualisasikan distribusi data menggunakan *Histogram* dan *Boxplot* untuk mendeteksi *outliers* (pencilan).
  - Mengidentifikasi hubungan (korelasi) antar variabel numerik menggunakan *Scatter Plot* dan *Heatmap* korelasi.
- **Feature Engineering (Rekayasa Fitur):**
  - **Encoding Data Kategorikal:** Mengubah data teks menjadi angka agar bisa diproses mesin (misalnya menggunakan *One-Hot Encoding* atau *Label Encoding*).
  - **Feature Scaling:** Menstandarkan rentang nilai data menggunakan *Min-Max Scaler* (Normalisasi) atau *Standard Scaler* (Standardisasi) agar fitur dengan skala besar tidak mendominasi model.
  - Membuat fitur baru (*feature creation*) dari fitur yang sudah ada untuk memberikan sinyal yang lebih kuat pada model prediksi.

## 🛠️ Library yang Digunakan
- `pandas`: Untuk manipulasi *DataFrame*.
- `matplotlib` & `seaborn`: Untuk visualisasi data grafis.
- `scikit-learn` (sklearn.preprocessing): Untuk alat bantu rekayasa fitur seperti *Scaler* dan *Encoder*.
