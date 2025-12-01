# 🍰 Loyalty Point System - Toko Bolu Kukus

Sistem manajemen loyalitas pelanggan berbasis web yang dirancang untuk toko retail (UMKM). Aplikasi ini memungkinkan kasir untuk memberikan poin berdasarkan nominal belanja, dan pelanggan untuk menukarkan poin dengan hadiah.

## 🚀 Fitur Utama

- **Role-Based Access:** Pemisahan antarmuka antara Admin/Kasir dan Member/Pelanggan.
- **Real-time Point Tracking:** Poin terupdate otomatis setelah transaksi.
- **Mobile Friendly:** Desain responsif untuk diakses via smartphone pelanggan.
- **Secure Authentication:** Login aman menggunakan nomor HP (via Supabase Auth).

## 🛠️ Teknologi yang Digunakan

- **Frontend:** HTML, CSS, JavaScript (Vanilla/Framework)
- **Backend/Database:** Supabase (PostgreSQL)
- **Deployment:** Vercel

## 📦 Cara Instalasi & Penggunaan (Local Development)

Jika Anda ingin menjalankan proyek ini di komputer Anda sendiri, ikuti langkah berikut:

Clone Repository
   ```bash
   git clone [https://github.com/username-anda/loyalty-bolu-kukus.git](https://github.com/username-anda/loyalty-bolu-kukus.git)

Setup Database (Supabase)

Buat project baru di Supabase.

Buat tabel profiles (untuk user data) dan transactions (untuk riwayat poin).

Dapatkan SUPABASE_URL dan SUPABASE_ANON_KEY.

Konfigurasi Environment

Buat file .env atau masukkan kredensial Supabase langsung ke dalam file konfigurasi JS Anda (jika client-side only).

Jalankan Aplikasi

Buka file index.html di browser Anda, atau gunakan Live Server.
