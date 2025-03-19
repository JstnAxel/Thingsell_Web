# E-Commerce Platform

## Deskripsi
Proyek ini adalah platform e-commerce yang dikembangkan menggunakan **Laravel** untuk backend dan **React** untuk frontend. Platform ini menyediakan **Vendor Panel** bagi penjual untuk memposting produk beserta variasinya. Selain itu, tersedia fitur pencarian produk, autentikasi pengguna, dan berbagai variasi produk berdasarkan kategori.

## Fitur Utama
- **Vendor Panel**: Penjual dapat menambahkan, mengedit, dan menghapus produk serta variasinya.
- **Autentikasi Pengguna**: Login, registrasi, dan manajemen akun menggunakan Laravel Breeze.
- **Pencarian Produk**: Fitur search untuk memudahkan pencarian produk yang diinginkan.
- **Kategori dan Variasi Produk**: Produk dapat memiliki berbagai variasi seperti ukuran, warna, dll.
- **Keranjang Belanja**: Pengguna dapat menambahkan produk ke keranjang sebelum melakukan checkout.
- **Checkout dan Pembayaran**: Integrasi pembayaran online untuk transaksi.
- **Dashboard Admin**: Untuk mengelola pengguna, produk, dan transaksi.

## Teknologi yang Digunakan
### Backend (Laravel)
- Laravel (v12)
- Laravel Breeze (untuk autentikasi)
- MySQL (Database)
- Filament

### Frontend (React)
- React (v18+)
- Redux (State Management)
- Tailwind CSS (Styling)
- Daisyui

## Instalasi
### 1. Clone Repository
```sh
  git clone https://github.com/username/repository-name.git
  cd repository-name
```

### 2. Instalasi
```sh
  cd repository-name
  composer install
  npm install
  cp .env.example .env
  Ubah APP_URL=http://127.0.0.1:8000
  php artisan key:generate
  php artisan migrate --seed
  npm run dev
