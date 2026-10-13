# Modul 2: Mengambil dan Membersihkan Data

## 🎯 Fokus Pembelajaran
Modul ini membahas langkah pertama dan paling krusial dalam *pipeline* Machine Learning, yaitu proses ekstraksi data (membaca data dari berbagai sumber) dan prapemrosesan data (*Data Cleaning*). Kualitas data yang baik akan sangat menentukan akurasi dari model yang akan dibangun.

## 📝 Rangkuman Materi
- **Membaca Data (Data Reading):** 
  - Praktik membuat koneksi ke *database* SQL (menggunakan `sqlite3`) langsung dari lingkungan Python.
  - Menggunakan fungsi dari *library* Pandas (seperti `pd.read_sql`) untuk mengeksekusi *query* SQL dan mengubah *output*-nya menjadi Pandas DataFrame agar mudah dianalisis.
- **Pembersihan Data (Data Cleaning):**
  - Mengatasi masalah *Missing Values* (data kosong/NaN) melalui teknik imputasi atau penghapusan (*dropping*).
  - Menghapus baris data yang duplikat (*duplicate records*).
  - Menyesuaikan dan memperbaiki format tipe data yang tidak konsisten.

## 🛠️ Library yang Digunakan
- `sqlite3`: Untuk mengelola koneksi dan *query* ke database SQL lokal.
- `pandas`: Untuk manipulasi, pembersihan, dan analisis data terstruktur (*DataFrame*).

## 📂 Lampiran File
- `modul2_data_reading.ipynb` : *Jupyter Notebook* yang berisi implementasi kode untuk membaca data dari *database* SQLite, menjalankan *query*, dan menampilkannya dalam bentuk *DataFrame* berserta parameternya.
