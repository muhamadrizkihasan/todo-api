<h2 id="installation">💻 Instalasi</h2>

1. Clone repository

```bash
git clone https://github.com/muhamadrizkihasan/todo_api
cd todo_api
composer install
cp .env.example .env
```

2. Konfigurasi database melalui file `.env`

```conf
DB_DATABASE=db_todo_api
```

3. Migrasi and symlink

```bash
php artisan key:generate
php artisan storage:link
php artisan migrate
```

4. Jalankan website

```bash
php artisan serve
```