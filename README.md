# E-Commerce Data Analysis Dashboard 

## Deskripsi
Proyek ini bertujuan untuk menganalisis data dari E-Commerce Public Dataset. Analisis ini mencakup proses Data Wrangling, Exploratory Data Analysis (EDA), dan Visualisasi Data untuk mendapatkan insight mengenai performa penjualan, kategori produk terlaris, dan segmentasi pelanggan menggunakan teknik RFM.

## Struktur Direktori
- **/data**: Berisi dataset yang digunakan (dalam format .csv).
- **/dashboard**: Berisi file `dashboard.py` dan data yang sudah dibersihkan (`all_data.csv`).
- **notebook.ipynb**: File Jupyter Notebook yang berisi alur analisis mulai dari awal hingga akhir.
- **README.md**: Dokumentasi proyek.
- **requirements.txt**: Daftar library Python yang dibutuhkan.

## Pertanyaan Bisnis
1. Bagaimana performa penjualan dan pendapatan perusahaan dalam beberapa bulan terakhir?
2. Kategori produk apa yang memiliki penjualan tertinggi dan menghasilkan pendapatan paling besar?
3. Siapa saja pelanggan yang termasuk dalam segmen "Top Spenders" atau "Loyal" menggunakan teknik RFM Analysis?

## Instalasi
Untuk menjalankan proyek ini secara lokal, pastikan Anda telah menginstal Python. Kemudian, ikuti langkah-langkah berikut:

1. Clone repository ini:
   git clone [https://github.com/tsabitaransi/ecommerce-analysis-project.git](https://github.com/tsabitaransi/ecommerce-analysis-project.git)
2. Masuk direktori proyek:
   ```bash
   cd ecommerce-dashboard
   ```
4. Instal library yang dibutuhkan:
   ```bash
   pip install -r requirements.txt
   ```

## Menjalankan Dashboard
```bash
streamlit run dashboard.py
```
