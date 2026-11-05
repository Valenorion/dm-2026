# Modul 5: Tugas Akhir (Course 1 Capstone)

## 🎯 Fokus Pembelajaran
Modul ini merupakan puncak dari Course 1, di mana seluruh konsep dan teknik dari Modul 1 hingga Modul 4 diintegrasikan ke dalam satu proyek akhir yang komprehensif. Fokus utamanya adalah mendemonstrasikan alur kerja (*workflow*) siklus hidup data yang utuh, mulai dari data mentah hingga penarikan kesimpulan statistik.

## 📝 Rangkuman Proyek
Pada tugas akhir ini, tahapan analisis yang dilakukan meliputi:
- **Pengumpulan dan Pembersihan Data (Data Wrangling):** Mengekstrak dataset, menangani nilai yang hilang (*missing values*), menghapus duplikasi, dan menstandarisasi format tipe data.
- **Eksplorasi Data (EDA):** Melakukan inspeksi visual menggunakan *histogram*, *boxplot*, dan *scatter plot* untuk mengidentifikasi pola, tren, dan *outliers* di dalam data.
- **Rekayasa Fitur (Feature Engineering):** Melakukan transformasi data, termasuk *encoding* variabel kategorikal dan *scaling* variabel numerik agar data siap digunakan untuk analisis lebih lanjut.
- **Pengujian Hipotesis (Hypothesis Testing):** Menerapkan statistik inferensial (seperti *T-test* atau uji korelasi) untuk memvalidasi apakah temuan visual dari tahap EDA memiliki signifikansi statistik secara matematis, bukan sekadar kebetulan.

## 🛠️ Library yang Digunakan
Proyek ini menggabungkan seluruh *library* inti yang telah dipelajari:
- `pandas` & `sqlite3`: Untuk manajemen dan pemrosesan data.
- `matplotlib` & `seaborn`: Untuk visualisasi data grafis.
- `scikit-learn` (`preprocessing`): Untuk rekayasa fitur (*scaling* & *encoding*).
- `scipy` (`stats`): Untuk pengujian hipotesis dan perhitungan *p-value*.
