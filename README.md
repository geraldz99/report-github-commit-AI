# 📊 GitHub Commit Reporter

**GitHub Commit Reporter** adalah ekstensi browser praktis yang dirancang untuk membantu *developer* membuat laporan pekerjaan harian secara otomatis berdasarkan riwayat *commit* di GitHub. Dengan dukungan AI, ekstensi ini akan menarik data *commit* Anda dan merangkumnya menjadi format laporan yang rapi, profesional, dan siap dikirim.

## ✨ Fitur Utama

- **Kategori Jam Kerja**: Pisahkan laporan aktivitas Anda berdasarkan jam **Kerja** 🏢 (reguler) atau **Lembur** 🌙 (overtime).
- **Filter Fleksibel**: Tarik data *commit* dengan mudah berdasarkan **Tanggal** tertentu dan **User GitHub** yang spesifik.
- **Laporan Berbasis AI**: Tidak perlu lagi merangkai kata manual. AI akan menganalisis pesan *commit* Anda dan menghasilkan deskripsi laporan otomatis yang mudah dipahami.
- **Cepat & Ringan**: Langsung diakses melalui *popup* ekstensi browser tanpa perlu membuka halaman web baru.

## 🚀 Cara Instalasi (Google Chrome / Microsoft Edge)

Untuk menginstal ekstensi ini menggunakan file `.crx`:

1. Unduh file `report-otomatis.crx` dari halaman *releases* atau *folder* proyek ini.
2. Buka browser Anda (Google Chrome atau Microsoft Edge).
3. Masuk ke halaman pengaturan ekstensi dengan mengetik `chrome://extensions/` (untuk Chrome) atau `edge://extensions/` (untuk Edge) di kolom URL, lalu tekan **Enter**.
4. Aktifkan **Developer mode** (Mode Pengembang) di pojok kanan atas halaman.
5. **Drag and Drop** (seret dan lepas) file `report-otomatis.crx` yang sudah Anda unduh tadi langsung ke tengah-tengah halaman ekstensi tersebut.
6. Akan muncul *pop-up* konfirmasi, klik **Add extension** (Tambahkan ekstensi).
7. Selesai! Ikon ekstensi **GitHub Commit Reporter** akan muncul di area toolbar browser Anda.

## 🛠️ Cara Penggunaan

1. Klik ikon ekstensi **GitHub Commit Reporter** di toolbar browser Anda.
2. Berada di tab **Buat Laporan**, pilih mode laporan yang sesuai (tombol **Kerja** atau **Lembur**).
3. Masukkan **Tanggal** aktivitas *commit* yang ingin dilaporkan.
4. Pilih atau ketik **User GitHub** (contoh: `geraldz99`).
5. Klik tombol hijau **🚀 Buat Laporan**.
6. Tunggu beberapa saat, dan **Hasil laporan AI** akan otomatis muncul di dalam kotak teks di bagian bawah.
7. Anda tinggal menyalin (*copy*) teks tersebut untuk dikirimkan sebagai laporan harian (Daily Standup/Report) Anda!

## ⚙️ Pengaturan Tambahan

Pada tab **Pengaturan** (Settings), Anda mungkin perlu memasukkan konfigurasi tambahan seperti:
- *Personal Access Token* GitHub (jika repositori bersifat *private*).
- API Key untuk layanan AI (OpenAI, Gemini, atau lainnya) yang digunakan untuk men-generate teks laporan.
