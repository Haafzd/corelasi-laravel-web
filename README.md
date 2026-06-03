# CORELASI Laravel Web

Aplikasi web CORELASI berbasis Laravel untuk dashboard guru dan manajemen aktivitas pembelajaran.

## Fitur utama
- Login guru
- Dashboard guru
- Jadwal mengajar
- Teaching journal / BAP
- Absensi
- Materi pembelajaran
- Tugas dan submission
- Nilai / assessment
- Notifikasi
- API mobile

## Tech stack
- Laravel
- PHP
- Blade
- Vite
- MySQL/MariaDB atau SQLite untuk pengembangan lokal

## Quick start
```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run dev
php artisan serve
```

## Struktur penting
- `app/Http/Controllers` — controller web dan API
- `app/Models` — model domain pembelajaran
- `routes/` — route aplikasi
- `resources/` — view dan asset frontend
