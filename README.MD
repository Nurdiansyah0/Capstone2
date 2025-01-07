# Capstone Project 2 - Supermarket Customer Segmentation

## Created By: Nurdiansyah

Repository ini merupakan salah satu proses dari program Bootcamp Data Science Purwadhika Digital School.

## Dataset

**Sumber:** https://github.com/Nurdiansyah0/Capstone2/blob/main/Jupyter/Supermarket%20Customers.csv

Dataset ini berisi informasi tentang pelanggan supermarket, meliputi demografi, perilaku pembelian, dan interaksi dengan kampanye pemasaran. 

**Kolom-kolom penting:**

* `ID`: ID unik pelanggan
* `Year_Birth`: Tahun kelahiran pelanggan
* `Education`: Tingkat pendidikan pelanggan
* `Marital_Status`: Status pernikahan pelanggan
* `Income`: Pendapatan tahunan pelanggan
* `MntWines`: Jumlah uang yang dihabiskan untuk wine dalam 2 tahun terakhir
* `MntFruits`: Jumlah uang yang dihabiskan untuk buah dalam 2 tahun terakhir
* ...

## Background Overview

Supermarket memiliki peran penting dalam memenuhi kebutuhan sehari-hari konsumen. Untuk meningkatkan kepuasan pelanggan dan menarik pelanggan baru, supermarket perlu memahami preferensi dan perilaku belanja pelanggan. Dengan memanfaatkan data, kita dapat melakukan segmentasi pelanggan, personalisasi penawaran, dan optimasi strategi pemasaran.

## Business Understanding

**Permasalahan Bisnis:**

* Kurangnya pemahaman tentang pola belanja pelanggan.
* Kesulitan dalam mengidentifikasi faktor-faktor yang mempengaruhi keputusan pembelian.
* Belum optimalnya segmentasi pasar dan personalisasi penawaran.

**Tujuan Analisis:**

* Memahami pola belanja pelanggan, termasuk produk yang sering dibeli, waktu pembelian, dan jumlah pembelian.
* Mengetahui faktor-faktor yang mempengaruhi keputusan pembelian, seperti harga, merek, kualitas produk, promosi, dan kenyamanan belanja.
* Mengidentifikasi segmen pasar berdasarkan karakteristik dan preferensi pelanggan.
* Meningkatkan pengalaman belanja pelanggan dengan memberikan rekomendasi produk yang relevan.

## Goal and Strategy

**Tujuan:**

1. Meningkatkan _repurchasing_ dan meminimalisir potensi _lost customer_.
2. Melakukan penawaran produk substitusi atau komplementer.
3. Meningkatkan penjualan produk `MntFruit` dengan menambahkan pengiklanan yang berkaitan dengan kesehatan.
4. Memberikan insight dan rekomendasi kepada tim bisnis dan tim pemasaran.

**Strategi:**

* Melakukan segmentasi pelanggan berdasarkan usia, pendidikan, total belanja, dan preferensi produk.
* Menerapkan sistem rekomendasi produk.
* Membuat paket produk yang menggabungkan `MntFruits` dengan produk sehat lainnya.
* Melakukan uji coba kampanye pemasaran yang berbeda pada segmen pelanggan yang berbeda.

## Data Overview

Dataset yang digunakan terdiri dari 2220 baris dan 29 kolom. 

| Kolom | Tipe Data | Deskripsi |
|---|---|---|
| ID | Numerik | ID unik pelanggan |
| Year_Birth | Numerik | Tahun kelahiran pelanggan |
| Education | Kategorikal | Tingkat pendidikan pelanggan |
| ... | ... | ... |

**Statistik Deskriptif:**

*  Rata-rata `Income`: $ ...
*  Minimum `Income`: $ ...
*  Maksimum `Income`: $ ...

## Data Overview dan EDA

**Proses EDA:**

1.  Membersihkan data dengan menangani _missing values_ dan data duplikat.
2.  Melakukan analisis univariat untuk memahami distribusi setiap variabel.
3.  Melakukan analisis bivariat untuk mengidentifikasi hubungan antar variabel.
4.  Melakukan analisis multivariat untuk mengidentifikasi pola yang lebih kompleks.

**Visualisasi Data:**

*  [![Distribusi Usia Pelanggan](../img/distribusi_usia.png)](../img/distribusi_usia.png)
*  [![Hubungan antara Income dan Total Belanja](../img/income_vs_total_belanja.png)](../img/income_vs_total_belanja.png)

**Kesimpulan Awal:**

*  ...
*  Terdapat outlier pada kolom `Income`. Outlier ini diidentifikasi dengan menggunakan metode ... 
*  ...

## Business Insight and Recommendation

*  **Segmentasi:** Lakukan segmentasi pelanggan berdasarkan ...  Gunakan algoritma clustering seperti K-Means untuk mengelompokkan pelanggan.
*  **Personalisasi:** Implementasikan sistem rekomendasi produk berbasis _collaborative filtering_ atau _content-based filtering_.
*  **Bundling:** Buat paket produk "Sehat dan Lezat" yang menggabungkan `MntFruits` dengan produk yogurt, granola, dan madu. Tawarkan diskon khusus untuk paket ini.
*  **Uji Coba:** Lakukan A/B testing untuk membandingkan efektivitas kampanye pemasaran digital yang berbeda, misalnya dengan menargetkan iklan berdasarkan usia dan preferensi produk.

## Conclusion


## Tableau Link

[Dashboard Tableau](link_tableau_anda)

Dashboard ini menampilkan visualisasi interaktif dari data penjualan, segmentasi pelanggan, dan tren pembelian.