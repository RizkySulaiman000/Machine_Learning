<b>🎓 Aplikasi Prediksi Kelulusan Mahasiswa</b>

Aplikasi berbasis web ini dirancang untuk memprediksi kelulusan mahasiswa berdasarkan nilai akademik dan data lainnya. Proyek ini mengimplementasikan teknik Machine Learning menggunakan model XGBoost dan menampilkan hasil 
prediksi melalui antarmuka interaktif berbasis Streamlit.

<b>📋 Deskripsi Proyek</b>

<b>Latar Belakang</b>

Mengetahui tingkat kelulusan mahasiswa merupakan hal penting bagi institusi pendidikan untuk memantau kualitas akademik. Dengan memanfaatkan data akademik mahasiswa, model prediksi dapat digunakan untuk memberikan wawasan awal terkait kelulusan.

<b>Tujuan</b>

Mengembangkan model machine learning yang dapat memprediksi kelulusan mahasiswa berdasarkan data akademik.
Menyediakan antarmuka web interaktif untuk melakukan prediksi dengan mudah.

🚀 Langkah Instalasi
1. Python versi 3.10 atau lebih baru

2. Paket-paket berikut diperlukan:
   a. xgboost
   
   b. streamlit

   c. scikit-learn

   d. imblearn

   e. pandas

   f. numpy

   g. matplotlib

<b>Langkah Instalasi</b>

1. Clone repository ini:

git clone https://github.com/username/predict-student-graduation.git

cd predict-student-graduation

2. Buat virtual environment dan aktifkan:

python -m venv env

source env/bin/activate  # Untuk Linux/MacOS

env\Scripts\activate     # Untuk Windows

3. Instal dependencies:

pip install -r requirements.txt

4. Jalankan aplikasi:

streamlit run app.py

<b>🧠 Deskripsi Model</b>

Model yang Digunakan

Model yang digunakan dalam proyek ini adalah XGBoost (Extreme Gradient Boosting). Model ini dipilih karena performanya yang unggul dalam menangani data tabular dengan ukuran besar dan kompleks.

Pipeline Proses

1. Data Preprocessing:

   a. Memilih 6 fitur utama: Nilai masuk, nilai semester 1, nilai semester 2, nilai kualifikasi sebelumnya, jumlah mata kuliah disetujui semester 1 dan semester 2.

   b. Menyeimbangkan distribusi kelas menggunakan SMOTE.

   c. Melakukan standarisasi data dengan StandardScaler.

2. Pelatihan Model:

   a. Model dilatih menggunakan XGBoostClassifier dengan parameter default dan evaluasi logloss.

<b>📊 Hasil dan Analisis</b>

a. Hasil Evaluasi

b. Accuracy: 93%

c. F1-Score Kelas Lulus: 0.95

d. F1-Score Kelas Tidak Lulus: 0.96

![image](https://github.com/user-attachments/assets/cd9600e4-1e61-4489-8b08-52cd0e68beba)

<b>📂 Grafik Distribusi Kelas</b>

Distribusi kelas sebelum dan sesudah oversampling menggunakan SMOTE:

Sebelum Oversampling:

![image](https://github.com/user-attachments/assets/db13cd63-c517-4ffd-8ce0-d487bb6bca66)


Sesudah Oversampling:

![image](https://github.com/user-attachments/assets/94f76b7c-0f0c-43e2-a818-dcb1e03bacb2)

<b>🌟 Fitur Utama</b>

Input Data Mahasiswa:

Form interaktif untuk memasukkan data akademik seperti:

1. Nilai Masuk Mahasiswa

2. Nilai Rata-Rata Semester 1

3. Nilai Rata-Rata Semester 2

4. Nilai Kualifikasi Sebelumnya

5. Mata Kuliah Disetujui Semester 1

6. Mata Kuliah Disetujui Semester 2

7. Komponen slider mempermudah pengguna untuk memasukkan data numerik.

<b>📸 Cuplikan Tampilan Web</b>

1. Halaman Utama

![image](https://github.com/user-attachments/assets/627c3ad2-fe11-4e38-8a16-154ae3b863fe)

3. Input Data Mahasiswa

![image](https://github.com/user-attachments/assets/fa8db9cf-cc55-4a5d-9257-c4a1a02eaae5)


4. Hasil Prediksi

![image](https://github.com/user-attachments/assets/ff58d271-5e65-4d5a-820f-844f33849881)

<b>📝 Lisensi</b>

<b>Copyright (c) 2024 @RizkySulaiman000</b>


