<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prediksi Nilai Berdasarkan Jam Belajar Menggunakan Single Linear Regression</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        code {
            background-color: #f4f4f4;
            padding: 5px;
            border-radius: 5px;
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
        }
        .section ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        .section p {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <h1>Prediksi Nilai Berdasarkan Jam Belajar Menggunakan Single Linear Regression</h1>

    <div class="section">
        <h2>Deskripsi Program</h2>
        <p>Program ini bertujuan untuk memprediksi nilai siswa berdasarkan jumlah jam belajar mereka menggunakan metode regresi linier sederhana. Regresi linier sederhana adalah teknik statistik yang digunakan untuk memodelkan hubungan linier antara dua variabel: variabel independen (jam belajar) dan variabel dependen (nilai siswa). Program ini menggunakan dataset yang berisi data jam belajar dan nilai siswa, kemudian membangun model regresi linier untuk memprediksi nilai berdasarkan jam belajar.</p>
    </div>

    <div class="section">
        <h2>Langkah-langkah Program</h2>
        <ul>
            <li><strong>Pengumpulan Data</strong>: Data jam belajar dan nilai siswa dikumpulkan dari dataset yang tersedia.</li>
            <li><strong>Pemrosesan Data</strong>: Data yang sudah dikumpulkan diproses untuk memastikan tidak ada nilai yang hilang (missing values) dan outlier.</li>
            <li><strong>Pembentukan Model</strong>: Model regresi linier sederhana dibentuk menggunakan algoritma Single Linear Regression.</li>
            <li><strong>Evaluasi Model</strong>: Model dievaluasi menggunakan metrik seperti R-squared, Mean Squared Error (MSE), dan Root Mean Squared Error (RMSE).</li>
            <li><strong>Prediksi</strong>: Setelah model divalidasi, model digunakan untuk memprediksi nilai siswa berdasarkan jumlah jam belajar yang baru.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Library yang Digunakan</h2>
        <ul>
            <li><code>matplotlib.pyplot</code>: Untuk visualisasi data.</li>
            <li><code>numpy</code>: Untuk operasi numerik.</li>
            <li><code>pandas</code>: Untuk manipulasi data.</li>
            <li><code>tensorflow</code>: Untuk machine learning.</li>
            <li><code>seaborn</code>: Untuk visualisasi data statistik.</li>
            <li><code>scipy.stats</code>: Untuk operasi statistik.</li>
            <li><code>sklearn.model_selection.train_test_split</code>: Untuk membagi dataset menjadi data latih dan data uji.</li>
            <li><code>sklearn.linear_model.LinearRegression</code>: Untuk membangun model regresi linier.</li>
            <li><code>sklearn.metrics.mean_squared_error, r2_score</code>: Untuk evaluasi model.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Contoh Visualisasi</h2>
        <p>Program ini juga menyertakan contoh visualisasi grafik regresi linier sederhana yang menunjukkan hubungan antara jam belajar dan nilai siswa.</p>
    </div>

    <div class="section">
        <h2>Tujuan Project</h2>
        <p>Tujuan utama dari proyek ini adalah untuk memahami hubungan antara jam belajar dan nilai siswa menggunakan model regresi linier sederhana. Model ini dapat digunakan sebagai dasar untuk membangun model yang lebih kompleks di masa depan.</p>
    </div>

    <div class="section">
        <h2>Dataset</h2>
        <p>Dataset yang digunakan dalam program ini adalah dataset "Student Scores" yang dapat diakses melalui <a href="https://www.kaggle.com/datasets/kamleshsam/student-scores/data" target="_blank">Kaggle</a>.</p>
    </div>

    <div class="section">
        <h2>Cara Menjalankan Program</h2>
        <ol>
            <li>Pastikan semua library yang diperlukan sudah terinstal.</li>
            <li>Jalankan program di lingkungan Python yang mendukung Jupyter Notebook atau Google Colab.</li>
            <li>Ikuti langkah-langkah yang ada di notebook untuk memproses data, membangun model, dan melakukan prediksi.</li>
        </ol>
    </div>

    <div class="section">
        <h2>Kesimpulan</h2>
        <p>Program ini menunjukkan bahwa regresi linier sederhana dapat digunakan untuk memprediksi nilai siswa berdasarkan jam belajar. Model ini memberikan gambaran dasar tentang hubungan antara variabel dan dapat dikembangkan lebih lanjut dengan memasukkan variabel lain atau menggunakan algoritma yang lebih kompleks.</p>
    </div>

    <div class="section">
        <h2>Kontribusi</h2>
        <p>Jika Anda ingin berkontribusi pada proyek ini, silakan fork repository ini dan buat pull request dengan perubahan yang Anda usulkan.</p>
    </div>

    <div class="section">
        <h2>Lisensi</h2>
        <p>Proyek ini dilisensikan di bawah <a href="LICENSE" target="_blank">MIT License</a>.</p>
    </div>
</body>
</html>
