
### Hasil Estimasi Parameter
- **δ** = 0.907 (lag PDRB berpengaruh positif terhadap PDRB)
- **β1** = -0.065 (Penduduk Miskin berpengaruh negatif terhadap PDRB)
- **β2** = -0.481 (Pengeluaran per Kapita berpengaruh negatif terhadap PDRB)
- **β3** = 1.168 (Indeks Pembangunan Manusia berpengaruh positif terhadap PDRB)

## Uji Signifikansi
### Uji Wald (Simultan)
- Nilai statistik uji Wald = 123828.99, p-value = 0.00.
- **Kesimpulan**: H0 ditolak, yang berarti secara simultan variabel lag PDRB, Penduduk Miskin, Pengeluaran per Kapita, dan IPM berpengaruh signifikan terhadap PDRB.

### Uji Z (Parsial)
- **Variabel Lag PDRB**: Z = 96.75, p-value = 0.00
- **Penduduk Miskin**: Z = 7.89, p-value = 0.00
- **Pengeluaran per Kapita**: Z = -7.23, p-value = 0.00
- **Indeks Pembangunan Manusia**: Z = -8.49, p-value = 0.00
- **Kesimpulan**: H0 ditolak untuk semua variabel, yang berarti variabel-variabel tersebut secara parsial berpengaruh signifikan terhadap PDRB.

## Uji Spesifikasi Model
### Uji Sargan
- Nilai S_hitung = 21.86, p-value = 0.94
- **Kesimpulan**: H0 diterima, yang berarti model estimasi valid dan instrumen yang digunakan tidak berkorelasi dengan galat.

### Uji Arellano-Bond
- **Orde 1**: Nilai statistik = -2.88, p-value = 0.004
- **Orde 2**: Nilai statistik = -1.21, p-value = 0.225
- **Kesimpulan**: H0 ditolak untuk orde pertama (terjadi autokorelasi), namun H0 gagal ditolak untuk orde kedua (tidak terjadi autokorelasi), yang berarti estimasi model GMM Blundell-Bond konsisten.


