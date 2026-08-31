# 🎨 PANDUAN STANDAR DESAIN PRESENTASI POWERPOINT (STYLE PPT)
> **Statistika Komputasi untuk Sains Data dan Rekayasa Perangkat Lunak**  
> **Program Studi Teknik Informatika, Fakultas Sains dan Informatika**  
> **Universitas Jenderal Achmad Yani (UNJANI) — 2026**  
> **Penulis & Pengembang:** Dr. Ridwan Ilyas, S.Kom., M.T.

---

## 🎯 1. Filosofi & Karakter Visual Desain
Standar presentasi ini mengadopsi gaya visual **Modern 2D Flat Cartoon Vector Infographic** yang harmonis dengan gambar ilustrasi kurikulum Statistika Komputasi UNJANI:
* **Bersih, Lapang & Tidak Padat (*Generous Negative Space*)**: Mengutamakan kenyamanan membaca audiens dengan ruang kosong minimal 40–50%.
* **Modular Berbasis Kartu (*Card-Based Layout*)**: Seluruh informasi dikelompokkan dalam panel kartu membulat (*rounded card containers*) dengan garis tepi (*outline*) yang tegas dan ramah.
* **Bebas Teks Panjang (*Concise & Visual First*)**: Menghindari paragraf panjang (*wall of text*). Informasi disajikan melalui poin ringkas, lencana metrik (*pill badges*), rumus terkotak, dan metafora visual dunia nyata.
* **Aturan Tanpa Tabrakan (*Zero-Intersection Rule*)**: Garis kurva, panah alur, dan titik data tidak boleh memotong teks judul, label angka, maupun ikon.

---

## 🎨 2. Palet Warna Standar (Aturan Harmoni 60:30:10)

Gaya warna presentasi mengacu pada kombinasi **Deep Emerald Teal & Vibrant Amber Gold**:

| Peran Warna | Proporsi | Nama Warna | Kode Hex | Nilai RGB | Penggunaan Utama |
| :--- | :---: | :--- | :---: | :---: | :--- |
| **Dominan** | **60%** | Pure Clean White | `#FFFFFF` | `255, 255, 255` | Latar belakang slide (*canvas background*) & badan kartu utama. |
| **Latar Kartu Tipis** | *(Sub-60%)* | Light Slate Mist | `#F8FAFC` | `248, 250, 252` | Pengisi kartu sekunder, latar kode, dan kontainer kontras lembut. |
| **Struktur Sekunder** | **30%** | Deep Emerald Teal | `#0F4C5C` | `15, 76, 92` | Tipografi judul utama, bingkai kartu, garis sumbu kurva, dan ikon dominan. |
| **Struktur Aksen** | *(Sub-30%)* | Dark Pine Green | `#064E3B` | `6, 78, 59` | Teks sub-judul, tombol utama, dan header tabel. |
| **Aksen Vokal** | **10%** | Vibrant Amber Gold | `#F59E0B` | `245, 158, 11` | Titik anomali/outlier, trofi bintang, badge status penting, dan garis batas keputusan. |
| **Aksen Hangat** | *(Sub-10%)* | Warm Honey Orange | `#FB8500` | `251, 133, 0` | Panah alur proses (*workflow arrows*) dan lencana kesimpulan (*takeaways*). |
| **Teks Badan (Body)** | — | Deep Slate Charcoal | `#1E293B` | `30, 41, 59` | Teks penjelasan reguler, poin keterangan, dan data numerik tabel. |

---

## 🔤 3. Standar Tipografi & Skala Hirarki Huruf

Gunakan font modern *sans-serif* yang memiliki keterbacaan tinggi dari jarak jauh:

### Rekomendasi Font Utama:
1. **Utama (Headings & Body):** `Poppins`, `Montserrat`, `Plus Jakarta Sans`, atau `Inter`
2. **Monospace (Kode & Rumus Numerik):** `JetBrains Mono`, `Fira Code`, atau `Consolas`

### Skala Ukuran Font (Slide 16:9 Widescreen — 1920x1080 px):

| Elemen Teks | Jenis Font / Weight | Ukuran (pt) | Warna | Contoh Penggunaan |
| :--- | :--- | :---: | :---: | :--- |
| **Slide Title (Atas)** | Bold / Extra Bold (KAPITAL) | `32 – 36 pt` | `#0F4C5C` | `SKALA PENGUKURAN DATA` |
| **Slide Subtitle** | Medium / Semi-Bold | `16 – 18 pt` | `#0D9488` | *4 Tingkatan Pengukuran dalam Komputasi & Sains Data* |
| **Card Header Title** | Bold | `20 – 22 pt` | `#0F4C5C` | `1. NOMINAL` / `2. ORDINAL` |
| **Body / Point Text** | Regular / Medium | `14 – 16 pt` | `#1E293B` | `Label identitas kategori tanpa urutan matematis.` |
| **Metric Badge / Value** | Bold | `18 – 24 pt` | `#F59E0B` | `ROC-AUC = 0.895` / `R² = 0.880` |
| **Footer Card Pill** | Bold (KAPITAL) | `11 – 13 pt` | `#FFFFFF` | `KATEGORI LABEL` *(pada pill background Teal)* |
| **Source / Footnote** | Regular / Italic | `10 – 12 pt` | `#64748B` | *Sumber: Modul 01 Statistika Komputasi UNJANI 2026* |

---

## 📐 4. Format & Tata Letak Slide (Slide Canvas Layout)

* **Rasio Kanvas:** `16:9 Widescreen` (1920 x 1080 px).
* **Margin Aman (*Safe Margin*):** Minimal `60 px` dari setiap sisi kanvas (Kiri, Kanan, Atas, Bawah).
* **Struktur Header Atas (Wajib di Setiap Slide Konten):**
  - **Judul Utama:** Terpusat (*centered*) atau rata kiri-atas dengan font kapital tebal warna Deep Emerald Teal.
  - **Sub-Judul Konteks:** Tepat di bawah judul utama dengan font italic/medium warna Slate Teal.
  - **Garis Pembatas Aksen (*Opsional*):** Garis horizontal tipis `2 px` warna Amber Gold di bawah sub-judul.

---

## 🧩 5. Desain Komponen Visual Standar

### A. Kontainer Kartu (*Rounded Card Panel*)
* **Bentuk:** Persegi panjang dengan sudut membulat (*Corner Radius*: `16 – 24 px`).
* **Garis Tepi (*Stroke Outline*):** Solid tebal `2.5 – 3.5 px` dengan warna `#0F4C5C` (Deep Emerald Teal).
* **Latar Belakang Kartu:** `#FFFFFF` (Putih) atau `#F8FAFC` (Slate Mist).
* **Efek Bayangan (*Drop Shadow*):** Sangat halus (*Blur: 12px, Opacity: 6%, Offset Y: 4px*). Hindari bayangan gelap tebal.

### B. Lencana Status (*Pill Badges*)
* **Bentuk:** Kapsul membulat penuh (*Full Rounded Pill*).
* **Tipe 1 (Lencana Kategori/Footer):** Latar `#0F4C5C` (Teal), Teks Putih `#FFFFFF` huruf kapital tebal.
* **Tipe 2 (Lencana Aksen/Highlight):** Latar `#FEF3C7` (Amber Muda), Teks `#B45309` (Amber Gelap), Garis tepi `#F59E0B`.
* **Tipe 3 (Lencana Sukses/Metrik Valid):** Latar `#CCFBF1` (Mint Muda), Teks `#0F766E` (Teal Gelap).

### C. Kotak Rumus Matematis & Notasi Statistik
* Tampilkan rumus dalam panel tersendiri dengan latar belakang `#F1F5F9` berbingkai teal `2 px`.
* Gunakan simbol matematika yang rapi:
  $$\text{Odds Ratio} = e^\beta = \frac{P(Y=1) / (1 - P(Y=1))}{P(Y=0) / (1 - P(Y=0))}$$
* Berikan kotak sorotan amber gold pada parameter kunci yang sedang dibahas.

### D. Panah Alur Proses (*Workflow Connectors*)
* Gunakan panah tebal bergaya kartun membulat warna **Vibrant Amber Gold (`#F59E0B`)** atau **Warm Honey Orange (`#FB8500`)**.
* Letakkan panah di antara kartu-kartu proses yang mengalir dari kiri ke kanan.

---

## 📑 6. Struktur Template Slide Presentasi (7 Jenis Slide)

```
+-----------------------------------------------------------------------------+
|                                MASTER SLIDE SET                             |
|                                                                             |
|  [SLIDE 1] Cover Kuliah / Bab       --> Judul Bab, Kode MK, Dosen & Logo    |
|  [SLIDE 2] Peta Konsep & Capaian    --> 3-Card Sasaran Pembelajaran (CPL)   |
|  [SLIDE 3] Infografis 2D Utama      --> Penempatan Gambar Ilustrasi Konsep  |
|  [SLIDE 4] Formulasi & Bedah Rumus  --> Kotak KaTeX Math + Logika Komputasi |
|  [SLIDE 5] Praktikum Python Code    --> Editor Dark/Light Box + Hasil Plot  |
|  [SLIDE 6] Analisis Kasus Nyata     --> Matriks Keputusan & Rekomendasi     |
|  [SLIDE 7] Ringkasan & Q&A          --> 3 Takeaway Cards + Footer Kontak    |
+-----------------------------------------------------------------------------+
```

### 1. Slide Cover (Judul Bab & Pertemuan)
* Latar belakang: Putih bersih dengan hiasan geometris sudut membulat teal & amber di pojok kanan atas.
* Judul Bab: `MODUL 06: PEMODELAN REGRESI LINIER` (Bold 40pt, `#0F4C5C`).
* Sub-judul: `Statistika Komputasi untuk Sains Data — Teknik Informatika UNJANI`.
* Profil: Nama Dosen Pengampu & Tahun Akademik di pojok kiri bawah.

### 2. Slide Infografis Konsep Utama
* Header: Judul materi terpusat di atas.
* Area Tengah: Menempatkan gambar ilustrasi 2D dari repositori (`notebooks/images/img_XX_....png`).
* Area Bawah: 3–4 lencana pill ringkas yang merangkum poin visual kartu.

### 3. Slide Formulasi Matematis & Komputasi
* Sisi Kiri: Kotak penjelasan konsep teoretis & analogi dunia nyata.
* Sisi Kanan: Kotak rumus matematika berbingkai teal dengan parameter bertanda sorot warna amber gold.

### 4. Slide Implementasi Kode Python & Output
* Sisi Kiri: Cuplikan kode Python bersih berlatar dark slate (`#0F172A`) dengan sintaks *highlighting*.
* Sisi Kanan: Grafik output visual (Plot Matplotlib/Seaborn) dengan lencana interpretasi statistik di bawahnya.

### 5. Slide Analisis Kasus Industri Nyata
* Format 2 Kolom:
  - Kolom 1: *Problem Statement & Dataset Context* (Fintech / E-Commerce / Cloud).
  - Kolom 2: *Statistical Inference & Business Action* (Keputusan berbasis ambang batas $p\text{-value}$ / ROC-AUC).

### 6. Slide Ringkasan (*Key Takeaways*)
* 3 Kartu Berjejer Mendatar:
  - Kartu 1: *Konsep Kunci*
  - Kartu 2: *Aturan Keputusan Statistik*
  - Kartu 3: *Praktik Terbaik Pemrograman*

---

## 🚫 7. Pantangan Desain (*Design Don'ts*)

1. ❌ **Dilarang menggunakan warna gradien pelangi atau warna neon mencolok** yang bertabrakan dengan palet Teal-Amber.
2. ❌ **Dilarang menumpuk teks di atas gambar ilustrasi**. Setiap gambar harus berada di ruang negatif yang bersih.
3. ❌ **Dilarang memotong kata (*awkward line-breaking*)** pada judul atau angka penting (contoh: `$10` terpisah dari `Juta`).
4. ❌ **Dilarang membuat slide dengan lebih dari 6 baris teks per poin**. Jika materi panjang, pecah menjadi 2 slide kartu terpisah.
5. ❌ **Dilarang menggunakan gambar raster buram (*low-resolution*)**. Selalu gunakan file PNG resolusi tinggi dari folder `notebooks/images/`.

---

## 🛠️ 8. Panduan Ekspor & Penyajian

* **Format Master:** Microsoft PowerPoint (`.pptx`) / Google Slides / Keynote dengan rasio `16:9`.
* **Distribusi ke Mahasiswa:** Simpan sebagai berkas **PDF Beresolusi Tinggi (*Print Quality*)** agar tata letak font dan kontur ilustrasi tetap tajam pada semua perangkat.
* **Integrasi Tautan:** Sertakan tombol badge `Open in Colab` pada slide praktikum yang menautkan langsung ke notebook GitHub.

---
**Teknik Informatika — Universitas Jenderal Achmad Yani (UNJANI)**  
*Dokumen Standar Desain Bahan Ajar & Presentasi Perkuliahan 2026*
