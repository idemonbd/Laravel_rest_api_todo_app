This is a simple Laravel 7 Project. You can learn laravel basic CRUD here and also REst API. Its follows standard way to CRUD in Laravel Framework.
This repo only for entry level laravel lerners.

## Installation
Install dependencies via composer
```ssh
composer install
```
Update dependencies (Optional)
```ssh
composer install via composer
```
Copy .env.example file to new .env file
```ssh
cp .env.example .env
```
Setup Database Connection
```ssh
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=Lalavel
DB_USERNAME=root
DB_PASSWORD=secret
```
Migrate Database
```ssh
php artisan migrate:fresh --seed
```
