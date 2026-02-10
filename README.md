# 📊 Supermarket Sales Data Analysis

## 📌 Deskripsi Proyek

Proyek ini berisi analisis data penjualan supermarket untuk memahami **pola penjualan, perilaku pelanggan, tingkat kepuasan, serta faktor-faktor yang memengaruhi pendapatan dan profit**. Analisis dilakukan menggunakan Python dengan fokus pada eksplorasi data (EDA) dan penarikan insight bisnis.

Dataset yang digunakan merupakan data transaksi supermarket yang mencakup informasi produk, pelanggan, waktu transaksi, metode pembayaran, hingga rating pelanggan.

---

## 📂 Struktur Dataset

Dataset memiliki beberapa kolom utama berikut:

* **Invoice ID**: ID unik untuk setiap transaksi
* **Branch**: Cabang supermarket
* **City**: Kota cabang supermarket
* **Customer Type**: Member atau Normal
* **Gender**: Jenis kelamin pelanggan
* **Product Line**: Kategori produk
* **Unit Price**: Harga satuan produk
* **Quantity**: Jumlah item yang dibeli
* **Tax 5%**: Pajak 5% dari transaksi
* **Sales / Total**: Total nilai transaksi (termasuk pajak)
* **COGS**: Cost of Goods Sold
* **Gross Income**: Keuntungan dari transaksi
* **Date & Time**: Waktu transaksi
* **Payment**: Metode pembayaran
* **Rating**: Penilaian pelanggan (1–10)

---

## 🎯 Tujuan Analisis

* Mengidentifikasi **kontributor utama penjualan dan profit**
* Memahami **perilaku pelanggan** berdasarkan tipe, gender, dan waktu
* Menganalisis **hubungan antar variabel numerik** (Sales, Quantity, Rating, Gross Income)
* Menentukan **faktor paling berpengaruh terhadap Gross Income**

---

## ❓ Pertanyaan Analisis Utama

1. Cabang/kota mana yang memiliki penjualan dan profit tertinggi?
2. Product line apa yang paling berkontribusi terhadap pendapatan?
3. Apakah terdapat perbedaan pola pembelian antara Member dan Normal?
4. Bagaimana pengaruh metode pembayaran terhadap nilai dan jumlah transaksi?
5. Kapan waktu penjualan paling tinggi (tanggal, bulan, jam)?
6. Apakah gender memengaruhi jenis produk yang dibeli dan total belanja?
7. Product line mana dengan tingkat kepuasan tertinggi dan terendah?
8. Apakah jumlah pembelian (Quantity) berhubungan dengan total pendapatan?
9. Apakah nilai transaksi yang lebih tinggi menghasilkan rating lebih baik?
10. Faktor apa yang paling berpengaruh terhadap Gross Income?

---

## 📈 Metodologi Analisis

* **Data Cleaning & Feature Engineering**

  * Ekstraksi jam, hari, dan bulan dari kolom datetime
* **Exploratory Data Analysis (EDA)**

  * Barplot untuk data kategorikal
  * Scatterplot & Regplot untuk hubungan numerik
  * Boxplot untuk distribusi dan perbandingan
* **Statistik Pendukung**

  * Rata-rata, total, min–max
  * Korelasi Pearson

---

## 🔍 Insight Utama

* **Quantity adalah faktor paling berpengaruh terhadap Gross Income** (korelasi ≈ 0.71)
* **Unit Price juga berpengaruh kuat**, namun di bawah Quantity
* **Tidak terdapat hubungan signifikan antara Sales dan Rating**
* **Member** berkontribusi lebih besar terhadap penjualan dan kuantitas dibanding Normal
* **Food and Beverages** memiliki tingkat kepuasan pelanggan tertinggi
* **Pelanggan perempuan** mendominasi total belanja di hampir semua product line
* Metode pembayaran **Cash dan Ewallet** memiliki kontribusi transaksi tertinggi

---

## 🛠️ Tools & Library

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📌 Kesimpulan

Analisis ini menunjukkan bahwa peningkatan **volume pembelian** merupakan strategi paling efektif untuk meningkatkan profit. Faktor non-finansial seperti **kualitas produk dan pelayanan** lebih berpengaruh terhadap kepuasan pelanggan dibandingkan nilai transaksi.

---

## 🚀 Pengembangan Lanjutan

* Analisis regresi multivariat
* Segmentasi pelanggan (clustering)
* Dashboard interaktif (Streamlit / Tableau)
* Prediksi penjualan dan profit

---
