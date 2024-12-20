# Analisis Data Panel Dinamis Menggunakan GMM Blundell-Bond

**Analisis Data Panel Dinamis Menggunakan Metode GMM Blundell-Bond pada Pertumbuhan Ekonomi Sulawesi Selatan**

**Abstrak**
Model data panel dinamis menggabungkan lag variabel dependen (lagged dependent variables) sebagai prediktor. Metode Generalized Method of Moments (GMM) Blundell-Bond efektif dalam mengatasi masalah autokorelasi dengan menggabungkan persamaan first-difference dan level, sehingga menghasilkan estimasi yang efisien dan tidak bias. Penelitian ini bertujuan untuk mengidentifikasi faktor-faktor yang memengaruhi pertumbuhan ekonomi di 24 kabupaten/kota di Sulawesi Selatan selama periode 2011-2019. Variabel prediktor yang digunakan meliputi Tingkat Kemiskinan, Pengeluaran per Kapita, dan Indeks Pembangunan Manusia. Hasil menunjukkan bahwa lag PDRB dan IPM memiliki pengaruh positif signifikan, sementara Tingkat Kemiskinan dan Pengeluaran per Kapita memberikan pengaruh negatif terhadap pertumbuhan ekonomi.

**Kata Kunci:** GMM Blundell-Bond, Data Panel Dinamis, Pertumbuhan Ekonomi, PDRB, IPM

---

## Pendahuluan
Pertumbuhan ekonomi merupakan salah satu indikator penting untuk mengukur keberhasilan pembangunan suatu wilayah. Dalam analisis data panel dinamis, variabel dependen dipengaruhi oleh lag variabel dependen (lagged value), sehingga memerlukan metode khusus untuk mengatasi autokorelasi yang mungkin muncul. Generalized Method of Moments (GMM) Blundell-Bond adalah salah satu metode yang dapat digunakan untuk memodelkan persamaan ini secara efisien.

Penelitian ini dilakukan untuk memahami bagaimana faktor-faktor seperti Tingkat Kemiskinan, Pengeluaran per Kapita, dan Indeks Pembangunan Manusia memengaruhi Produk Domestik Regional Bruto (PDRB) di Sulawesi Selatan selama periode 2011-2019.

## Metodologi
### Data
Dataset yang digunakan berasal dari Badan Pusat Statistik Sulawesi Selatan. Data mencakup:
- PDRB (dalam juta rupiah)
- Tingkat Kemiskinan
- Pengeluaran per Kapita
- Indeks Pembangunan Manusia

### Model
Metode GMM Blundell-Bond diterapkan pada model regresi data panel dinamis untuk mengatasi autokorelasi. 

Pengujian signifikansi parameter dilakukan menggunakan uji Wald dan Z, sedangkan validitas instrumen diuji menggunakan uji Sargan dan Arellano-Bond.

## Hasil dan Diskusi
Hasil menunjukkan bahwa:
1. Lag PDRB dan IPM memiliki pengaruh positif terhadap PDRB dengan koefisien masing-masing 0.907 dan 1.168.
2. Tingkat Kemiskinan dan Pengeluaran per Kapita memberikan pengaruh negatif terhadap PDRB dengan koefisien masing-masing -0.065 dan -0.481.

### Tabel Hasil Estimasi
| Variabel       | Koefisien | Signifikansi |
|----------------|-----------|--------------|
| Lag PDRB       | 0.907     | **Signifikan** |
| Tingkat Kemiskinan | -0.065    | **Signifikan** |
| Pengeluaran per Kapita | -0.481    | **Signifikan** |
| IPM            | 1.168     | **Signifikan** |

Model ini divalidasi dengan Mean Square Error (MSE) yang lebih kecil dibandingkan metode lain seperti GMM Arellano-Bond.

## Kesimpulan
Metode GMM Blundell-Bond memberikan hasil yang signifikan dan efisien dalam menganalisis data panel dinamis untuk pertumbuhan ekonomi. Lag PDRB dan IPM memiliki pengaruh positif, sementara Tingkat Kemiskinan dan Pengeluaran per Kapita memiliki pengaruh negatif terhadap PDRB. Penelitian ini dapat digunakan sebagai dasar untuk perencanaan kebijakan ekonomi yang lebih baik di Sulawesi Selatan.

## Referensi
1. Blundell, R., & Bond, S. (1998). Initial conditions and moment restrictions in dynamic panel data models. *Journal of Econometrics*, 87(1), 115-143.
2. Arellano, M., & Bond, S. (1991). Some tests of specification for panel data: Monte Carlo evidence and an application to employment equations. *Review of Economic Studies*, 58(2), 277-297.
