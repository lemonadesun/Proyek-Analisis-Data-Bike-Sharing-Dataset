# Proyek Analisis Data: Bike Sharing Dataset

Nama: Septia Clara Sinaga

Email: M232D4KX2951@bangkit.academy

ID Dicoding: M232D4KX2951

## Bike Sharing Dataset

Dataset Bike Sharing merupakan kumpulan data yang mencakup informasi tentang penyewaan sepeda harian yang mencatat jumlah sepeda yang dipinjam, cuaca, dan faktor-faktor lain yang memengaruhi kegiatan peminjaman sepeda. Dataset ini berisikan informasi tentang penyewaan sepeda harian yang mencakup data tanggal, musim, tahun, bulan, jam, hari libur, hari kerja, cuaca, suhu, suhu terasa, kelembaban, kecepatan angin, serta jumlah pengguna sepeda casual, pengguna sepeda terdaftar, dan total jumlah penyewaan sepeda. Namun pada proyek ini variabel yang dipakai hanya data data tanggal, jam, dan cuaca. Hasil visualisasi dari dataset bike sharing akan digunakan dalam menjawab 2 pertanyaan, yaitu:

Pertanyaan 1: Berapa total jam penyewaan sepeda tertinggi dalam satu hari yang tercatat dalam data rental sepeda dan apa faktor yang mempengaruhi peningkatan penyewaan sepeda pada hari tersebut?

Pertanyaan 2: Apakah penyewaan sepeda dipengaruhi oleh kondisi cuaca?

## Sumber Data

Sumber data yang digunakan berasal dari https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset.

## Cara Membuat Dashboard
### Setup Environment
1. **Membuat dan Mengaktifkan Python Environment**
   - Menggunakan virtual environment (venv):
      ```
      python -m venv venv
      .\venv\Scripts\activate
      ```
2. **Mengunduh Libraries**:
   - Berikut cara mengunduh semua libraries yang diperlukan:
     ```
      python -m pip install pandas
      python -m pip install numpy
      python -m pip install matplotlib
      python -m pip install pyplot
      python -m pip install streamlit
      python -m pip install seaborn
     ```
### Run Streamlit App
1. Navigasikan ke Direktori Proyek di mana file 'bike.py' sebagai dashboard disimpan.
2. Jalankan Aplikasi Streamlit dengan perintah:
   ```
    python -m streamlit run bike.py
   ```
3. Upload file bike.py ke github
4. Diploy menggunakan streamlit app dengan menghubungkannya dengan github
     
