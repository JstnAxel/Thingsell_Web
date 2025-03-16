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
- MySQL / PostgreSQL (Database)
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

### 2. Instalasi Backend (Laravel)
```sh
  cd backend
  composer install
  cp .env.example .env
  php artisan key:generate
  php artisan migrate --seed
  php artisan serve
```

### 3. Instalasi Frontend (React)
```sh
  cd ../frontend
  npm install
  npm run dev
```

## Konfigurasi
**Database**: Sesuaikan konfigurasi database di `.env` Laravel.





