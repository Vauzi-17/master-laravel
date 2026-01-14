# Master Laravel

Aplikasi Laravel sederhana untuk pembelajaran.

## Kebutuhan Sistem

- Laragon
- PHP 8.2.29
- Composer
- MySQL
- phpMyAdmin

## Instalasi

Pastikan Laragon sudah terinstall dan berjalan.

1. Clone repository
```bash
git clone https://github.com/Vauzi-17/master-laravel.git
cd master-laravel
```

2. Salin file environment
```bash
copy .env.example .env
```

5. Generate application key
```bash
php artisan key:generate
```

6. Jalankan migrasi database
```bash
php artisan migrate
```

7. Jalankan server development
```bash
php artisan serve
```