# 📊 Analisis Tren Penjualan Produk Tahun 2024

## 📌 Tentang Proyek

Proyek ini merupakan bagian dari Uji Kompetensi BNSP Skema Analis Data Muda (Associate Data Analyst). Studi kasus yang diberikan berfokus pada analisis data transaksi penjualan untuk menghasilkan insight bisnis dan menyajikannya dalam bentuk dashboard interaktif.

Analisis dilakukan untuk membantu stakeholder memahami performa penjualan berdasarkan produk, wilayah, dan periode waktu sehingga dapat mendukung pengambilan keputusan berbasis data.

---

## 🎯 Tujuan Proyek

Tujuan dari proyek ini adalah:

- Melakukan pembersihan dan validasi data penjualan.
- Menelaah struktur data dan kualitas data.
- Mengidentifikasi variabel yang relevan untuk analisis.
- Menganalisis performa penjualan berdasarkan produk, wilayah, dan waktu.
- Menyajikan hasil analisis dalam bentuk dashboard interaktif.
- Memberikan rekomendasi berdasarkan insight yang diperoleh.

---

## 📂 Dataset

**Nama Dataset:** `dataset_penjualan_kotor.csv`

### Informasi Dataset

| Informasi | Nilai |
|------------|--------|
| Jumlah Baris | 205 |
| Jumlah Kolom | 9 |
| Jumlah Produk | 5 |
| Jumlah Wilayah | 5 |
| Missing Value Quantity | 10 |
| Missing Value Total Price | 8 |

Dataset berisi data transaksi penjualan produk elektronik yang mencakup informasi produk, wilayah, kuantitas pembelian, tanggal transaksi, dan total penjualan.

---

## 🛠️ Tools yang Digunakan

### SQL
Digunakan untuk:
- Eksplorasi data
- Validasi data
- Agregasi dan analisis data

### Power BI
Digunakan untuk:
- Data visualization
- Dashboard development
- Business reporting

---

## 🔍 Tahapan Analisis

### 1. Data Understanding
Melakukan pemeriksaan terhadap:

- Struktur data
- Tipe data
- Kelengkapan data
- Konsistensi data

### 2. Data Cleaning

Tahapan pembersihan data meliputi:

- Identifikasi missing values
- Pemeriksaan inkonsistensi data
- Validasi nilai transaksi
- Persiapan data untuk analisis

### 3. Exploratory Data Analysis (EDA)

Analisis dilakukan berdasarkan:

- Tren penjualan bulanan
- Performa produk
- Performa wilayah
- Distribusi transaksi

### 4. Dashboard Development

Dashboard dikembangkan menggunakan Power BI untuk memvisualisasikan:

- Total Produk
- Total Wilayah
- Total Transaksi
- Total Penjualan
- Penjualan per Bulan
- Penjualan per Produk
- Penjualan per Wilayah
- Distribusi Produk dan Wilayah

---

## 📊 Dashboard

![Dashboard](dashboard/dashboard.png)

---

## 💡 Insight Utama

### 1. Januari Menjadi Bulan dengan Penjualan Tertinggi

Januari mencatat total penjualan sebesar Rp72,9 juta dan menjadi periode dengan performa terbaik sepanjang periode pengamatan. Hal ini menunjukkan tingginya aktivitas pembelian pada awal tahun.

### 2. Surabaya Menjadi Kontributor Penjualan Terbesar

Surabaya menghasilkan total penjualan sebesar Rp83,6 juta atau sekitar 24% dari total penjualan. Wilayah ini menjadi pasar dengan performa terbaik dibandingkan wilayah lainnya.

### 3. Electric Kettle Merupakan Produk dengan Penjualan Tertinggi

Electric Kettle menghasilkan penjualan sebesar Rp88,1 juta dan menjadi produk dengan kontribusi pendapatan terbesar dalam dataset.

### 4. Penjualan Mengalami Fluktuasi Selama Periode Pengamatan

Setelah mencapai puncak pada Januari, penjualan mengalami penurunan signifikan pada Februari sebelum kembali meningkat pada bulan-bulan berikutnya.

### 5. Portofolio Produk Relatif Seimbang

Meskipun Electric Kettle menjadi produk unggulan, produk lainnya juga memberikan kontribusi yang signifikan terhadap total penjualan sehingga risiko ketergantungan pada satu produk relatif rendah.

---

## 🚀 Rekomendasi

### Strategi Produk
- Memastikan ketersediaan stok Electric Kettle untuk memenuhi permintaan pasar.
- Mengembangkan strategi cross-selling dan bundling dengan produk lain.

### Strategi Wilayah
- Mempertahankan dan meningkatkan penetrasi pasar di Surabaya.
- Mengadopsi strategi pemasaran yang berhasil di Surabaya ke wilayah lain.

### Strategi Penjualan
- Mengevaluasi penyebab penurunan penjualan pada Februari.
- Menyusun program promosi pada periode dengan performa rendah.

### Strategi Analitik
- Mengumpulkan data pelanggan yang lebih detail untuk analisis segmentasi pelanggan di masa mendatang.
- Mengembangkan dashboard monitoring secara berkala untuk mendukung pengambilan keputusan.

---

## 📁 Struktur Repository

```text
├── dataset/
│   └── dataset_penjualan_kotor.csv
│
├── sql/
│   └── query_analysis.sql
│
├── powerbi/
│   └── Sales_Analysis_Dashboard.pbix
│
├── dashboard/
│   └── dashboard.png
│
└── README.md
```

---

## 🏆 Informasi Sertifikasi

| Keterangan | Informasi |
|------------|------------|
| Skema Sertifikasi | Analis Data Muda (Associate Data Analyst) |
| Lembaga Sertifikasi | LSP Sertifa Teknologi Informasi Indonesia |
| Tanggal Uji Kompetensi | 19 Desember 2025 |
| Hasil | Kompeten |

---

## 👨‍💻 Author

**Septa Bagas Setyawan**

Mahasiswa Pendidikan Teknik Elektronika  
Universitas Negeri Yogyakarta

- LinkedIn: [www.linkedin.com/in/septa-bagas-setyawan](https://www.linkedin.com/in/septabagass/)

---

⭐ Proyek ini dibuat sebagai bagian dari portofolio Data Analyst untuk menunjukkan kemampuan dalam data cleaning, data analysis, data visualization, dan penyusunan insight bisnis menggunakan SQL dan Power BI.
