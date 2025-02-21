# Prediksi-marketing-perbankan-berdasarkan-segmentasi-nasabah

## Latar Belakang
   perbankan sedang mengalami kesulitan memilih target nasabah untuk meningkatkan peluang penjualan produknya secara maksimal.Untuk menjawab hal ini, untuk itu diperlukan menganalisis berdasarkan data kampanye pemasaran terakhir yang dilakukan bank dan mengidentifikasi pola yang akan membantu bank dalam menemukan kesimpulan untuk mengembangkan strategi masa depan
   
## Tujuan Penelitian
   Mengembangkan model machine learning yang mampu memprediksi apakah nasabah akan membeli produk atau tidak
   
## Rumusan Masalah
1. Bagaimana memprediksi target pelanggan berdasarkan deposit?
2. Bagaimana mengembangkan model untuk memprediksi target pelanggan yan efektif dan efisien berdasarkan deposit?
   
## Data yang akan dipakai
   Data yang digunakan segmentasi customer bank di kaggle.Sumber data :Bank Marketing Dataset"https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset". Deskripsi data segmentasi customer bank adalah sebagsi berikut :
   1. Age (Usia): Usia nasabah.
   2. Job (Pekerjaan): Pekerjaan yang dilakukan oleh nasabah.
   3. Marital (Status Pernikahan): Apakah nasabah menikah atau tidak.
   4. Education (Pendidikan): Tingkat pendidikan yang telah diselesaikan..
   5. Default: Apakah nasabah masuk dalam daftar default atau tidak.
   6. Balance (Saldo): Sisa saldo di rekening nasabah.
   7. Housing (Hunian): Informasi tentang hunian nasabah.
   8. Loan (Pinjaman): Apakah nasabah memiliki pinjaman sebelumnya atau tidak.
   9. Contact (Kontak): Sumber informasi ini.
   10.Day (Tanggal): Tanggal hari ini.
   11. Month (Bulan): Bulan.
   12. Duration (Durasi): Jumlah hari sejak terakhir kali nasabah dihubungi.
   13. Campaign (Kampanye Pemasaran): Kampanye pemasaran yang sedang berlangsung.
   14. Pdays: Jumlah hari yang berlalu setelah klien terakhir kali dihubungi.
   15. Previous (Respon Sebelumnya): Respon sebelumnya dari nasabah.
   16. Poutcome (Hasil Kampanye Sebelumnya): Hasil dari kampanye pemasaran sebelumnya.
   17. deposit(Tabungan): Ya atau tidak (variabel target).

## Metode
Metode yang digunakan untuk menyelesaikan masalah ini adalah metode supervised learning dengan jenis label klasifikasi. Dengan menggunakan pemodelan   randomforest,svm,Logic regression  dan naive bayes, KNN,ACROS.
Langkah-langkah yang akan diambil meliputi:
1. Persiapan data: Mengimpor dataset
2. Mengeksplore data: menglihat data, menangani missing values, melakukan visualisasi data.
3. Mengcleaning data: Membersihkan data yang tidak diperlukan, mengubah data yang tidak valid menjadi valid
4. Pelatihan model: Melatih model menggunakan data train dan testing.
5. Evaluasi model: Mengevaluasi kinerja model menggunakan metrik evaluasi yang relavan
6. model selection: Mengoptimalkan model dan melakukan penyetelan hyperparameter jika diperlukan untuk meningkatkan kinerja.
7. inclusion :Membuat kesimpulan hasil akhir data semua proses yang sudah dilakukan
