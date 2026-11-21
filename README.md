# Pengelompokan dan Klasifikasi Transaksi

Proyek Dicoding oleh Ilham Jaya Saputra. Tahap pertama mengelompokkan transaksi dengan K-Means dan mengeksplorasi reduksi dimensi menggunakan PCA. Tahap kedua menggunakan label klaster hasil pengelompokan sebagai target klasifikasi.

## Urutan notebook

1. [Pengelompokan transaksi](%5BClustering%5D_Submission_Akhir_BMLP_Ilham_Jaya_Saputra.ipynb). Mulai di sini untuk melihat eksplorasi data dan pembentukan klaster. Berkas `data_clustering.csv` dan `data_clustering_inverse.csv` menyimpan hasil tahap ini.
2. [Klasifikasi label klaster](%5BKlasifikasi%5D_Submission_Akhir_BMLP_Ilham_Jaya_Saputra.ipynb). Notebook membaca `data_clustering_inverse.csv`, memisahkan kolom `Target` dari fitur, lalu membandingkan Decision Tree dan Random Forest.

Laporan evaluasi Random Forest mencatat akurasi 0,99 pada 389 baris uji. Angka itu mengukur seberapa baik model memprediksi label klaster dari tahap sebelumnya, bukan seberapa akurat klaster itu terhadap kategori bisnis yang diberi label secara terpisah.

[Proyek pengelompokan transaksi di portofolio Ilham Jaya Saputra](https://www.ilhamjayas.my.id/#pc-transaction)
