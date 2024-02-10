## Prerequisites

Untuk menjalankan project ini maka wajib memiliki beberapa program dengan versi minimal sebagai berikut :

-   PHP v.8.1.2 atau diatasnya
-   Composer v.2.5.8 atau diatasnya
-   Node.js v.18.17.1 atau diatasnya
-   NPM v.9.6.7 atau diatasnya
-   MySQL

#### Install dependencies

Jalankan command ini di terminal :

```
composer install

```

```
npm install

```

#### Setup environment variabel:

```
cp -i .env.example .env
```

#### Pada file .env isi variable dibawah sesuai konfigurasi mysql pada perangkat anda :

```
DB_CONNECTION=
DB_HOST=
DB_PORT=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=

```

#### Jalankan command ini untuk mengenerate key app

```
php artisan key:generate

```

#### Jalankan migration (Pastikan konfigurasi mysql pada .env sudah benar & sesuai)

```
php artisan migrate

```

### Menjalankan Seeder :

```
php artisan db:seed

```

#### Menjalankan aplikasi :

```
php artisan serve

```

### Jalankan command ini di terminal baru :

```
npm run dev

```

### Buka link ini di browser :

http://127.0.0.1:8000
