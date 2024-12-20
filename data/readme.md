
### **Data**

Data yang digunakan dalam penelitian ini merupakan data sekunder yang diperoleh dari **Badan Pusat Statistik Provinsi Sulawesi Selatan** dan dapat diakses melalui [https://sulsel.bps.go.id](https://sulsel.bps.go.id).

#### **Deskripsi Data**
Data ini mencakup informasi yang berkaitan dengan **Produk Domestik Regional Bruto (PDRB)** serta beberapa variabel ekonomi di provinsi Sulawesi Selatan.

##### Variabel Respon:
- **Produk Domestik Regional Bruto (PDRB)**: PDRB tahun 2011-2019 untuk 24 kabupaten/kota di Sulawesi Selatan.

##### Variabel Prediktor:
- **Penduduk Miskin**: Jumlah penduduk miskin di masing-masing kabupaten/kota.
- **Pengeluaran per Kapita**: Pengeluaran rata-rata per kapita di kabupaten/kota.
- **Indeks Pembangunan Manusia (IPM)**: Indeks yang menggambarkan tingkat pembangunan dalam suatu wilayah.

## Metode Analisis

Penelitian ini menggunakan software statistik **STATA 14** dan **Microsoft Excel** untuk menyelesaikan proses perhitungan. Adapun langkah-langkah yang dilakukan dalam penelitian ini berdasarkan tujuan penelitian adalah sebagai berikut:

### **1. Estimasi Parameter Model Regresi Panel Dinamis dengan Pendekatan GMM Blundell-Bond**
Untuk mencapai tujuan pertama, langkah-langkah yang dilakukan adalah sebagai berikut:
- **Penguraian Model**: Menguraikan model persamaan GMM Blundell-Bond berdasarkan Persamaan.
- **Matriks Variabel Instrumen**: Membentuk matriks variabel instrumen GMM Blundell-Bond sesuai dengan Persamaan.
- **Momen Kondisi Populasi**: Memformulasikan momen kondisi populasi sesuai dengan model Persamaan.
- **Momen Kondisi Sampel**: Memformulasikan momen kondisi sampel sesuai dengan model Persamaan.
- **Fungsi Kuadratik Model Sampel**: Membentuk fungsi kuadratik model sampel sesuai dengan model Persamaan dengan matriks pembobot berukuran L×L. Matriks pembobot dihitung menggunakan rumus Persamaan dan Persamaan.
- **Penguraian dan Minimasi Fungsi Kuadrat**: Melakukan penguraian dan meminimumkan fungsi kuadrat untuk mendapatkan hasil estimasi parameter **δ** dan **β**.

### **2. Mengetahui Faktor-Faktor yang Mempengaruhi Pertumbuhan Ekonomi**
Untuk mencapai tujuan kedua, langkah-langkah yang dilakukan adalah sebagai berikut:
- **Deskripsi Variabel**: Mendeskripsikan variabel-variabel yang digunakan dalam penelitian.
- **Pemodelan Regresi Panel Dinamis**: Melakukan pemodelan regresi panel dinamis dengan pendekatan GMM Blundell-Bond pada data pertumbuhan ekonomi di Sulawesi Selatan Tahun 2011-2019.
- **Uji Signifikansi Parameter**: Melakukan pengujian signifikansi parameter model GMM Blundell-Bond secara simultan menggunakan uji Wald dan uji signifikansi parsial menggunakan uji Z.
- **Pengujian Spesifikasi Model**: Melakukan pengujian spesifikasi pada model GMM Blundell-Bond menggunakan uji Sargan dan uji Arellano-Bond.
- **Interpretasi Hasil**: Menginterpretasikan hasil yang diperoleh dengan memperhatikan efek jangka pendek (short-run multiplier) dan efek jangka panjang (long-run multiplier) setiap variabel prediktor.
- **Penarikan Kesimpulan**: Melakukan penarikan kesimpulan berdasarkan hasil analisis.

## Akses Data
Data lengkap untuk analisis ini dapat diunduh dari situs resmi **Badan Pusat Statistik Provinsi Sulawesi Selatan** di [https://sulsel.bps.go.id](https://sulsel.bps.go.id).
