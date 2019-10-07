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

## Commands

```bash

>> run developement

php artisan serve


>> make model

php artisan make:model Mypayments


>> make controller

php artisan make:controller Mypayments --resource


>> routing / make auth views

php artisan make:auth

```


## Deploy

```bash

composer install

>> composer install

generate key

>> php artisan key:generate

migrating DB schema

>> php artisan migrate

>> php artisan db:seed

or 

>> php artisan migrate --seed

```

- https://laraveldaily.com/how-to-deploy-laravel-projects-to-live-server-the-ultimate-guide/


