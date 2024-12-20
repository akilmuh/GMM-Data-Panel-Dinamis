# Data untuk Proyek Dynamic-Panel-Data-GMM

## Sumber Data
Data yang digunakan dalam proyek ini merupakan data sekunder yang diperoleh dari **Badan Pusat Statistik Provinsi Sulawesi Selatan** dan dapat diakses melalui [https://sulsel.bps.go.id](https://sulsel.bps.go.id).

## Deskripsi Data
Data ini mencakup informasi yang berkaitan dengan **Produk Domestik Regional Bruto (PDRB)** serta beberapa variabel ekonomi di provinsi Sulawesi Selatan.

### Variabel Respon:
- **Produk Domestik Regional Bruto (PDRB)**: PDRB tahun 2011-2019 untuk 24 kabupaten/kota di Sulawesi Selatan.

### Variabel Prediktor:
- **Penduduk Miskin**: Jumlah penduduk miskin di masing-masing kabupaten/kota.
- **Pengeluaran per Kapita**: Pengeluaran rata-rata per kapita di kabupaten/kota.
- **Indeks Pembangunan Manusia (IPM)**: Indeks yang menggambarkan kualitas hidup berdasarkan beberapa indikator sosial dan ekonomi.

## Identifikasi Variabel

### 1. **Variabel Respon (Y):**
   - **Produk Domestik Regional Bruto (PDRB)**:
     - **Tipe Data**: Numerik  
     - **Deskripsi**: Variabel respon dalam penelitian ini adalah jumlah **Produk Domestik Regional Bruto (PDRB)** untuk setiap kabupaten/kota di Sulawesi Selatan. PDRB diukur dalam **juta rupiah** dan digunakan sebagai indikator pertumbuhan ekonomi di tingkat daerah.

### 2. **Variabel Prediktor:**
   - **Penduduk Miskin (X₁)**:
     - **Tipe Data**: Numerik  
     - **Deskripsi**: **Penduduk Miskin** adalah jumlah penduduk yang memiliki rata-rata pengeluaran per kapita per bulan di bawah garis kemiskinan. Variabel ini diukur dalam **persen** dan diharapkan mempengaruhi tingkat pertumbuhan ekonomi di setiap daerah.
   
   - **Pengeluaran per Kapita (X₂)**:
     - **Tipe Data**: Numerik  
     - **Deskripsi**: **Pengeluaran per Kapita** didefinisikan sebagai biaya yang dikeluarkan untuk konsumsi oleh semua anggota rumah tangga selama sebulan, dibagi dengan jumlah anggota rumah tangga. Pengeluaran ini diukur dalam **ribu rupiah** dan merupakan indikator penting dalam analisis ekonomi daerah.
   
   - **Indeks Pembangunan Manusia (IPM) (X₃)**:
     - **Tipe Data**: Numerik  
     - **Deskripsi**: **Indeks Pembangunan Manusia (IPM)** adalah indikator yang menggambarkan tingkat pembangunan dalam suatu wilayah. IPM dihitung berdasarkan faktor-faktor seperti pendidikan, kesehatan, dan standar hidup. Variabel ini diukur dalam **persen** dan digunakan untuk mengukur kualitas hidup di masing-masing kabupaten/kota.

## Pengolahan Data
Sebelum digunakan dalam analisis GMM (Generalized Method of Moments), data telah melalui beberapa tahapan pengolahan:
- **Pembersihan Data**: Menghapus data yang tidak lengkap atau duplikat.
- **Transformasi Variabel**: Beberapa variabel dihitung ulang untuk analisis panel.
- **Imputasi**: Beberapa nilai yang hilang diimputasi menggunakan metode tertentu.

## Akses Data
Data lengkap untuk analisis ini dapat diunduh dari situs resmi **Badan Pusat Statistik Provinsi Sulawesi Selatan** di [https://sulsel.bps.go.id](https://sulsel.bps.go.id).
