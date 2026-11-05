# Modul 4: Statistik Inferensial dan Pengujian Hipotesis

## 🎯 Fokus Pembelajaran
Berbeda dengan statistik deskriptif yang hanya merangkum data yang ada, modul ini membahas **Statistik Inferensial**, yaitu bagaimana kita menarik kesimpulan tentang seluruh populasi berdasarkan sampel data yang kita miliki. Modul ini mengajarkan validasi secara matematis agar temuan dari data tidak sekadar kebetulan belaka.

## 📝 Rangkuman Materi
- **Distribusi Probabilitas:** Memahami konsep distribusi normal (kurva lonceng) dan pentingnya *Z-score* dalam menentukan seberapa jauh sebuah titik data dari rata-rata.
- **Pengujian Hipotesis (Hypothesis Testing):**
  - Menyusun Hipotesis Nol ($H_0$) yang menyatakan tidak ada efek/hubungan, dan Hipotesis Alternatif ($H_1$).
  - Memahami parameter keberhasilan uji statistik melalui nilai batas Signifikansi ($\alpha$, biasanya 0.05).
- **Interpretasi p-value:** Menggunakan *p-value* untuk mengambil keputusan. Jika *p-value* < $\alpha$, maka Hipotesis Nol ditolak, membuktikan bahwa temuan (seperti perbedaan antar grup atau korelasi) secara statistik signifikan.
- **Uji Statistik Terapaan:** Pengenalan pada *T-test* (untuk membandingkan rata-rata dua kelompok) dan evaluasi korelasi.

## 🛠️ Library yang Digunakan
- `scipy` (scipy.stats): Library utama untuk fungsi statistik ilmiah, distribusi probabilitas, dan pengujian hipotesis di Python.
- `pandas`: Untuk menyiapkan struktur data sebelum diuji.
