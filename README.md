# Prediksi Nilai Berdasarkan Jam Belajar Menggunakan Single Linear Regression

## Deskripsi Program
Program ini bertujuan untuk memprediksi nilai siswa berdasarkan jumlah jam belajar mereka menggunakan metode **regresi linier sederhana**. Regresi linier sederhana adalah teknik statistik yang digunakan untuk memodelkan hubungan linier antara dua variabel: variabel independen (jam belajar) dan variabel dependen (nilai siswa). Program ini menggunakan dataset yang berisi data jam belajar dan nilai siswa, kemudian membangun model regresi linier untuk memprediksi nilai berdasarkan jam belajar.

---

## Langkah-langkah Program
1. **Pengumpulan Data**: Data jam belajar dan nilai siswa dikumpulkan dari dataset yang tersedia.
2. **Pemrosesan Data**: Data yang sudah dikumpulkan diproses untuk memastikan tidak ada nilai yang hilang (missing values) dan outlier.
3. **Pembentukan Model**: Model regresi linier sederhana dibentuk menggunakan algoritma Single Linear Regression.
4. **Evaluasi Model**: Model dievaluasi menggunakan metrik seperti R-squared, Mean Squared Error (MSE), dan Root Mean Squared Error (RMSE).
5. **Prediksi**: Setelah model divalidasi, model digunakan untuk memprediksi nilai siswa berdasarkan jumlah jam belajar yang baru.

---

## Library yang Digunakan
- `matplotlib.pyplot`: Untuk visualisasi data.
- `numpy`: Untuk operasi numerik.
- `pandas`: Untuk manipulasi data.
- `tensorflow`: Untuk machine learning.
- `seaborn`: Untuk visualisasi data statistik.
- `scipy.stats`: Untuk operasi statistik.
- `sklearn.model_selection.train_test_split`: Untuk membagi dataset menjadi data latih dan data uji.
- `sklearn.linear_model.LinearRegression`: Untuk membangun model regresi linier.
- `sklearn.metrics.mean_squared_error, r2_score`: Untuk evaluasi model.

---

## Contoh Visualisasi
Program ini juga menyertakan contoh visualisasi grafik regresi linier sederhana yang menunjukkan hubungan antara jam belajar dan nilai siswa.

---

## Tujuan Project
Tujuan utama dari proyek ini adalah untuk memahami hubungan antara jam belajar dan nilai siswa menggunakan model regresi linier sederhana. Model ini dapat digunakan sebagai dasar untuk membangun model yang lebih kompleks di masa depan.

---

## Dataset
Dataset yang digunakan dalam program ini adalah dataset **"Student Scores"** yang dapat diakses melalui [Kaggle](https://www.kaggle.com/datasets/kamleshsam/student-scores/data).

---

## Cara Menjalankan Program
1. Pastikan semua library yang diperlukan sudah terinstal.
2. Jalankan program di lingkungan Python yang mendukung Jupyter Notebook atau Google Colab.
3. Ikuti langkah-langkah yang ada di notebook untuk memproses data, membangun model, dan melakukan prediksi.

---

## Kesimpulan
Program ini menunjukkan bahwa regresi linier sederhana dapat digunakan untuk memprediksi nilai siswa berdasarkan jam belajar. Model ini memberikan gambaran dasar tentang hubungan antara variabel dan dapat dikembangkan lebih lanjut dengan memasukkan variabel lain atau menggunakan algoritma yang lebih kompleks.

---

## Kontribusi
Jika Anda ingin berkontribusi pada proyek ini, silakan fork repository ini dan buat pull request dengan perubahan yang Anda usulkan.

---

## Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).
