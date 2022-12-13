<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Install Laravel Application with Docker support

[Installation Guide](https://laravel.com/docs/9.x)

### Linux

> curl -s https://laravel.build/buil-a-rest-api-with-laravel | bash

> cd buil-a-rest-api-with-laravel

> ./vendor/bin/sail up

### Generate Customer & Invoice models

> ./vendor/bin/sail artisan make:model Customer --all

> ./vendor/bin/sail artisan make:model Invoice --all


### Prepare Cusomter & Invoice Factory & Seeder before migration

> ./vendor/bin/sail artisan migrate:fresh --seed

### Create V1\Customer resource

> ./vendor/bin/sail artisan make:resource V1\CustomerResource