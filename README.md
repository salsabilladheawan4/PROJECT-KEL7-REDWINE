# Projek Statistika dan Probabilitas - Kelompok 7 (3TIE)

Analisis Hubungan Kadar Alkohol dan Keasaman Volatil terhadap Kualitas Anggur Merah Vinho Verde sebagai Dasar Penyusunan Aturan Fuzzy

Politeknik Caltex Riau - Program Studi Teknik Informatika - T.A 2025/2026

## Anggota Kelompok

| Nama | NIM |
| :--- | :--- |
| Salsabilla Dheawan Shenza | 2455301173 |
| Farhan Gusri Fadhilah | 2455301066 |
| Gebi Rovando Rahmanda | 2455301072 |
| Zikra Mahiza Wafiq | 2455301210 |

## Deskripsi

Repository ini berisi data dan program Python untuk Tahap 3 projek, yaitu deskripsi data, statistika deskriptif, probabilitas empiris, dan visualisasi data pada dataset Red Wine Quality (1.599 sampel, 12 variabel). Variabel utama: `alcohol`, `volatile acidity`, dan `quality`.

## Sumber Data

Data sekunder: [Red Wine Quality - Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009) (Cortez et al., 2009). Data disimpan pada `3TIE_07_WineQuality-Red.xlsx` (sheet `Dataset`) tanpa mengubah nilai asli.

## Struktur Repository

```text
.
├── PROJECT_KEL7_REDWINE.ipynb      # program analisis (statistik deskriptif, visualisasi) menggunakan Google Colab
└── 3TIE_07_WineQuality-Red.xlsx    # dataset utama
**
Cara Menjalankan**
Program ini dibuat menggunakan Google Colab. Untuk menjalankannya:

Buka file PROJECT_KEL7_REDWINE.ipynb langsung di GitHub.

Klik tombol "Open in Colab" di bagian atas (jika tersedia), atau unduh file tersebut dan buka melalui Google Colab.

Pastikan file dataset 3TIE_07_WineQuality-Red.xlsx diunggah ke session storage Colab sebelum menjalankan kode.
**
Keluaran Program**
Pemeriksaan data (dimensi, nilai kosong, tipe data)

Statistika deskriptif: mean, median, modus, min, max, standar deviasi

Distribusi frekuensi skor quality

Identifikasi pencilan (outlier) menggunakan Boxplot

Grafik: diagram batang quality, histogram alcohol, dan histogram pH

**Referensi**
Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Modeling wine preferences by data mining from physicochemical properties. Decision Support Systems, 47(4), 547-553.
