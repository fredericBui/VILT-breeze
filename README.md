# Built a VILT project with Laravel Breeze 29/10/2022

Base on the https://laravel.com/docs/9.x/starter-kits tutoriel

## 1 - Create a Laravel project :

composer create-project laravel/laravel example-app

## 2 - Configure database :

Change informations in .env<br/>
DB_PORT=3306<br/>
DB_DATABASE=laravel<br/>
DB_USERNAME=root<br/>
DB_PASSWORD=<br/>

Puis réaliser la migration en BDD :<br/>
php artisan migrate

## 3 - Install Laravel Breeze

composer require laravel/breeze --dev

## 4 - Breeze Vue stacks

php artisan breeze:install vue

php artisan migrate
npm install
npm run dev

## 5 - Run Laravel

php artisan serve

## 6 - Try routes

Try \login & \register
