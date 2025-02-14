# Prediksi Nilai Berdasarkan Jam Belajar Menggunakan Single Linear Regression

## Deskripsi Proyek

Proyek ini bertujuan untuk memprediksi nilai siswa berdasarkan jumlah jam belajar mereka menggunakan metode regresi linier sederhana. Regresi linier sederhana adalah teknik statistik yang digunakan untuk memodelkan hubungan linier antara dua variabel: variabel independen (jam belajar) dan variabel dependen (nilai siswa). Model ini menghasilkan garis regresi yang merepresentasikan hubungan tersebut.

## Dataset

Dataset yang digunakan dalam proyek ini adalah dataset "Student Scores" yang dapat diakses melalui [Kaggle](https://www.kaggle.com/datasets/kamleshsam/student-scores/data). Dataset ini berisi dua kolom utama:
- `Hours`: Jumlah jam belajar siswa.
- `Scores`: Nilai yang diperoleh siswa.

## Library yang Digunakan

Proyek ini menggunakan beberapa library Python, antara lain:
- `matplotlib`: Untuk visualisasi data.
- `numpy`: Untuk operasi numerik.
- `pandas`: Untuk manipulasi data.
- `seaborn`: Untuk visualisasi data yang lebih menarik.
- `scipy`: Untuk statistik.
- `sklearn`: Untuk implementasi model regresi linier dan evaluasi model.

## Langkah-langkah

1. **Import Library**: Mengimpor library yang diperlukan.
2. **Import Dataset**: Membaca dataset dari URL.
3. **Data Cleaning**: Memeriksa dan membersihkan data dari missing values dan outliers.
4. **Visualisasi Data**: Membuat grafik scatter plot untuk melihat hubungan antara jam belajar dan nilai.
5. **Pembuatan Model**: Membuat model regresi linier sederhana menggunakan `LinearRegression` dari `sklearn`.
6. **Evaluasi Model**: Menghitung Mean Squared Error (MSE) dan R-squared untuk mengevaluasi performa model.
7. **Prediksi**: Menggunakan model untuk memprediksi nilai berdasarkan jam belajar.

## Hasil

Model regresi linier sederhana berhasil dibuat dan dievaluasi. Hasil prediksi menunjukkan bahwa terdapat hubungan linier positif antara jumlah jam belajar dan nilai yang diperoleh siswa.

## Cara Menjalankan Proyek

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/repository-name.git
2. Install library yang diperlukan:

    ```bash
    pip install -r requirements.txt
3. Jalankan notebook Jupyter:
   ```bash
   jupyter notebook Prediksi_Nilai_Berdasarkan_Jam_Belajar_Menggunakan_Single_Linear_Regression.ipynb
