# 🚲 Divvy Analysis for Google Data Analytics Capstone – Case Study 1 With R
## How Does a Bike-Share Navigate Speedy Success?

### 📘 Deskripsi
Repositori ini berisi hasil analisis proyek akhir (Capstone Project) dari **Google Data Analytics Professional Certificate**, dengan studi kasus pertama:  
> *“How Does a Bike-Share Navigate Speedy Success?”*

Analisis dilakukan terhadap data Divvy Bike Share untuk memahami pola penggunaan antara **casual riders** dan **annual members**, serta memberikan **rekomendasi strategis** berdasarkan insight yang diperoleh dari data.

---

### 🧩 Tujuan Proyek
1. Memahami perbedaan perilaku pengguna casual dan member.  
2. Mengidentifikasi tren waktu, durasi, dan pola perjalanan.  
3. Memberikan saran berbasis data untuk meningkatkan konversi casual riders menjadi members.  

---

### 🛠️ Tools dan Bahasa yang Digunakan
- **RStudio** (R Markdown)
- **tidyverse**, **lubridate**, **ggplot2**
- **Git & GitHub** untuk version control
- **Excel / Google Sheets** untuk praproses awal

---

### 📂 Struktur Folder

<h2 align="left">📁 Struktur Folder Proyek</h2>

<div align="left">

<table>
<tr>
<td width="35%"><b>📦 Folder / File</b></td>
<td><b>Deskripsi</b></td>
</tr>

<tr>
<td><code>data_raw/</code></td>
<td>📊 <b>Data mentah dari Divvy</b> (tidak diunggah karena ukuran besar).  
Tersedia dalam format <code>.zip</code> melalui tautan eksternal yang disertakan di laporan.</td>
</tr>

<tr>
<td><code>data_clean/</code></td>
<td>🧹 <b>Data hasil pembersihan</b> — file CSV yang siap untuk analisis.</td>
</tr>

<tr>
<td><code>scripts/</code></td>
<td>💻 <b>Kode R</b> untuk proses pembersihan data, eksplorasi, dan visualisasi.  
Menggunakan library seperti <code>tidyverse</code>, <code>lubridate</code>, dan <code>ggplot2</code>.</td>
</tr>

<tr>
<td><code>plots/</code></td>
<td>📈 <b>Hasil visualisasi</b> — seluruh grafik dalam format <code>.png</code>.</td>
</tr>

<tr>
<td><code>reports/</code></td>
<td>📝 <b>Laporan akhir</b> dalam format <code>.Rmd</code>, <code>.docx</code>, dan <code>.pdf</code>.</td>
</tr>

<tr>
<td><code>.gitignore</code></td>
<td>🚫 Menyimpan daftar file yang dikecualikan dari versi kontrol Git  
(seperti data mentah, cache, dan file sementara).</td>
</tr>

<tr>
<td><code>divvy-analysis.Rproj</code></td>
<td>⚙️ File konfigurasi proyek RStudio — menjaga konsistensi lingkungan kerja.</td>
</tr>

<tr>
<td><code>README.md</code></td>
<td>📚 Dokumentasi utama proyek — menjelaskan alur kerja, struktur folder, dan hasil analisis.</td>
</tr>

</table>
</div>

---

✨ <i>Struktur ini dirancang mengikuti prinsip <b>reproducible data analysis</b>:  
memisahkan data, kode, hasil visualisasi, dan laporan agar analisis dapat diulang dan diverifikasi dengan mudah.</i>




---

### 📁 Dataset
Karena ukuran data melebihi batas GitHub (100 MB), file CSV tidak disertakan.  
Dataset lengkap dapat diunduh melalui tautan berikut:

👉 [Unduh Dataset di Posit Cloud](https://posit.cloud/content/11241914?idle=1761278638517)

> Studi kasus ini telah diujikan di `RStudio` / `Posit Cloud` dengan URL di atas.

---

### 📊 Hasil Utama
- File analisis utama: `cyclictic_full_analysis_with_r.Rmd`  
- Laporan akhir: `cyclictic_full_analysis_with_r.docx`  
- Visualisasi pembersihan data: `plots/komparasi_sebelum_sesudah.png`

---

### 👤 Penulis
**Febri Supriadi** 
**[GCC x Telkom 2025]** 
📍 TIF DIstrik Kalimantan Barat, Pontianak, Indonesia  
📅 Oktober, 2025  
🔗 [GitHub Repository](https://github.com/febrisupriadi/divvy-analysis-for-google-data-analytics-capstone-cs1-how-does-a-bike-share-navigate-speedy-success-)

---

### 🧾 Lisensi
Repositori ini dibuat untuk tujuan pembelajaran dan portofolio.  
Semua data bersumber dari **Divvy Bike Share (Motivate International Inc.)** melalui **Google Data Analytics Capstone dataset**.

---

### 🧠 Catatan
Beberapa file besar telah dihapus dari versi Git untuk mematuhi batas ukuran GitHub.  
Untuk menjalankan ulang analisis, pastikan Anda menaruh dataset mentah di folder: <td><code>data_clean/</code></td>


---

### 🚀 Terima kasih!
Jika repositori ini dapat bermanfaat bagi Anda, silakan ⭐️ berikan bintang pada proyek ini di GitHub.


