# Student Productivity Prediction

**Author:** Muhammad Raafi

## Tentang Proyek

Student Productivity Prediction merupakan proyek Machine Learning yang bertujuan untuk memprediksi skor produktivitas mahasiswa berdasarkan berbagai faktor yang berkaitan dengan kebiasaan belajar, aktivitas sehari-hari, dan performa akademik.

Proyek ini menerapkan beberapa tahapan Machine Learning, mulai dari pengolahan data, eksplorasi data, preprocessing, pengembangan model regresi, evaluasi performa model, hingga penyimpanan model agar dapat digunakan kembali.

Proyek ini dibuat sebagai bagian dari pembelajaran dan penerapan konsep Machine Learning menggunakan Python.

## Tujuan Proyek

- Memahami karakteristik data yang digunakan dalam proses Machine Learning.
- Melakukan preprocessing untuk mempersiapkan data sebelum pelatihan model.
- Menangani missing value dan memeriksa data duplikat.
- Mengidentifikasi potensi outlier dalam data.
- Melakukan Exploratory Data Analysis (EDA).
- Mempersiapkan fitur numerik dan kategorikal.
- Mengembangkan model regresi untuk memprediksi skor produktivitas mahasiswa.
- Membandingkan performa model menggunakan metrik evaluasi.
- Menyimpan model terlatih agar dapat digunakan kembali.

## Tahapan Pengerjaan

### 1. Data Loading dan Data Understanding

Tahap awal dilakukan dengan memuat data menggunakan Pandas. Selanjutnya, dilakukan pemeriksaan terhadap jumlah baris, jumlah kolom, tipe data, karakteristik fitur, dan statistik deskriptif untuk memahami kondisi data sebelum diproses.

### 2. Data Preprocessing

Preprocessing dilakukan untuk mempersiapkan data agar dapat digunakan dalam proses pelatihan model. Tahapan ini mencakup:

- Mengidentifikasi dan menangani missing value.
- Memeriksa data duplikat.
- Mengidentifikasi potensi outlier menggunakan metode Interquartile Range (IQR).
- Melakukan encoding pada fitur kategorikal jika diperlukan.
- Melakukan standardisasi fitur numerik jika diperlukan.
- Mempersiapkan fitur dan variabel target sesuai kebutuhan model.

### 3. Exploratory Data Analysis (EDA)

Exploratory Data Analysis dilakukan untuk memahami distribusi, karakteristik, dan pola dalam data melalui analisis statistik serta visualisasi.

Tahap ini membantu mengeksplorasi hubungan antarfitur dan memahami karakteristik data yang berpotensi berkaitan dengan skor produktivitas mahasiswa.

### 4. Pengembangan Model Machine Learning

Algoritma regresi yang dibahas dalam proyek ini meliputi:

- **Linear Regression:** Mempelajari hubungan linear antara fitur input dan variabel target.
- **Least Angle Regression (LARS):** Menggunakan pendekatan bertahap untuk menentukan koefisien model regresi.
- **Gradient Boosting Regressor:** Menggabungkan sejumlah model secara bertahap untuk menghasilkan prediksi yang lebih baik.

Performa model dibandingkan berdasarkan hasil evaluasi untuk mengetahui model yang memberikan hasil prediksi terbaik.

### 5. Evaluasi Model

Evaluasi dilakukan untuk mengukur kemampuan model dalam menghasilkan prediksi. Metrik evaluasi regresi yang digunakan atau dibahas dalam proyek ini meliputi:

- **Mean Absolute Error (MAE):** Mengukur rata-rata selisih absolut antara nilai aktual dan nilai prediksi.
- **Mean Squared Error (MSE):** Mengukur rata-rata kuadrat kesalahan prediksi.
- **R² Score:** Mengukur seberapa baik model menjelaskan variasi pada variabel target.

Hasil evaluasi digunakan untuk membandingkan performa model berdasarkan nilai metrik yang diperoleh.

### 6. Penyimpanan Model

Model disimpan dalam dua format file, yaitu:

- `gbr_model.pkl`
- `gbr_model.joblib`

Kedua file tersebut digunakan untuk menyimpan model yang telah dilatih sehingga dapat dimuat kembali tanpa perlu mengulangi proses pelatihan, selama file dan dependensi yang diperlukan tersedia serta sesuai.

## Teknologi yang Digunakan

- **Python** — Bahasa pemrograman utama untuk pengolahan data dan pengembangan model.
- **Pandas** — Membaca, mengolah, dan menganalisis data.
- **NumPy** — Mendukung operasi numerik.
- **Matplotlib** — Membuat visualisasi data.
- **Seaborn** — Membantu eksplorasi dan visualisasi data.
- **Scikit-learn** — Menyediakan algoritma Machine Learning, preprocessing, dan metrik evaluasi.
- **Pickle** — Menyimpan dan memuat model dalam format `.pkl`.
- **Joblib** — Menyimpan dan memuat model dalam format `.joblib`.
- **Jupyter Notebook** — Menjalankan kode dan mendokumentasikan eksperimen Machine Learning.

## Struktur Repository

```text
Student-Productivity-Prediction/
│
├── student_productivity_prediction.ipynb
├── README.md
├── train.csv
├── test.csv
├── sample_submission.csv
├── gbr_model.pkl
└── gbr_model.joblib
```

### Keterangan File

- `student_productivity_prediction.ipynb` — Notebook yang berisi kode, eksplorasi data, preprocessing, pelatihan, dan evaluasi model.
- `README.md` — Dokumentasi proyek.
- `train.csv` — Data yang digunakan untuk melatih model.
- `test.csv` — Data yang digunakan untuk menghasilkan prediksi.
- `sample_submission.csv` — Template format hasil prediksi.
- `gbr_model.pkl` — File model yang disimpan menggunakan Pickle.
- `gbr_model.joblib` — File model yang disimpan menggunakan Joblib.

*Catatan: Nama file dalam struktur di atas harus sesuai dengan file yang benar-benar tersedia di repository GitHub.*

## Cara Menjalankan Proyek

1. Unduh atau clone repository ke komputer.
2. Pastikan file yang dibutuhkan tersedia di direktori proyek.
3. Buka notebook menggunakan Jupyter Notebook.
4. Jalankan sel kode secara berurutan mulai dari pemuatan data hingga evaluasi model.
5. Periksa hasil preprocessing, eksplorasi data, dan evaluasi model.
6. Jika ingin menggunakan model yang telah disimpan, muat file `.pkl` atau `.joblib` menggunakan metode yang sesuai.

## Kesimpulan

Proyek Student Productivity Prediction menerapkan tahapan utama Machine Learning untuk mempelajari dan memprediksi skor produktivitas mahasiswa. Melalui preprocessing, eksplorasi data, pengembangan model regresi, dan evaluasi, proyek ini menjadi sarana pembelajaran penerapan Machine Learning dalam analisis data pendidikan.

Proyek ini juga dapat digunakan sebagai dokumentasi praktikum dan portofolio untuk menunjukkan pemahaman dasar mengenai pengolahan data serta pengembangan model prediksi menggunakan Python.

## Sumber Data

Dataset diperoleh dari Kaggle:

[Student Productivity Prediction Challenge — Kaggle](https://www.kaggle.com/competitions/student-performance-prediction-machine-learning-challenge/data?select=test.csv)

## Author

**Muhammad Raafi**

Proyek Praktikum Machine Learning — Student Productivity Prediction.
