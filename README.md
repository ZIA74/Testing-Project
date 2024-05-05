
## Setup

```
set .env file 
composer install
php artisan optimize:clear
php artisan migrate --seed
php artisan passport:client --personal
test api
```