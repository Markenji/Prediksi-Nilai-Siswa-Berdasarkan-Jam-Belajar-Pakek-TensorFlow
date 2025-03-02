
# Prediksi Nilai Siswa Berdasarkan Jam Belajar

Proyek ini bertujuan untuk memprediksi nilai siswa berdasarkan jumlah jam belajar mereka menggunakan model *machine learning*.  Dataset yang digunakan berisi data jam belajar dan nilai yang diperoleh oleh sejumlah siswa.

## Tahapan Analisis

Proyek ini melalui beberapa tahapan, yaitu:

1. **Impor Dataset:** Dataset diperoleh dari sumber online dan dibaca ke dalam *dataframe* Pandas.

2. **Pembersihan Data:**  Data diperiksa untuk nilai yang hilang (*missing values*) dan *outlier*.  Tidak ada nilai yang hilang dan outlier diperiksa menggunakan *boxplot*.

3. **Rekayasa Fitur:** Distribusi data jam belajar dan nilai dianalisa menggunakan histogram dan *Q-Q plot* untuk mengetahui sebaran datanya.  Uji Shapiro-Wilk digunakan untuk menguji normalitas data.

4. **Statistik Deskriptif:** Statistik deskriptif seperti rata-rata, standar deviasi, nilai minimum, dan maksimum dihitung dan ditampilkan untuk variabel jam belajar dan nilai.

5. **Pembagian Data Latih dan Uji (*Train-Test Split*):** Data dibagi menjadi data latih dan data uji untuk melatih dan mengevaluasi model.

6. **Pembuatan Model:**  Beberapa model *neural network* dibangun menggunakan TensorFlow/Keras dengan arsitektur dan jumlah *epoch* yang berbeda.

7. **Evaluasi Model:** Model dievaluasi menggunakan metrik regresi seperti MAE (*Mean Absolute Error*), MSE (*Mean Squared Error*), dan R-squared.  Model terbaik dipilih berdasarkan metrik-metrik ini.

8. **Pengujian Model dengan Data Baru:** Model terbaik diuji dengan data baru untuk mengukur kemampuan generalisasi.  Hasil prediksi dibandingkan dengan nilai sebenarnya menggunakan MAE, MSE, dan R-squared.

## Hasil dan Kesimpulan

Model terbaik yang dihasilkan (Model 3) memiliki 2 lapisan tersembunyi dan dilatih selama 500 epoch.  Namun, saat diuji dengan data baru, model menunjukkan performa yang buruk, ditandai dengan nilai R-squared negatif. Ini mengindikasikan bahwa model tidak mampu menangkap hubungan antara jam belajar dan nilai dengan baik pada data baru.  Perlu dilakukan peningkatan model lebih lanjut.
