# E-Commerce Data Analysis Dashboard 

## Deskripsi
Proyek ini bertujuan untuk menganalisis data dari E-Commerce Public Dataset. Analisis ini mencakup proses Data Wrangling, Exploratory Data Analysis (EDA), dan Visualisasi Data untuk mendapatkan insight mengenai performa penjualan, kategori produk terlaris, dan segmentasi pelanggan menggunakan teknik RFM.

## Struktur Direktori
- **/data**: Berisi dataset yang digunakan (dalam format .csv).
- **/dashboard**: Berisi file `dashboard.py` dan data yang sudah dibersihkan (`all_data.csv`).
- **notebook.ipynb**: File Jupyter Notebook yang berisi alur analisis mulai dari awal hingga akhir.
- **README.md**: Dokumentasi proyek.
- **requirements.txt**: Daftar library Python yang dibutuhkan.

## Setup Environment - Anaconda
```bash
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Terminal
```bash
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Menjalankan Dashboard
```bash
streamlit run dashboard.py
```
