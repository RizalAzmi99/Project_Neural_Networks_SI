
# Data Science & Machine Learning Portfolio

Repository ini berisi kumpulan proyek *Data Science* dan *Machine Learning* yang mencakup berbagai domain, mulai dari retail, kesehatan, lingkungan, hingga perhotelan. Setiap proyek dikerjakan menggunakan Python di Google Colab.

## Daftar Proyek

Berikut adalah detail dari setiap *notebook* yang ada dalam repository ini:

### 1. Online Retail Analytics
* **File:** `Online_Retail_ll.ipynb`
* **Dataset:** Online Retail II.
* **Deskripsi:**
    Analisis data transaksi retail online untuk memahami pola pelanggan atau prediksi penjualan. Proyek ini menggunakan pendekatan *Deep Learning* dengan TensorFlow/Keras untuk memproses data transaksi yang kompleks.
* **Metode & Algoritma:**
    * Data Cleaning & Preparation.
    * Deep Learning dengan TensorFlow (Sequential Model, Dense Layers, Dropout).
    * Analisis performa model.

### 2. Heart Failure Prediction
* **File:** `Dataset2HeartFailureClinicialRecord.ipynb`
* **Dataset:** Heart Failure Clinical Records.
* **Deskripsi:**
    Proyek ini bertujuan untuk memprediksi risiko kematian (*DEATH_EVENT*) pada pasien gagal jantung. Analisis mencakup eksplorasi data klinis (seperti umur, diabetes, tekanan darah) dan pembangunan model klasifikasi.
* **Metode & Algoritma:**
    * Data Preprocessing (Normalisasi, Train-Test Split).
    * Classification (Random Forest / Decision Tree).
    * Evaluasi Model (Confusion Matrix, Accuracy).

### 3. Air Quality & Time Series Analysis
* **File:** `AirQuality.ipynb`
* **Deskripsi:**
    Proyek ini berfokus pada analisis data runtun waktu (*Time Series*) kualitas udara. Notebook ini mencakup pemahaman data historis untuk melihat tren harian/musiman dan melakukan prediksi (forecasting) kondisi udara di masa depan.
* **Metode:**
    * Time Series Decomposition.
    * Visualisasi Tren Data (Plotting).
    * Forecasting Model.

### 4. Hotel Booking Demand Analysis
* **File:** `Dataset_hotel_booking.ipynb`
* **Dataset:** Hotel Booking Demand.
* **Deskripsi:**
    Analisis data reservasi hotel untuk memprediksi kemungkinan pembatalan pemesanan (*booking cancellation*). Proyek ini membantu dalam memahami pola perilaku pelanggan hotel.
* **Metode & Algoritma:**
    * Exploratory Data Analysis (EDA).
    * Neural Networks / Deep Learning (Epochs & Validation Split).
    * Prediksi Binary Class (Cancel vs Not Cancel).

---

## Teknologi yang Digunakan
Proyek-proyek ini dibangun menggunakan pustaka Python berikut:
* **Pandas & NumPy:** Untuk manipulasi dan analisis data.
* **Matplotlib & Seaborn:** Untuk visualisasi data.
* **Scikit-Learn:** Untuk algoritma Machine Learning klasik.
* **TensorFlow / Keras:** Untuk membangun model Deep Learning/Neural Networks.

## Cara Menjalankan
Karena file berbentuk Jupyter Notebook (`.ipynb`), cara termudah untuk menjalankannya adalah:

1.  Buka file `.ipynb` yang diinginkan di GitHub ini.
2.  Klik tombol **"Open in Colab"** (jika tersedia) atau download file dan upload ke [Google Colab](https://colab.research.google.com/).
3.  Pastikan dataset yang dibutuhkan sudah di-upload ke *Google Drive* atau *Session Storage* Colab.
4.  Jalankan setiap sel kode secara berurutan (*Runtime > Run all*).

---
Dibuat oleh 
1. Muhamad Ramadan Awaliadi
2. Muhammad Rizal Azmi
3. Jonathan Stevanus THE
4. Syahtria Akbaruari
