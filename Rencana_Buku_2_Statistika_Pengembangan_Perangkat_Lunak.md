# RENCANA BUKU 2: STATISTIKA PADA PENGEMBANGAN PERANGKAT LUNAK
**Penulis:** Dr. Ridwan Ilyas, S.Kom., M.T.  
**Afiliasi:** Program Studi Teknik Informatika, Fakultas Sains dan Informatika, Universitas Jenderal Achmad Yani (UNJANI)  
**Tahun:** 2026  
**Lisensi:** Open Source (MIT)

---

## 🎯 Deskripsi & Tujuan Buku
Buku ini berfokus pada integrasi metode statistika inferensial dan pengukuran dalam disiplin Rekayasa Perangkat Lunak (*Software Engineering*), *Human-Computer Interaction* (HCI), dan *Software Quality Assurance* (QA). Pembahasan mencakup desain dan uji reliabilitas instrumen kuesioner usabilitas (SUS, TAM, UEQ), uji kesepakatan antar penguji/tester (Cohen's & Fleiss' Kappa), eksperimen A/B Testing sistem, analisis varians interaksi antarmuka (Two-Way ANOVA), serta pemodelan keandalan sistem (*Software Reliability Engineering*) dan retensi pengguna (*Survival Analysis*).

---

## 📚 Struktur Bab dan Rencana Materi

### **BAGIAN I: PENGANTAR METRIK & SAMPLING PERANGKAT LUNAK**
* **Bab 1: Peran Statistika dalam Software Development Life Cycle (SDLC)**
  * 1.1 Pengambilan Keputusan Berbasis Bukti Data dalam Rekayasa Software
  * 1.2 Taksonomi Metrik Perangkat Lunak: Proses, Kualitas Kode, Defect, dan UX
  * 1.3 Teknik Sampling Responden Pengguna dan Penentuan Sampel Minimum

### **BAGIAN II: INSTRUMEN SURVEI & PENGUJIAN RELIABILITAS KUESIONER**
* **Bab 2: Kerangka Kerja Pengukuran Usabilitas dan Skala Pengukuran**
  * 2.1 Standar Kuesioner: *System Usability Scale* (SUS), TAM, dan UEQ
  * 2.2 Perhitungan Skor SUS dan Interpretasi *Percentile Rank / Adjective Rating*
* **Bab 3: Uji Validitas dan Reliabilitas Konsistensi Internal**
  * 3.1 Teori Pengukuran Klasik dan Validitas Butir (*Item-Total Correlation*)
  * 3.2 **Cronbach's Alpha ($lpha$)**: Formula, Standar Penerimaan ($\ge 0.70$), dan Analisis *Item Deleted*
  * 3.3 Praktikum Python: Uji Validitas & Reliabilitas Kuesioner SUS (`pingouin`)

### **BAGIAN III: UJI KESEPAKATAN ANTAR-EVALUATOR (INTER-RATER RELIABILITY & QA)**
* **Bab 4: Pengukuran Konsistensi pada Software Testing & Bug Reporting**
  * 4.1 Mengapa *Percentage Agreement* Menyesatkan (*Correction for Chance Agreement*)
  * 4.2 **Cohen's Kappa ($\kappa$)** untuk Data Nominal (Dua Evaluator QA)
* **Bab 5: Uji Kesepakatan Lanjutan: Weighted Kappa & Fleiss' Kappa**
  * 5.1 **Weighted Cohen's Kappa** untuk Data Ordinal (Tingkat Keparahan Bug / *Severity*)
  * 5.2 **Fleiss' Kappa** untuk Banyak Evaluator ($> 2$ Rater pada *Heuristic Usability Review*)
  * 5.3 Praktikum Python: Menghitung Indeks Kesepakatan QA dengan `statsmodels`

### **BAGIAN IV: EKSPERIMENTASI SOFTWARE, A/B TESTING & KOMPARASI SISTEM**
* **Bab 6: Desain Eksperimen & Uji Hipotesis Software Testing**
  * 6.1 Perumusan Hipotesis Komparasi ($H_0$ vs $H_1$, $lpha$, $p$-value)
  * 6.2 *Between-Subjects* vs. *Within-Subjects Experimental Design*
* **Bab 7: Uji Komparasi Dua Versi Sistem (A/B Testing)**
  * 7.1 *Independent Two-Sample t-Test* dan Welch's t-Test (A/B Testing UI/Algoritma)
  * 7.2 *Paired Samples t-Test* (Kinerja Sebelum vs. Sesudah Refactoring)
  * 7.3 Uji Non-Parametrik: Mann-Whitney U Test & Wilcoxon Signed-Rank Test
  * 7.4 Uji Chi-Square & Binomial untuk Perbandingan *Conversion Rate*
* **Bab 8: Analisis Varians (ANOVA) Multi-Faktor dan Efek Interaksi**
  * 8.1 *One-Way ANOVA* dan Uji Pasca-ANOVA (*Tukey HSD / Bonferroni*)
  * 8.2 *Two-Way ANOVA*: Efek Utama (*Main Effects*) dan Efek Interaksi (*Interaction Effects*)
  * 8.3 *Repeated Measures ANOVA* untuk Pengujian Berulang
  * 8.4 Uji Non-Parametrik Kruskal-Wallis untuk Banyak Kelompok

### **BAGIAN V: ANALISIS KEANDALAN SISTEM & WAKTU BERTAHAN (SURVIVAL ANALYSIS)**
* **Bab 9: Pemodelan Keandalan Perangkat Lunak (Software Reliability Engineering)**
  * 9.1 Analisis *Time-to-Event* dan Data Tersensor (*Censored Data*)
  * 9.2 Metrik MTBF (*Mean Time Between Failures*), MTTR, dan Laju Kegagalan
  * 9.3 Kurva Kelangsungan Hidup Kaplan-Meier dan Uji Log-Rank Antar-Rilis
* **Bab 10: Analisis Retensi & Waktu Churn Pengguna (User Churn Modeling)**
  * 10.1 Pemodelan Bahaya Proporsional Cox (*Cox Proportional Hazards Model*)
  * 10.2 Identifikasi Faktor Risiko Berhentinya Pengguna Menggunakan Aplikasi
  * 10.3 Praktikum Python: Pemodelan Keandalan & Churn dengan `lifelines`

### **BAGIAN VI: STUDI KASUS INTEGRATIF EVALUASI SOFTWARE**
* **Bab 11: Studi Kasus Evaluasi Software End-to-End**
  * 11.1 Studi Kasus 1: Evaluasi Usabilitas Redesain SIM Kampus (Kuesioner SUS, Cronbach's Alpha, Two-Way ANOVA)
  * 11.2 Studi Kasus 2: Penilaian Konsistensi Klasifikasi Kerentanan Bug QA (Weighted & Fleiss' Kappa)
  * 11.3 Studi Kasus 3: A/B Testing & Retensi Peluncuran Fitur Baru (t-Test, Chi-Square, Kaplan-Meier)
