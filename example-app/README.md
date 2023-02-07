
1. Install Composer
2. Set php
3. Download Laravel terbaru
4. Jalankan laravel dengan perintah php artisan serve
5. Ganti file konfigurasi .env untuk koneksi ke database
6. Buat model table dan migrasi dengan perinta php artisan make:model Post -m dan atur pada file database/migration/ up()
7. Jalankan php artisan migrate agar table dan field terbuat
8. Buat Models, Controller dan View bisa gunakan blade template

Models: app/Models/Post.php
Controller: app/http/Controllers/PostController.php
View: resources/views/posts/
Routing: routes/web.php

