# Capstone Project 2 

### Created By : Nurdiansyah
Repository ini merupakan salah satu proses dari program Bootcamp Data Science Purwadhika Digital School ini

Dataset source :https://github.com/Nurdiansyah0/Capstone2/blob/main/Jupyter/Supermarket%20Customers.csv

## Bacground Overview
<h1 style="font-size:200%"> <center> Supermarket Customer Segementation</center></h1>
<hr>


<div style="text-align: center;">
    <img src="../img/images.jpeg" alt="Description of the image" />
</div>



Sebagai jantung kehidupan sehari-hari, supermarket memiliki peran krusial dalam memenuhi aspirasi konsumen. <br>Untuk terus memanjakan pelanggan setia dan menarik minat yang lebih luas.<br>**Sebagai Data Scientist** kita bertugas membuat Sebuah supermarket berkomitmen untuk memahami secara mendalam preferensi dan perilaku belanja mereka. Dengan demikian, pengelola supermarket dapat merancang pengalaman belanja yang sesuai, memenuhi ekspektasi, dan menciptakan loyalitas yang mendalam.

## Business Understanding
Pada Langkah business understanding kami ingin memahami permasalahan business yang dimiliki oleh perusahaan dan menentukan tujuan dari hasil analysis ini.
- Memahami pola belanja: Mengidentifikasi produk apa saja yang sering dibeli, waktu pembelian, dan jumlah pembelian.
- Mengetahui faktor yang mempengaruhi keputusan pembelian: Memahami faktor-faktor seperti harga, merek, kualitas produk, promosi, dan kenyamanan belanja yang mempengaruhi pilihan konsumen.
- Mengidentifikasi segmen pasar: Membagi pelanggan menjadi kelompok-kelompok berdasarkan karakteristik dan preferensi yang berbeda untuk dapat memberikan penawaran yang lebih personal
- Meningkatkan pengalaman belanja: Menyarankan produk yang sesuai dengan memahami apa yang dibutuhkan pelanggan,

## Goal and Strategy
Setelah mengetahui permasalahan business nya, kita bisa menargetkan tujuan kita yaitu: 
1. Meningkatkan repurchasing dan juga untuk menimalisir potensial lost customer.
2. Melakukan penawaran Substitusi atau Komplementary dengan produk-produk yang saling melengkapi atau saling menggantikan <br>
tindakan ini dapat berguna untuk mendorong pemasaran produk yang cenderung rendah.
3. Menambahkan pengiklanan yang berkaitan dengan kesehatan sehingga MntFruit tejual lebih banyak , mengingat segmentasi usia pelanggan diatas 40 tahun.
4. Memberikan insight dan rekomendasi yang dapat membantu tim bisnis dan tim pemasaran untuk meningkatkan repurchasing. 

## Data Overview
Data Ecommerce Olist yang kami analysis ini berasal dari Purwadhika, data ini terdiri dari 29 Kolom dan 2220 baris
!


## Data Overview dan EDA
Sebelum melewati data cleaning, Penting untuk mempertahankan data asli karena ini data yang paling menggambarkan situasi sebenarnya di EDA dan Insight ini kami akan menjabarkan hasil dari analyisis yang sudah kami lakukan.

### Kesimpulan awal
Sebelum dilakukan pemodelan machine learning lebih lanjut <br>kita dapat menarik kesimpulan sementara guna membandingkan hasil pemodelan machine laearning yang akan kita buat nanti.

- Kelahiran termuda ada di tahun 1996
- Kolom Income memiliki data Outlier 
- Usia pelanggan terbanyak adalah antara 41 tahun s/d 50 tahun
- Paling banyak Total belanja adalah $2525
- Produk `MntWines` paling banyak terjual untuk individu dengan pendidikan PhD
- produk `MntFruits` adalah yang paling sedikit terjual dengan mayoritas pembeli berpendidikan Bachelor
- individu yang berpendidikan High School cenderung lebih sedikit dalam berbelanja produk.
- aktivitas perbelanjaan terbanyak dilakukan di toko

## Business Insight, recommendation
Analisis data awal menunjukkan bahwa pelanggan berusia 41-50 tahun merupakan kelompok terbesar dengan rata-rata total belanja sebesar $2525. Pelanggan dengan pendidikan PhD cenderung lebih memilih produk MntWines, sementara pelanggan dengan pendidikan Bachelor lebih menyukai produk MntFruits. Namun, terdapat outlier pada kolom Income yang perlu diteliti lebih lanjut.

Saran Awal:

Segmentasi: Lakukan segmentasi pelanggan berdasarkan usia, pendidikan, total belanja, dan preferensi produk untuk memberikan penawaran yang lebih personal.
Personalisasi: Implementasikan sistem rekomendasi produk berdasarkan riwayat pembelian pelanggan.
Bundling: Buat paket produk yang menggabungkan MntFruits dengan produk sehat lainnya untuk meningkatkan penjualan MntFruits.
Uji Coba: Lakukan uji coba kampanye pemasaran yang berbeda pada segmen pelanggan yang berbeda untuk mengukur efektivitasnya.
Langkah Selanjutnya:

Analisis Mendalam: Lakukan analisis mendalam terhadap outlier pada kolom Income untuk memahami penyebabnya dan dampaknya terhadap model.
Visualisasi Data: Gunakan visualisasi data untuk mempermudah pemahaman pola dan tren dalam data.
Pemodelan Prediktif: Kembangkan model prediksi untuk memprediksi perilaku pembelian pelanggan di masa depan.
Dengan perbaikan-perbaikan ini, diharapkan Anda dapat memperoleh pemahaman yang lebih baik tentang data Anda dan merancang strategi pemasaran yang lebih efektif."

Catatan: Saran-saran di atas bersifat umum dan dapat disesuaikan dengan kasus spesifik Anda. Selalu pastikan untuk menggabungkan pemahaman domain bisnis Anda dengan hasil analisis data untuk mengambil keputusan yang tepat.
<h1 style="font-size:200%"> <center> Supermarket Customer Segementation</center></h1>
<hr>


<div style="text-align: center;">
    <img src="../img/output.png" alt="Description of the image" />
</div>




## Conclusion
Analisis data penjualan menunjukkan bahwa pelanggan berusia 30-40 tahun merupakan segmen pasar yang paling potensial. Produk Wines dan Meat merupakan produk paling populer dan sering dibeli bersama. Pelanggan cenderung lebih sering melakukan pembelian pada akhir pekan dan pada saat musim liburan. Selain itu, promosi diskon terbukti efektif dalam meningkatkan penjualan.

Berdasarkan temuan ini, disarankan untuk fokus pada pengembangan produk baru yang melengkapi produk Wines dan Meat. Selain itu, perlu ditingkatkannya kampanye pemasaran digital yang ditargetkan pada segmen pelanggan berusia 30-40 tahun. Dengan demikian, diharapkan dapat meningkatkan penjualan dan pangsa pasar perusahaan."


