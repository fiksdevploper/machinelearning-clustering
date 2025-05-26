# Segmentasi Pelanggan Menggunakan KMeans Clustering

Proyek ini berfokus pada segmentasi pelanggan mal berdasarkan perilaku dan data pembelian mereka untuk memberikan wawasan bagi strategi pemasaran. Analisis dilakukan menggunakan algoritma KMeans clustering.

## Gambaran Umum

Segmentasi pelanggan adalah teknik penting bagi bisnis untuk memahami basis pelanggan mereka dengan lebih baik. Dengan mengelompokkan pelanggan ke dalam segmen yang berbeda, strategi pemasaran yang ditargetkan dapat dikembangkan untuk meningkatkan keterlibatan pelanggan dan meningkatkan penjualan. Proyek ini menggunakan dataset "Mall Customer Segmentation Data" dari Kaggle untuk mengidentifikasi segmen pelanggan di dalam pusat perbelanjaan.

## Dataset

Dataset yang digunakan dalam proyek ini adalah "Mall Customer Segmentation Data," diperoleh dari [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

### Deskripsi

Dataset ini dibuat untuk tujuan pembelajaran konsep segmentasi pelanggan, juga dikenal sebagai analisis keranjang pasar. Ini mencakup informasi dasar tentang pelanggan mal yang diperoleh melalui kartu keanggotaan. Kolom-kolom dalam dataset adalah:

-   **CustomerID:** ID unik yang diberikan kepada setiap pelanggan
-   **Gender:** Jenis kelamin pelanggan
-   **Age:** Usia pelanggan
-   **Annual Income (k$):** Pendapatan tahunan pelanggan dalam ribuan dolar
-   **Spending Score (1-100):** Skor yang diberikan kepada pelanggan oleh mal berdasarkan perilaku pelanggan dan data pengeluaran

### Pernyataan Masalah

Manajemen mal bertujuan untuk memahami pelanggannya dengan lebih baik, khususnya mengidentifikasi kelompok pelanggan (target pelanggan) yang dapat dengan mudah ditargetkan. Pemahaman ini akan memungkinkan tim pemasaran untuk merencanakan strategi yang tepat dan efektif.

## Metodologi

Proyek ini menggunakan algoritma KMeans clustering untuk mengelompokkan pelanggan berdasarkan pendapatan tahunan dan skor pengeluaran mereka. Jumlah cluster optimal ditentukan menggunakan Metode Elbow. Analisis ini membantu memvisualisasikan dan menafsirkan segmen pelanggan yang berbeda, memberikan wawasan yang dapat ditindaklanjuti untuk tim pemasaran mal.

## File

-   `clustering.ipynb`: Jupyter Notebook yang berisi kode untuk memuat data, eksplorasi, pra-pemrosesan, clustering, dan visualisasi.
-   `Mall_Customers.csv`: Dataset yang digunakan untuk analisis.

## Library yang Digunakan

-   pandas
-   matplotlib
-   yellowbrick
-   scikit-learn (sklearn)

## Pengaturan

1.  Kloning repositori:

    ```bash
    git clone <repository_url>
    ```

2.  Pastikan Anda telah menginstal Python 3.x.

3.  Instal library yang diperlukan:

    ```bash
    pip install pandas matplotlib scikit-learn yellowbrick
    ```

4.  Jalankan Jupyter Notebook `clustering.ipynb` untuk mereproduksi analisis.

## Hasil

Analisis menghasilkan segmen pelanggan yang berbeda, yang dapat digunakan oleh tim pemasaran untuk menyesuaikan strategi mereka. Misalnya, segmen mungkin mencakup:

-   Pendapatan Tinggi, Skor Pengeluaran Tinggi: Target untuk produk premium.
-   Pendapatan Rendah, Skor Pengeluaran Tinggi: Potensi untuk penawaran promosi.
-   Pendapatan Tinggi, Skor Pengeluaran Rendah: Perlu lebih dilibatkan.

## Kesimpulan

Proyek ini menyediakan metodologi yang jelas untuk segmentasi pelanggan menggunakan KMeans clustering. Wawasan yang diperoleh dapat membantu mal mengembangkan kampanye pemasaran yang lebih efektif, yang mengarah pada peningkatan kepuasan pelanggan dan pendapatan.

## Penulis

fiksdeveloper | dicoding academy

## Ucapan Terima Kasih

-   Dataset "Mall Customer Segmentation Data" yang disediakan oleh Kaggle.
-   Para pengembang library Python yang digunakan dalam proyek ini.
