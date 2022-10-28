# EDA-Pakistan-s-Largest-Ecommerce-Dataset
Folder ini berisi Analisis Mengenai Dataset "Pakistan's Largest Ecommerce"

# Latar Belakang
Kumpulan data pesanan E-commerce terbesar di Pakistan. Dataset ini berisi setengah juta catatan transaksi dari bulan Juli 2016 hingga Agustus 2018. Data ini dikumpulkan dari berbagai pedagang di E-commerce sebagai bagian dari studi penelitian.

## Pernyataan Masalah
Ingin mengetahui performa penjualan perusahaan E-commerce terbesar di Pakistan, dengan informasi tersebut diharapkan dapat membantu meningkatkan keuntungan penjualan bagi perusahaan E-commerce tersebut.
# Data
Dataset ini berisi rincian informasi dari setengah juta pesanan E-commerce di Pakistan dari bulan Juli 2016 - Agustus 2018. Untuk menjawab pertanyaan di atas, saya akan menganalisa data pesanan yang telah dikumpulkan ini. Dataset dapat diakses melalui link https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset. 

Terdapat 26 kolom di dalam dataset "Pakistan Largest Ecommerce Dataset.csv", diantaranya adalah:

1. item_id: Nomor unik untuk setiap barang
1. status: Status barang yang dipesan
1. created_at: Tanggal saat pemesanan barang
1. sku: Stock keeping unit, 
1. price: Harga tiap barang
1. qty_ordered: Jumlah barang yang dipesan
1. grand_total: Jumlah harga yang dibayar oleh customer 
1. increment_id: Kode struk transaksi
1. category_name_1: Kategori barang
1. sales_commission_code: Kode komisi penjualan
1. discount_amount: Potongan harga yang diberikan
1. payment_method: Metode pembayaran
1. Working Date: Jam kerja
1. BI Status: Bisnis Income Status
1. MV: Hasil perkalian kolom price dengan qty_ordered
1. Year: Tahun costumer bergabung
1. Month: Bulan customer bergabung
1. Customer Since: Informasi menganai tahun dan bulan customer bergabung
1. M-Y: Informasi mengenai bulan dan tahun saat transaksi berlangsung
1. FY: Tahun Fiskal Perusahaan
1. Customer ID: Nomor unik untuk setiap customer
1. Unnamed: 21: Kolom kosong
1. Unnamed: 22: Kolom kosong
1. Unnamed: 23: Kolom kosong
1. Unnamed: 24: Kolom kosong
1. Unnamed: 25: Kolom kosong

## Data Cleaning
Dilakukan cleaning data dengan mengatasi menghapus data duplikat,menangani anomali-anomali data, menangani missing value, memperbaiki tipe data yang sesuai, dan membuat kolom baru.

# Kesimpulan:
Berdasarkan hasil analisis mengenai dataset "Pakistan Largest Ecommerce" yang telah dilakukan dapat kita simpulkan bahwa: 
* Dari tahun 2016 hingga tahun 2018 eCommerce di Pakistan mengalami pertumbuhan yang cukup baik
* Rata-rata penjualan tertinggi terjadi di Bulan Juni, dimana saat itu bertepatan dengan Bulan Puasa
* Penjualan tertinggi dan konsumen paling banyak bergabung ke eCommerce ketika **Bulan November**.
* Kategori Mobiles & Tablets menghasilkan penjualan tertinggi dengan total penjualan 2.440.788.000 rupee pakistan dan barang yang paling banyak terjual berasal dari kategori Mobiles & Tablets sebanyak 132.694 barang
* Konsumen yang berbelanja dengan memakai kode komisi hanya 18.5% atau sebanyak 106.737 dari 576.480 orang.
* Metode pembayaran yang paling banyak dipakai pada Ecommerce di Pakistan adalah COD (Cash on Delivery).
* Kategori Mobiles & Tablets menjadi kategori yang penjualannya tertinggi dengan potongan harga hanya 0,6%, sedangkan kateogri Beauty & Grooming menempati urutan ke-8 dari 15 kategori penjualan tertinggi dengan potongan harga 9.3%.

# Rekomendasi:
* Pada kategori yang paling banyak penjualan menandakan barang-tersebut banyak diminati, sebaiknya perbanyak/menambahkan jenis barang dan stock pada kategori tersebut menjadi lebih lengkap lagi, sehingga dapat menarik konsumen baru untuk membeli di eCommerce ini.
* Memberikan reward pada affiliator eCommerce yang telah berhasil mendatangkan pelanggan untuk berbelanja di eCommerce ini dengan tujuan mendatangkan affiliator-affiliator baru sehingga perusahaan dan affiliator sama-sama diuntungkan. Perusahaan mendapatkan keuntungan promosi/iklan sebagai salah satu strategi pemasaran gratis sehingga meminimalkan cost untuk promosi. Affiliator baru jika berhasil mengiklankan dan memikat konsumen hingga berbelanja di eCommerce ini akan mendapatkan komisi.
* Memberikan potongan harga atau potongan ongkos kirim untuk pelanggan yang menggunakan metode pembayaran yang perusahaan inginkan, misal metode pembayaran 'bankalfalah' dengan cara bekerja sama dengan bankalfalah, sehingga perusahaan dan bankalfalah sama-sama dapat diuntungkan. Perusahaan diuntungkan karena tidak perlu membuat tim khusus untuk mengelola *cash receipt* sehingga dapat menekan biaya operasional, dan bagi 'bankalfalah' mendapatkan nasabah baru.
* Untuk menarik konsumen baru untuk berbelanja di eCommerce ini adalah dengan membuat program event yang cocok di Pakistan seperti 'Black Friday' karena pada kenyataannya dengan adanya event tersebut sepertiga dari konsumen yg bergabung merupakan konsumen yang aktif berbelanja di eCommerce ini, dengan diadakan program/event baru diharapkan dapat mendatangkan lebih banyak konsumen baru dan meningkatkan penjualan perusahaan eCommerce.
* Kategori yang tidak begitu menghasilkan penjualan yang tinggi tidak perlu memberikan potongan harga yang besar, karena jika memberikan diskon yg cukup besar bisa jadi perusahaan tidak mendapatkan keuntungan. Pada kenyataannya kategori Mobiles & Tablets yang menjadi kategori menghasilkan penjualan tertinggi tidak memberikan diskonbesar, hanya 0.6%.

Dengan rekomendasi-rekomendasi diatas diharapkan dapat membantu perusahaan eCommerce di Pakistan meningkatkan keuntungan penjualan perusahaan eCommerce.
