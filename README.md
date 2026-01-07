# 📊 Clustering Kecamatan Menggunakan K-Means

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan **clustering kecamatan** berdasarkan beberapa **variabel numerik** menggunakan algoritma **K-Means**.  
Sebelum proses clustering, data dilakukan **preprocessing** berupa seleksi kolom numerik dan **normalisasi Min-Max**.  
Hasil clustering divisualisasikan menggunakan **PCA (Principal Component Analysis)** agar dapat ditampilkan dalam bentuk 2 dimensi, lengkap dengan **label nama kecamatan**.

---

## 🛠️ Library yang Digunakan
- pandas
- matplotlib
- scikit-learn

Instalasi library:
```bash
pip install pandas matplotlib scikit-learn
```
---
## 📂 Struktur Data
Dataset berbentuk file CSV dengan ketentuan:
- Memiliki **kolom Kecamatan**
- Kolom lainnya berupa **data numerik** yang digunakan untuk clustering

Contoh struktur data:
```bash
Kecamatan | Variabel_1 | Variabel_2 | Variabel_3 | ...
```
---
## 🔄 Alur Proses Analisis
1. Membaca data dari file CSV
2. Memisahkan kolom Kecamatan
3. Menyeleksi kolom numerik
4. Melakukan normalisasi Min-Max
5. Menentukan jumlah cluster dengan Elbow 6. Method
7. Melakukan clustering menggunakan K-Means
8. Visualisasi hasil clustering dengan PCA
---

## 📐 Normalisasi Data
Normalisasi dilakukan menggunakan **MinMaxScaler** untuk menyamakan skala data ke rentang 0–1 sehingga setiap variabel memiliki kontribusi yang seimbang dalam proses clustering.

---
## 🔍 Elbow Method
Elbow Method digunakan untuk menentukan jumlah cluster optimal dengan melihat penurunan nilai inertia terhadap jumlah cluster (k).

---
## 📊 Visualisasi Cluster
- PCA digunakan untuk mereduksi dimensi data menjadi 2 dimensi
- Setiap titik merepresentasikan satu kecamatan
- Warna menunjukkan hasil cluster
- Label pada titik menunjukkan nama kecamatan
---

## 🧠 Interpretasi Hasil
Hasil clustering dapat dimanfaatkan untuk:
- Pengelompokan kecamatan berdasarkan karakteristik data
- Analisis wilayah (rendah, sedang, tinggi)
- Mendukung pengambilan keputusan berbasis data
---

## 👤 Author
- Muhammad Rarendra Satiya 
- Muhammad Fariz Abid Ramadhana

---
## 📊 Visualisasi Tableau
- [Dashboard Analisis dan Klasterisasi Indeks Sosial-Ekonomi Kecamatan di Kota Surabaya](https://public.tableau.com/views/DashboardAnalisisdanKlasterisasiIndeksSosial-EkonomiKecamatandiKotaSurabaya/Dashboard15?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)




