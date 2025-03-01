# Classification and Exploratory Data Analysis (EDA)
---
# 📌 Deskripsi

Proyek ini mencakup Analisis Eksploratori Data (EDA) dan Klasifikasi menggunakan teknik pembelajaran mesin. EDA digunakan untuk memahami pola dan karakteristik data, sedangkan model klasifikasi digunakan untuk membuat prediksi berdasarkan data yang telah diproses.

---
# 🚀 Fitur Utama

- EDA (Exploratory Data Analysis):

Statistik deskriptif

Visualisasi distribusi data

Deteksi nilai hilang dan outlier

Korelasi antar variabel

- Klasifikasi:

Pemrosesan data dan fitur engineering

Implementasi model pembelajaran mesin (SVM, Random Forest, Logistic Regression, dll.)

Evaluasi model dengan metrik akurasi, precision, recall, F1-score

Optimasi model dengan hyperparameter tuning

---

🛠️ Teknologi yang Digunakan

- Python (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn)

- Jupyter Notebook / Google Colab untuk analisis dan eksperimen

- Machine Learning Models: Logistic Regression, Decision Tree, Random Forest, SVM, dll.

---

# 📊 Penjelasan Data

Dataset ini mengandung informasi tentang sesi belanja online, termasuk aktivitas pelanggan selama sesi, status produk yang dilihat atau dimasukkan ke dalam keranjang, dan beberapa data profil pelanggan. Setiap sesi mengandung data seperti kapan sesi dimulai, durasi, produk yang dilihat dan dimasukkan ke dalam keranjang, serta apakah sesi tersebut menghasilkan pembelian atau tidak. Atribut dalam dataset dibagi menjadi beberapa kategori utama, seperti waktu sesi, aktivitas belanja, dan profil pelanggan.

---

# 📌 Atribut Kolom

- Atribut Waktu Sesi

sessionNo: Nomor sesi yang berjalan, digunakan sebagai penomoran urutan dari setiap sesi. Ini adalah bilangan alami.

startHour: Jam ketika sesi dimulai, dengan nilai antara 0 hingga 23 (format 24 jam).

startWeekday: Hari dalam seminggu saat sesi dimulai, dengan nilai 1 untuk Senin, 2 untuk Selasa, hingga 7 untuk Minggu.

- Atribut Durasi Sesi

duration: Total waktu (dalam detik) yang dihabiskan sejak sesi dimulai. Ini adalah angka desimal non-negatif yang menunjukkan lamanya sesi.

- Atribut Aktivitas Klik Produk

cCount: Jumlah produk yang diklik pelanggan selama sesi. Ini adalah bilangan alami.

cMinPrice: Harga terendah dari produk yang diklik selama sesi, dinyatakan sebagai angka desimal non-negatif.

cMaxPrice: Harga tertinggi dari produk yang diklik selama sesi, angka desimal non-negatif.

cSumPrice: Total harga dari semua produk yang diklik selama sesi, angka desimal non-negatif.

- Atribut Aktivitas Produk di Keranjang Belanja

bCount: Jumlah produk yang dimasukkan ke dalam keranjang selama sesi, bilangan alami.

bMinPrice: Harga terendah dari produk yang dimasukkan ke keranjang, angka desimal non-negatif.

bMaxPrice: Harga tertinggi dari produk yang dimasukkan ke keranjang, angka desimal non-negatif.

bSumPrice: Total harga dari semua produk yang dimasukkan ke dalam keranjang, angka desimal non-negatif.

bStep: Langkah dalam proses pembelian yang sedang dilakukan, dengan nilai dari 1 hingga 5. Ini adalah bilangan alami yang menunjukkan tahap proses pembelian yang telah dicapai.

- Atribut Status Online dan Ketersediaan Produk

onlineStatus: Indikator apakah pelanggan online atau tidak selama sesi. Memiliki nilai y untuk "ya" dan n untuk "tidak".

availability: Status ketersediaan atau pengiriman produk yang dilihat, yang menjelaskan apakah produk tersebut bisa dipesan atau tidak (misalnya, "completely orderable," "mainly orderable," dll.).

- Atribut Profil Pelanggan

customerID: Nomor unik yang mengidentifikasi pelanggan.

maxVal: Harga pembelian maksimal yang diizinkan untuk pelanggan tersebut.

customerScore: Evaluasi atau skor pelanggan dari sudut pandang toko.

accountLifetime: Umur akun pelanggan dalam hitungan bulan.

payments: Jumlah pembayaran yang telah dilakukan oleh pelanggan.

age: Usia pelanggan dalam bilangan alami.

address: Bentuk sapaan pelanggan (1 untuk Mr, 2 untuk Mrs, 3 untuk Company).

lastOrder: Waktu dalam hari yang telah berlalu sejak pesanan terakhir pelanggan.

- Atribut Hasil Sesi

order: Hasil dari sesi tersebut, yaitu apakah sesi tersebut menghasilkan pembelian (y untuk pembelian) atau tidak (n untuk non-pembelian).
