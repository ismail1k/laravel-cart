# laravel-api-cart
A simple Shopping Cart system for e-commerce projects. Compatible with Laravel API.

## Installation
First, add `ismail1k/laravel-api-cart` package to your Laravel project using Composer:
```shell
composer require "ismail1k/laravel-api-cart"
```
then add the follow line to `providers` in `config/app.php`:
```php
Ismail1k\LaravelApiCart\CartServiceProvider::class,
```
Next step, add some published files like migrations: 
```shell
php artisan vendor:publish --provider="Ismail1k\LaravelApiCart\CartServiceProvider"
```
then run the follow line:
```shell
php artisan migrate
```

## Usage
