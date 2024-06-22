# Aplikasi Pelaporan Barang Rusak

Aplikasi ini adalah sistem pelaporan barang rusak berbasis API menggunakan Node.js. Pengguna dapat melaporkan barang yang rusak.

## Fitur

- Laporan barang rusak.
- Manajemen status laporan (menunggu, diproses, selesai, dll.).
- Autentikasi pengguna (opsional).
- Dokumentasi API yang jelas.

## Instalasi

Pastikan Anda telah menginstal Node.js dan npm di sistem Anda sebelum memulai.

1. **Clone Repository**
    ```bash
    git clone https://github.com/username/aplikasi-pelaporan-barang-rusak.git
    cd aplikasi-pelaporan-barang-rusak
    ```

2. **Instal Dependensi**
    ```bash
    npm install
    ```

3. **Konfigurasi Lingkungan**
    - Salin file `.env.example` menjadi `.env`:
      ```bash
      cp .env.example .env
      ```
    - Sesuaikan nilai-nilai dalam file `.env` sesuai dengan konfigurasi yang dibutuhkan (seperti pengaturan database, kunci API, dll.).

4. **Jalankan Migrasi Database (jika diperlukan)**
    - Jika Anda menggunakan database dan memerlukan migrasi, jalankan perintah migrasi menggunakan Sequelize atau alat migrasi yang sesuai:
      ```bash
      npx sequelize-cli db:migrate
      ```
    - Pastikan database telah siap sebelum menjalankan migrasi.

5. **Jalankan Server**
    - Setelah semua langkah di atas selesai, Anda dapat menjalankan server API dengan perintah:
      ```bash
      npm start
      ```
    - Aplikasi akan mulai berjalan, dan server akan aktif pada `http://localhost:3000` secara default, kecuali diatur sebaliknya dalam konfigurasi.

## Penggunaan

- Pastikan server API berjalan dengan baik.
- Gunakan dokumentasi API yang tersedia untuk mengetahui endpoint-endpoint yang ada, metode HTTP yang didukung, dan format permintaan dan respons yang diharapkan.

