# Analisis dan Transformasi Data Pelanggan Supermarket

## Ringkasan

Repositori ini mendokumentasikan proses analisis dan transformasi data yang dilakukan pada dataset `Supermarket Customers`. Tujuan utama dari analisis ini adalah untuk memperoleh pemahaman yang lebih mendalam tentang karakteristik, perilaku, dan preferensi pelanggan supermarket.  Informasi ini selanjutnya digunakan untuk menghasilkan rekomendasi yang dapat ditindaklanjuti bagi manajemen dalam rangka mengoptimalkan strategi pemasaran dan penjualan, serta meningkatkan kinerja bisnis secara keseluruhan.

## Dataset

Dataset `Supermarket Customers` yang digunakan dalam analisis ini memuat informasi komprehensif tentang 2240 pelanggan supermarket. Data yang terkandung di dalamnya meliputi:

* **Demografi:** Usia, tingkat pendidikan, status perkawinan.
* **Ekonomi:** Pendapatan rumah tangga.
* **Pembelian:** Pengeluaran untuk berbagai kategori produk (wine, daging, ikan, buah, manisan, emas).
* **Perilaku:** Riwayat pembelian, preferensi saluran pembelian (online, offline, katalog), frekuensi kunjungan website.
* **Respons Pemasaran:**  Partisipasi dalam kampanye pemasaran.

## Metodologi Analisis

Analisis data dilakukan melalui beberapa tahapan:

1. **Analisis Deskriptif:**  Memberikan gambaran umum tentang dataset, meliputi  statistik deskriptif  dan visualisasi data untuk mengidentifikasi  pola awal.

2. **Analisis Demografi:** Menelaah  distribusi  karakteristik demografis pelanggan,  seperti usia, tingkat pendidikan, dan status perkawinan, untuk  mengidentifikasi segmen pasar potensial.

3. **Analisis Pengeluaran:** Menghitung rata-rata pengeluaran per pelanggan  untuk setiap kategori produk  guna  memahami  preferensi produk dan  potensi pendapatan.

4. **Segmentasi Pelanggan:**  Mengelompokkan pelanggan ke dalam segmen yang berbeda berdasarkan pendapatan dan  tipe rumah tangga (ada tidaknya anak)  untuk  memungkinkan strategi pemasaran yang lebih terarah.

5. **Analisis Statistik:**  Menerapkan uji Kruskal-Wallis,  uji non-parametrik yang membandingkan dua atau lebih kelompok data independen, untuk  menentukan apakah ada perbedaan yang signifikan dalam  pola pengeluaran antar segmen pelanggan.

6. **Transformasi Data:**  Melakukan  preprocessing data  untuk meningkatkan kualitas dan  kecocokan data untuk analisis lebih lanjut, meliputi:

    * **Rekayasa Fitur:**  Membuat variabel baru yang relevan, seperti `Age`.
    * **Pengelompokan Data Kategorikal:**  Menyederhanakan variabel `Marital_Status`  menjadi dua kategori: "Married" dan "Single".
    * **One-Hot Encoding:**  Mengubah variabel kategorikal `Education` menjadi representasi numerik  yang  cocok untuk  model machine learning.
    
## Temuan Utama

* **Perbedaan Pengeluaran:**  Terdapat perbedaan yang signifikan secara statistik dalam pengeluaran pelanggan  untuk  wine,  produk daging, dan  produk ikan, yang  menunjukkan adanya  variasi  preferensi produk  antar segmen.

* **Faktor yang Mempengaruhi:**  Pendapatan, keberadaan anak, dan tingkat pendidikan merupakan  faktor-faktor penting yang  mempengaruhi pengeluaran pelanggan  untuk berbagai kategori produk.

* **Segmen Bernilai Tinggi:**

    * Pelanggan dengan pendapatan tinggi dan berpendidikan tinggi  cenderung  mengalokasikan  lebih banyak pengeluaran  untuk  wine dan produk daging.
    *  Pelanggan tanpa anak di rumah menunjukkan  pola pengeluaran yang serupa, dengan  fokus pada  wine dan  produk daging.

* **Pelanggan dengan Anak:**  Cenderung  memprioritaskan  pembelian produk ikan.


## Rekomendasi

Berdasarkan temuan  ini,  kami mengajukan  rekomendasi berikut  bagi manajemen supermarket:

* **Segmentasi Pelanggan yang Lebih Lanjut:**  Melakukan segmentasi pelanggan yang lebih terperinci  dengan  mempertimbangkan  faktor-faktor  demografi,  ekonomi, dan  perilaku.

* **Strategi Pemasaran yang Terarah:** 

    * Mengembangkan strategi pemasaran yang disesuaikan dengan karakteristik dan kebutuhan  setiap segmen pelanggan.
    * Menawarkan promosi dan  penawaran khusus  untuk produk  wine dan  daging kepada  segmen  berpendapatan tinggi dan  berpendidikan tinggi.
    *  Menerapkan strategi penetapan harga yang kompetitif  untuk produk ikan  guna menarik  pelanggan dengan anak.

* **Bundling Produk:** 

    *  Merancang paket bundling produk  yang  menarik,  seperti  wine dan  daging,  untuk  meningkatkan penjualan  dan  nilai transaksi.
    * Menawarkan bundling produk ikan  dengan produk pelengkap  (sayuran, bumbu masak)  untuk  meningkatkan  kenyamanan  dan  nilai bagi pelanggan.

* **Pengembangan Produk dan Layanan:** 

    *  Melakukan riset pasar  untuk  mengidentifikasi  peluang  pengembangan produk dan layanan baru  yang  memenuhi  kebutuhan  dan  preferensi  segmen pelanggan yang berbeda.

* **Analisis Data Berkelanjutan:**  Memanfaatkan analisis data  secara  berkelanjutan  untuk  memantau  perubahan  tren pasar,  perilaku pelanggan, dan  efektivitas  strategi pemasaran.


## Struktur Repositori

* `Supermarket Customers.csv`: Dataset asli dalam format CSV.
* `Supermarket Customers Transformed.csv`: Dataset yang telah ditransformasi  dalam format CSV.
* `README.md`:  File dokumentasi ini.
* `analisis_data.ipynb`:  (Opsional) Notebook Jupyter yang berisi kode dan  dokumentasi analisis data.


## Tableau
https://public.tableau.com/views/Book1_17361672679150/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
