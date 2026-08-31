# 📊 Statistika Komputasi untuk Sains Data dan Rekayasa Perangkat Lunak
> **Repositori Modul Praktikum & Silabus Buku Ajar Statistika Terapan**  
> **Program Studi Teknik Informatika, Fakultas Sains dan Informatika**  
> **Universitas Jenderal Achmad Yani (UNJANI) — 2026**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python: 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-14%20Notebooks-orange.svg)](https://jupyter.org/)
[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%99%A5-red.svg)](https://github.com/rdwnilyas-coder)

---

## 👨‍🏫 Dosen Pengampu & Pengembang Modul
* **Nama:** Dr. Ridwan Ilyas, S.Kom., M.T.
* **Afiliasi:** Program Studi Teknik Informatika, Universitas Jenderal Achmad Yani (UNJANI)
* **Tahun Akademik:** 2026

---

## 📖 Tentang Repositori
Repositori ini bersifat **Open Source** dan dirancang khusus untuk mendukung perkuliahan **Statistika Komputasi** serta menjadi pendamping komputasional dari dua rencana buku ajar:
1. 📘 **Buku 1: Statistika untuk Analisis Data** (*Data Analytics, Data Science, Machine Learning, Data Mining & Studi Kasus Industri*)
2. 📗 **Buku 2: Statistika pada Pengembangan Perangkat Lunak** (*Software QA, Usability SUS/TAM, Inter-Rater Reliability, A/B Testing & Survival Analysis*)

Setiap modul praktikum disusun dalam format interaktif **Jupyter Notebook (`.ipynb`)**, dilengkapi dengan:
* 🎨 **Visual Ilustrasi Konsep PNG (Aturan 60:30:10)** pada setiap materi.
* 📂 **Dataset Contoh Realistis (`.csv`)** yang siap pakai di folder `datasets/`.
* 🐍 **Kode Python Komputasi Statistik** menggunakan pustaka standar industri (`pandas`, `scipy`, `statsmodels`, `scikit-learn`, `mlxtend`, `seaborn`).
* 📊 **Visualisasi Grafik Kontekstual & Tabel Hasil Pengujian**.
* 📝 **Paragraf Kesimpulan Saintifik Terstruktur** (*Q&A, Key Findings, dan Actionable Insights*).

---

## 🗂️ Struktur Direktori Proyek

```
Statistika/
│
├── README.md                                                  # Dokumentasi Utama Proyek
├── LICENSE                                                    # Lisensi Open Source MIT
├── requirements.txt                                           # Daftar dependensi pustaka Python
├── .gitignore                                                 # Filter file sementara / dokumen privat
│
├── Rencana_Buku_1_Statistika_Analisis_Data.md                 # Silabus Lengkap Rencana Buku 1
├── Rencana_Buku_2_Statistika_Pengembangan_Perangkat_Lunak.md  # Silabus Lengkap Rencana Buku 2
│
├── datasets/                                                  # Koleksi Dataset Realistis CSV
│   ├── 01_ecommerce_sales_eda.csv                             # Transaksi E-Commerce (Modul 01, 02, 03)
│   ├── 02_server_performance_assumptions.csv                  # Metrik Kinerja Server (Modul 04)
│   ├── 03_user_engagement_correlation.csv                     # Metrik Interaksi User (Modul 05)
│   ├── 04_software_cost_regression.csv                        # Estimasi Biaya Software (Modul 06)
│   ├── 05_credit_risk_classification.csv                      # Kelayakan Kredit UMKM (Modul 07 & 12)
│   ├── 06_dim_reduction_customer_features.csv                 # Fitur Multidimensi Pengguna (Modul 08)
│   ├── 07_customer_segmentation_clustering.csv                # Perilaku Belanja (Modul 09 & 13)
│   ├── 08_market_basket_transactions.csv                      # Transaksi Keranjang Belanja (Modul 10 & 13)
│   ├── 09_probability_distributions.csv                       # Simulasi Peluang & Antrian (Modul 11)
│   └── 10_ab_testing_system_metrics.csv                       # Eksperimen A/B Testing Sistem (Modul 14)
│
├── images/                                                    # Koleksi Visual Ilustrasi PNG (60:30:10)
│
└── notebooks/                                                 # 14 Modul Praktikum Jupyter Notebooks
    ├── 01_eksplorasi_dan_skala_pengukuran.ipynb               # Skala Nominal, Ordinal, Rasio & Encoding
    ├── 02_ukuran_pemusatan_penyebaran_outlier.ipynb           # Mean, Median, IQR, Z-Score & Outlier
    ├── 03_visualisasi_data_dan_tabel_kontingensi.ipynb        # Crosstab, Heatmap, Boxplot & Multivariat
    ├── 04_pengujian_asumsi_data_diagnostik.ipynb              # Shapiro-Wilk, Q-Q Plot, Levene, VIF
    ├── 05_analisis_korelasi_dan_feature_selection.ipynb       # Korelasi Pearson, Spearman & Parsial
    ├── 06_regresi_linier_sederhana_dan_berganda.ipynb         # OLS Regression, R-squared, Uji F & t
    ├── 07_regresi_logistik_klasifikasi_biner.ipynb            # Sigmoid, Odds Ratio, Confusion Matrix, ROC
    ├── 08_reduksi_dimensi_pca_dan_faktor.ipynb                # PCA, Eigenvalues, Scree Plot, Biplot
    ├── 09_analisis_klaster_kmeans_dan_hirarki.ipynb           # Dendrogram, K-Means, Elbow & Silhouette
    ├── 10_market_basket_association_rules.ipynb               # Support, Confidence, Lift, Apriori
    ├── 11_teori_probabilitas_dan_distribusi.ipynb             # Bayes, Binomial, Poisson, Normal, Z-Score
    ├── 12_studi_kasus_prediksi_risiko_fintech.ipynb           # Studi Kasus 1: Credit Scoring & Threshold
    ├── 13_studi_kasus_segmentasi_rekomendasi_ecommerce.ipynb  # Studi Kasus 2: Persona Klaster & Bundling
    └── 14_studi_kasus_optimasi_kinerja_sistem_abtesting.ipynb # Studi Kasus 3: A/B Testing Latency & Conv
```

---

## 📚 Daftar Lengkap 14 Modul Praktikum (Buku 1)

| No | Modul Praktikum | Topik Utama | Pustaka Utama |
| :---: | :--- | :--- | :--- |
| **01** | [Eksplorasi & Skala Pengukuran](notebooks/01_eksplorasi_dan_skala_pengukuran.ipynb) | Tipe Data, Skala Nominal-Ordinal-Rasio, One-Hot Encoding | `pandas`, `seaborn` |
| **02** | [Pemusatan, Penyebaran & Outlier](notebooks/02_ukuran_pemusatan_penyebaran_outlier.ipynb) | Mean, Median, Modus, IQR, Z-Score, Deteksi Outlier | `scipy.stats`, `matplotlib` |
| **03** | [Visualisasi & Crosstab](notebooks/03_visualisasi_data_dan_tabel_kontingensi.ipynb) | Tabel Kontingensi, Proporsi Bivariat, Violin Plot | `pandas`, `seaborn` |
| **04** | [Uji Asumsi Data](notebooks/04_pengujian_asumsi_data_diagnostik.ipynb) | Shapiro-Wilk, Q-Q Plot, Uji Levene, Analisis VIF | `scipy.stats`, `statsmodels` |
| **05** | [Analisis Korelasi & Seleksi Fitur](notebooks/05_analisis_korelasi_dan_feature_selection.ipynb) | Pearson $r$, Spearman $
ho$, Korelasi Parsial, Heatmap | `scipy.stats`, `seaborn` |
| **06** | [Regresi Linier Berganda](notebooks/06_regresi_linier_sederhana_dan_berganda.ipynb) | OLS Regression, $R^2$, Diagnostik Residual, Prediksi Biaya | `statsmodels.api`, `sklearn` |
| **07** | [Regresi Logistik Biner](notebooks/07_regresi_logistik_klasifikasi_biner.ipynb) | Sigmoid, Odds Ratio ($e^eta$), Confusion Matrix, ROC-AUC | `statsmodels`, `sklearn` |
| **08** | [Reduksi Dimensi (PCA)](notebooks/08_reduksi_dimensi_pca_dan_faktor.ipynb) | Vektor Eigen, Kriteria Kaiser, Scree Plot, 2D Biplot | `sklearn.decomposition` |
| **09** | [Analisis Klaster K-Means](notebooks/09_analisis_klaster_kmeans_dan_hirarki.ipynb) | Klasterisasi Hirarki, K-Means, Elbow Curve, Silhouette | `scipy.cluster`, `sklearn` |
| **10** | [Market Basket Analysis](notebooks/10_market_basket_association_rules.ipynb) | Support, Confidence, Lift, Algoritma Apriori | `mlxtend` |
| **11** | [Teori Probabilitas & Distribusi](notebooks/11_teori_probabilitas_dan_distribusi.ipynb) | Teorema Bayes, Distribusi Binomial, Poisson, Normal | `scipy.stats`, `numpy` |
| **12** | [Studi Kasus 1: Risiko Fintech](notebooks/12_studi_kasus_prediksi_risiko_fintech.ipynb) | Scoring Kredit UMKM, ROC-AUC & Threshold Tuning | `statsmodels`, `sklearn` |
| **13** | [Studi Kasus 2: E-Commerce](notebooks/13_studi_kasus_segmentasi_rekomendasi_ecommerce.ipynb) | Persona Segmentasi K-Means & Aturan Rekomendasi | `sklearn`, `mlxtend` |
| **14** | [Studi Kasus 3: A/B Testing](notebooks/14_studi_kasus_optimasi_kinerja_sistem_abtesting.ipynb) | Uji Beda Welch t-Test & Chi-Square Rasio Konversi | `scipy.stats`, `seaborn` |

---

## 🚀 Panduan Memulai & Menjalankan Modul

### 1. Kloning Repositori
```bash
git clone https://github.com/rdwnilyas-coder/statistika-komputasi-unjani.git
cd statistika-komputasi-unjani
```

### 2. Menyiapkan Virtual Environment Python
```bash
# Membuat virtual environment
python3 -m venv venv

# Mengaktifkan environment (macOS/Linux)
source venv/bin/activate
# Windows: venv\Scripts\activate
```

### 3. Memasang Dependensi
```bash
pip install -r requirements.txt
```

### 4. Menjalankan JupyterLab / Notebook
```bash
jupyter lab
```

---

## 📜 Lisensi & Hak Cipta
Repositori dan seluruh materi di dalamnya dilisensikan di bawah **[MIT License](LICENSE)**. Bebas digunakan, dimodifikasi, dan didistribusikan untuk keperluan akademik, pengajaran, penelitian, maupun pengembangan profesional.

---
**Teknik Informatika — Universitas Jenderal Achmad Yani (UNJANI)**  
*Jl. Terusan Jend. Sudirman, Cimahi, Jawa Barat 40525*
