# Pemetaan Spasial Ketimpangan Kesejahteraan di Indonesia Menggunakan Big Data Meta Relative Wealth Index (RWI)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Ringkasan Penelitian
Penelitian ini memetakan pola distribusi spasial dan menganalisis tingkat ketimpangan kesejahteraan relatif pada **502 kabupaten/kota** di Indonesia menggunakan *micro-spatial big data* Meta Relative Wealth Index (RWI). Data mentah berbasis titik mikro ($2.4\text{ km} \times 2.4\text{ km}$) sebanyak **115.625 baris** diagregasikan ke tingkat kabupaten/kota untuk menganalisis kesenjangan pembangunan antara Kawasan Barat Indonesia (KBI) dan Kawasan Timur Indonesia (KTI).

---

## 📂 Daftar File & Deskripsi Proyek

| Nama File | Deskripsi / Fungsi |
| :--- | :--- |
| `Jurnal_Ilmiah_Analisis_Kesejahteraan_Rakyat.docx` | Naskah lengkap paper ilmiah berformat IEEE/Sains. |
| `pemetaan.ipynb` | Notebook Python untuk *preprocessing*, pembersihan data, dan agregasi data mentah ke tingkat kabupaten/kota. |
| `hasil_analisis.ipynb` | Notebook Python untuk analisis statistik deskriptif, ekstraksi daerah ekstrem (*top/bottom 10*), dan analisis kawasan. |
| `idn_relative_wealth_index.csv` | Dataset mentah Meta RWI Indonesia (*115.625 baris titik mikro*). |
| `rwi_per_kabupaten.xlsx` | Dataset teragregasi hasil pengolahan (*502 baris kabupaten/kota*). |
| `gadm41_IDN_2.json` | File peta geospasial batas wilayah administrasi kabupaten/kota di Indonesia (GeoJSON). |

---

## 📊 Hasil Utama Penelitian
- **Distribusi Nasional:** Mencong ke kanan (*right-skewed*) dengan rerata **+0.0042** dan nilai tengah (*median*) **-0.1816**. Lebih dari 50% kabupaten/kota berada di bawah rerata nasional.
- **Daerah Ekstrem:**
  - **Skor Tertinggi:** Kota Jakarta Pusat (+1.4122)
  - **Skor Terendah:** Kabupaten Asmat (-0.6722)
- **Ketimpangan Regional:**
  - **Kawasan Jawa:** Rerata RWI tertinggi (**+0.4632**, $N=120$)
  - **Kawasan Maluku & Papua:** Rerata RWI terendah (**-0.3151**, $N=60$)
  - **Kesenjangan Spasial:** Selisih rerata mencapai **0.7783 poin** antara Jawa dan Maluku-Papua.

---

## 👤 Penulis
- **Charlie Da Vinci Ranggi** (NIM: 825230167)
- **Jurusan Sistem Informasi, Fakultas Teknologi Informasi**
- **Universitas Tarumanagara**
