# Laravel-API

Simple app builded on laravel 5.7.


## Installation

```bash

git clone https://github.com/ghost717/laravel-api.git newProjectName

cd newProjectName

config .env file


>> run developement

php artisan serve

```

## Build Info

```bash

>> install laravel 

composer create-project --prefer-dist laravel/laravel blog


>> install voyager

composer require tcg/voyager


>> migration bug

/app/Providers/AppServiceProvider.php
Schema::defaultStringLength(191);

>> sample db

php artisan voyager:install --with-dummy


>> make auth routing / views

php artisan make:auth


```

