# RENCANA BUKU 1: STATISTIKA UNTUK ANALISIS DATA
**Penulis:** Dr. Ridwan Ilyas, S.Kom., M.T.  
**Afiliasi:** Program Studi Teknik Informatika, Fakultas Sains dan Informatika, Universitas Jenderal Achmad Yani (UNJANI)  
**Tahun:** 2026  
**Lisensi:** Open Source (MIT)

---

## 🎯 Deskripsi & Tujuan Buku
Buku ini dirancang khusus sebagai buku ajar komputasional dan panduan praktis bagi mahasiswa Teknik Informatika, Sains Data, dan Rekayasa Perangkat Lunak. Buku ini mengintegrasikan konsep teori statistika dengan implementasi pemrograman Python modern (*Exploratory Data Analysis*, Pengujian Hipotesis, Teori Probabilitas, Pemodelan Prediktif Regresi, Klasifikasi Logistik, Reduksi Dimensi PCA, Pengelompokan K-Means, *Association Rules Data Mining*, dan Studi Kasus Industri Nyata).

---

## 📚 Struktur Bab dan Rencana Materi

### **BAGIAN I: FONDASI DATA & EXPLORATORY DATA ANALYSIS (EDA)**
* **Bab 1: Pengantar Analisis Data dan Skala Pengukuran**
  * 1.1 Paradigma Analisis Data: Deskriptif, Diagnostik, Prediktif, dan Preskriptif
  * 1.2 Skala Pengukuran Data: Nominal, Ordinal, Interval, dan Rasio
  * 1.3 Implikasi Skala terhadap *Feature Encoding* (One-Hot vs. Ordinal Encoding)
  * 1.4 Praktikum Python: *Data Ingestion* dan Pemeriksaan Tipe Data (`pandas`)
* **Bab 2: Ukuran Pemusatan, Penyebaran, dan Deteksi Outlier**
  * 2.1 Ukuran Pemusatan (*Mean, Median, Modus*)
  * 2.2 Ukuran Penyebaran (*Variance, Standard Deviation, Range, IQR*)
  * 2.3 Deteksi Data Pencilan (*Outlier Detection*: IQR Rule & Z-Score)
  * 2.4 Praktikum Python: Pembersihan Outlier dan Statistik Deskriptif Otomatis
* **Bab 3: Visualisasi Data Eksploratif dan Tabulasi Silang**
  * 3.1 Tabel Frekuensi dan Tabel Kontingensi (*Crosstab*)
  * 3.2 Visualisasi Distribusi: Histogram, KDE Plot, Boxplot, dan Scatter Plot
  * 3.3 Praktikum Python: Membangun Dasbor EDA dengan `seaborn` & `matplotlib`

### **BAGIAN II: UJI ASUMSI, KORELASI, DAN INFERENSIAL DATA**
* **Bab 4: Pengujian Asumsi Data dan Diagnostik Statistik**
  * 4.1 Distribusi Normal dan *Central Limit Theorem*
  * 4.2 Uji Normalitas: Shapiro-Wilk, Kolmogorov-Smirnov, dan Q-Q Plot
  * 4.3 Uji Homogenitas Varians (Levene's Test) dan Multikolinearitas (VIF)
  * 4.4 Praktikum Python: Pipeline Otomasi Pengujian Asumsi Dataset
* **Bab 5: Analisis Korelasi dan Seleksi Fitur**
  * 5.1 Korelasi Pearson ($r$), Spearman Rank ($ho$), dan Point-Biserial
  * 5.2 Korelasi Parsial (Mengontrol Variabel Perancu)
  * 5.3 Praktikum Python: Seleksi Fitur Berbasis Matriks Korelasi & Heatmap

### **BAGIAN III: PEMODELAN PREDIKTIF & MACHINE LEARNING**
* **Bab 6: Analisis Regresi Linier Sederhana dan Berganda**
  * 6.1 Teori *Ordinary Least Squares* (OLS) dan Estimasi Parameter
  * 6.2 Evaluasi Model: $R^2$, *Adjusted* $R^2$, Uji F (Simultan), dan Uji t (Parsial)
  * 6.3 Diagnostik Residual (Linearitas, Homoskedastisitas, Normalitas Galat)
  * 6.4 Praktikum Python: Estimasi Biaya Software dengan `statsmodels` & `scikit-learn`
* **Bab 7: Regresi Logistik untuk Pemodelan Klasifikasi**
  * 7.1 Fungsi Sigmoid, Logit, dan *Odds Ratio* ($e^eta$)
  * 7.2 Estimasi *Maximum Likelihood* (MLE) dan Evaluasi (*Confusion Matrix, ROC-AUC*)
  * 7.3 Praktikum Python: Prediksi Kelancaran Kredit UMKM / Deteksi *Churn*

### **BAGIAN IV: REDUKSI DIMENSI, PENGELOMPOKAN, & DATA MINING**
* **Bab 8: Reduksi Dimensi dan Analisis Faktor (PCA)**
  * 8.1 *Curse of Dimensionality*, Vektor Eigen, dan *Eigenvalues*
  * 8.2 Kriteria Kaiser, *Scree Plot*, dan Rotasi Varimax
  * 8.3 Praktikum Python: Kompresi Fitur Kompleks Menggunakan `sklearn.decomposition.PCA`
* **Bab 9: Analisis Klaster (Cluster Analysis / Unsupervised Learning)**
  * 9.1 Jarak Euclidean, Manhattan, dan Cosine
  * 9.2 Klasterisasi Hirarki (Dendrogram) dan *K-Means Clustering*
  * 9.3 Penentuan Jumlah Klaster Optimal (*Elbow Method* & *Silhouette Score*)
  * 9.4 Praktikum Python: Segmentasi Perilaku Pelanggan Sistem
* **Bab 10: Penambangan Pola Asosiasi (Market Basket Analysis)**
  * 10.1 *Association Rule Mining* dan Algoritma Apriori
  * 10.2 Metrik Kunci: *Support, Confidence,* dan *Lift*
  * 10.3 Praktikum Python: Sistem Rekomendasi Keranjang Belanja dengan `mlxtend`

### **BAGIAN V: TEORI PROBABILITAS & DISTRIBUSI PELUANG**
* **Bab 11: Teori Probabilitas dan Distribusi Peluang**
  * 11.1 Aksioma Peluang, Peluang Bersyarat, dan Teorema Bayes
  * 11.2 Distribusi Diskrit: Distribusi Binomial dan Distribusi Poisson
  * 11.3 Distribusi Kontinu: Distribusi Normal (Gaussian) dan Transformasi Z-Score
  * 11.4 Praktikum Python: Simulasi Peluang dan Pemodelan Laju Request Server

### **BAGIAN VI: STUDI KASUS INTEGRATIF INDUSTRI**
* **Bab 12: Studi Kasus 1 - Prediksi Risiko Kredit & Fintech Analytics**
  * 12.1 Pipeline Scoring Kelayakan Kredit UMKM End-to-End
  * 12.2 Tuning Decision Threshold untuk Optimasi Keuntungan dan Mitigasi NPL
* **Bab 13: Studi Kasus 2 - Segmentasi Pelanggan & Rekomendasi E-Commerce**
  * 13.1 Pemetaan Persona Belanja (K-Means) & Penambangan Pola Bundling (Apriori)
  * 13.2 Perancangan Rekomendasi Cross-Selling untuk Meningkatkan AOV
* **Bab 14: Studi Kasus 3 - Eksperimentasi A/B Testing & Optimasi Kinerja Sistem**
  * 14.1 Desain Eksperimen Komparasi Antarmuka & Infrastruktur Server
  * 14.2 Pengujian Hipotesis Komparatif (Welch t-Test & Chi-Square of Proportions)
