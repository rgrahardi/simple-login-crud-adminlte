#simple-login-crud-adminlte

## First Time Setup
1. Cloning repository.
1. Pastikan folder berikut dapat ditulis oleh server web:
	1. `storage`
	1. `bootstrap/cache`
1. Run command `composer install`.
1. Run command `npm install`.
1. Run command `npm run dev` untuk dev atau `npm run prod` untuk production.
1. Copy `.env.example` menjadi `.env` dan sesuaikan isinya.
1. Run command `php artisan key:generate`.
1. Run command `php artisan migrate:fresh --seed`.
1. Run command `php artisan storage:link`.
1. Run command `php artisan laravolt:link`.
1. Run command `php artisan serve` atau gunakan valet lalu buka URL yang disediakan oleh konsol di browser.
