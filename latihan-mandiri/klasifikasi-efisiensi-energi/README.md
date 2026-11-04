# EcoPulse - Modul Klasifikasi Efisiensi Energi (Fitur 2)

Repositori ini berisi progres belajar dan implementasi algoritma Decision Tree untuk mengklasifikasikan status efisiensi energi operasional gedung ke dalam kelas Efisien, Normal, dan Boros[cite: 8, 9]. Proyek ini merupakan bagian dari prototipe sistem EcoPulse yang dikembangkan untuk mata kuliah Data Mining 2026 di Universitas Dian Nuswantoro[cite: 5].

**Tujuan Proyek**
* Membentuk label kelas efisiensi energi melalui pembagian sepertiga kuantil dari atribut konsumsi absolut[cite: 16].
* Melatih model Decision Tree Classifier berdasarkan atribut lingkungan dan operasional gedung[cite: 10]. 
* Mengeluarkan atribut target (EnergyConsumption) dari fitur masukan untuk mencegah terjadinya kebocoran informasi (data leakage)[cite: 17].
* Mengekspor model akhir dalam bentuk pipeline berformat pickle (`fitur2_klasifikasi_efisiensi.pkl`) yang siap dimuat oleh backend[cite: 14].

**Dataset**
* Proyek ini menggunakan dataset sintetik "Energy Consumption Prediction" dari Kaggle[cite: 15].
* Dataset berisi 1.000 baris pencatatan data per jam selama 42 hari dengan 11 kolom atribut dasar[cite: 15].

**Teknologi & Pustaka**
* Bahasa: Python[cite: 19].
* Pustaka Analisis & Praproses: pandas, NumPy[cite: 19].
* Pustaka Machine Learning: scikit-learn (Decision Tree Classifier, GridSearchCV, Pipeline)[cite: 13, 19, 20].
* Visualisasi: matplotlib, seaborn[cite: 19].
* Serialisasi Model: joblib[cite: 14, 19].

**Arsitektur Modul**
Model dilatih di lingkungan notebook dan diekspor menggunakan `joblib`[cite: 14]. Proses praproses data digabungkan di dalam pipeline `scikit-learn` agar transformasi data konsisten saat model diintegrasikan ke layanan API FastAPI[cite: 12, 14].
