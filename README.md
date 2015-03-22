# docker-laravel
Laravel 5 with Dockerized PHP-FPM, MySQL and nginx using docker-compose

## Usage

### Get Composer

    docker-compose run --rm phpnginx curl -O https://getcomposer.org/installer
    docker-compose run --rm phpnginx php installer

### Install Laravel 5 using Composer

	docker-compose run --rm phpnginx php composer.phar create-project laravel/laravel src --prefer-dist