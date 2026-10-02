# Steam Game Analysis

Proyek analisis data game Steam yang dibuat untuk mempelajari karakteristik game berdasarkan data pengguna, ulasan, rating, dan harga. Proyek ini menggunakan teknik data mining berupa clustering untuk mengelompokkan game berdasarkan karakteristik yang memiliki kemiripan.

## 📌 Deskripsi

Proyek ini bertujuan untuk menganalisis dataset game Steam dan menemukan pola atau kelompok game berdasarkan beberapa karakteristik utama, seperti:

- Jumlah user reviews
- Persentase ulasan positif
- Harga game

Hasil clustering kemudian digunakan untuk melihat karakteristik setiap kelompok serta mengidentifikasi game yang memiliki karakteristik berbeda dari kelompok lainnya.

## 🎯 Tujuan

- Memahami karakteristik data game pada platform Steam.
- Melakukan eksplorasi dan preprocessing data.
- Mengelompokkan game berdasarkan karakteristik tertentu menggunakan clustering.
- Menganalisis karakteristik dari setiap cluster.
- Mengidentifikasi data atau game dengan karakteristik yang tidak umum.

## 🛠️ Teknologi

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📊 Dataset

Dataset yang digunakan berisi informasi mengenai game Steam, termasuk data yang berkaitan dengan:

- Nama game
- Harga
- User reviews
- Positive ratio
- Informasi lainnya yang tersedia pada dataset

Dataset digunakan sebagai bahan eksplorasi dan analisis untuk menemukan pola berdasarkan karakteristik game.

## 🔎 Tahapan Analisis

### 1. Data Preparation
Melakukan pemeriksaan dan persiapan dataset sebelum digunakan dalam proses analisis.

### 2. Exploratory Data Analysis
Menganalisis distribusi dan hubungan antar variabel yang digunakan dalam penelitian.

### 3. Feature Selection
Memilih beberapa fitur yang relevan untuk proses clustering, yaitu:

- User Reviews
- Positive Ratio
- Price

### 4. Clustering
Melakukan pengelompokan game berdasarkan karakteristik fitur yang telah dipilih.

Hasil clustering menghasilkan beberapa kelompok game dengan karakteristik yang berbeda.

### 5. Cluster Analysis
Setiap cluster dianalisis berdasarkan nilai rata-rata fitur untuk mengetahui karakteristik masing-masing kelompok.

### 6. Anomaly Identification
Melakukan identifikasi terhadap game yang memiliki karakteristik berbeda berdasarkan hasil clustering.

## 📈 Hasil Analisis

Hasil clustering menunjukkan adanya beberapa kelompok game dengan karakteristik yang berbeda berdasarkan jumlah ulasan, persentase ulasan positif, dan harga.

Contoh ringkasan hasil clustering:

| Cluster | User Reviews | Positive Ratio | Price |
|---------|-------------:|----------------:|------:|
| 0 | 6122.73 | 83.64 | 9.50 |
| 1 | 4709.36 | 73.44 | 42.17 |
| 2 | 46.20 | 75.01 | 5.65 |

Cluster dengan jumlah review yang relatif rendah menunjukkan karakteristik yang berbeda dibandingkan kelompok dengan jumlah review yang lebih tinggi. Hasil clustering kemudian digunakan sebagai dasar untuk melakukan analisis lebih lanjut terhadap game yang berada pada kelompok tertentu.

## 📂 Struktur Project

```text
Steam-Game-Analysis/
│
├── README.md
├── 23.11.5391_Raditya Julian Primasakti_UAS Big Data & Data Mining.ipynb
└── dataset/
    └── game.csv
