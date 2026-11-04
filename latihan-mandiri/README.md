# EcoPulse - Modul Klasifikasi Efisiensi Energi (Fitur 2)

Repositori ini berisi progres belajar dan implementasi algoritma Decision Tree untuk mengklasifikasikan status efisiensi energi operasional gedung ke dalam kelas Efisien, Normal, dan Boros. Proyek ini merupakan bagian dari prototipe sistem EcoPulse yang dikembangkan untuk mata kuliah Data Mining 2026 di Universitas Dian Nuswantoro.

**Tujuan Proyek**
* Membentuk label kelas efisiensi energi melalui pembagian sepertiga kuantil dari atribut konsumsi absolut.
* Melatih model Decision Tree Classifier berdasarkan atribut lingkungan dan operasional gedung. 
* Mengeluarkan atribut target (EnergyConsumption) dari fitur masukan untuk mencegah terjadinya kebocoran informasi (data leakage).
* Mengekspor model akhir dalam bentuk pipeline berformat pickle (`fitur2_klasifikasi_efisiensi.pkl`) yang siap dimuat oleh backend.

**Dataset**
* Proyek ini menggunakan dataset sintetik "Energy Consumption Prediction" dari Kaggle.
* Dataset berisi 1.000 baris pencatatan data per jam selama 42 hari dengan 11 kolom atribut dasar.

**Teknologi & Pustaka**
* Bahasa: Python.
* Pustaka Analisis & Praproses: pandas, NumPy.
* Pustaka Machine Learning: scikit-learn (Decision Tree Classifier, GridSearchCV, Pipeline).
* Visualisasi: matplotlib, seaborn.
* Serialisasi Model: joblib.

**Arsitektur Modul**
Model dilatih di lingkungan notebook dan diekspor menggunakan `joblib`. Proses praproses data digabungkan di dalam pipeline `scikit-learn` agar transformasi data konsisten saat model diintegrasikan ke layanan API FastAPI[cite: 12, 14].
