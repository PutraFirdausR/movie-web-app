<div align="center">
  <h1>🎬 Movie Web App</h1>
  <p>Aplikasi web sederhana untuk mencari dan melihat informasi film favoritmu, dibangun murni dengan HTML, CSS, dan JavaScript.</p>

  <p>
    <a href="https://github.com/PutraFirdausR/movie-web-app/stargazers">
      <img src="https://img.shields.io/github/stars/PutraFirdausR/movie-web-app?style=social" alt="Stars" />
    </a>
    <a href="https://github.com/PutraFirdausR/movie-web-app/network/members">
      <img src="https://img.shields.io/github/forks/PutraFirdausR/movie-web-app?style=social" alt="Forks" />
    </a>
  </p>
</div>

<br />

## 📌 Tentang Proyek

**Movie Web App** adalah proyek *frontend* interaktif yang memungkinkan pengguna untuk melakukan pencarian judul film dan melihat detailnya (seperti poster, tahun rilis, dan plot cerita). Data film diambil secara *real-time* menggunakan *Fetch API* dari penyedia data film pihak ketiga.

Proyek ini sangat cocok untuk melatih pemahaman dasar DOM Manipulation, Asynchronous JavaScript (Async/Await & Fetch), dan desain antarmuka yang responsif.

## 🚀 Fitur Utama

* **Pencarian Film:** Ketik judul film dan dapatkan hasil pencarian secara instan.
* **Detail Informasi:** Menampilkan poster film, judul, tahun rilis, dan detail lainnya.
* **Desain Responsif:** Tampilan yang menyesuaikan ukuran layar, nyaman dibuka di PC maupun HP.
* **Ringan & Cepat:** Berjalan langsung di *browser* tanpa perlu kompilasi tambahan.

## ⚙️ Teknologi yang Digunakan

* **HTML5** - Untuk kerangka dan struktur halaman.
* **CSS3** - Untuk memberikan gaya, *layout*, dan animasi visual.
* **JavaScript (ES6+)** - Untuk logika aplikasi, manipulasi DOM, dan memanggil API (Fetch API).

## 🛠️ Cara Penggunaan

Karena proyek ini menggunakan HTML, CSS, dan JS murni, kamu tidak perlu menginstal *module* atau *library* apa pun.

### Langkah-langkah:

1.  **Clone repositori ini:**
    ```bash
    git clone [https://github.com/PutraFirdausR/movie-web-app.git](https://github.com/PutraFirdausR/movie-web-app.git)
    ```
2.  **Masuk ke folder proyek:**
    ```bash
    cd movie-web-app
    ```
3.  **Jalankan aplikasi:**
    Cukup klik ganda pada file `index.html` untuk membukanya di *browser* bawaanmu.
    *(Alternatif: Gunakan ekstensi "Live Server" di VS Code untuk pengalaman yang lebih baik).*

### 🔑 Pengaturan API Key (Jika Menggunakan API Eksternal)
Jika aplikasi ini mengambil data dari API seperti OMDB atau TMDB, pastikan kamu mengganti `API_KEY` di dalam file `script.js` (atau file JS milikmu) dengan API Key milikmu sendiri.
```javascript
// Contoh di file script.js
const API_KEY = 'masukkan_api_key_kamu_di_sini';
