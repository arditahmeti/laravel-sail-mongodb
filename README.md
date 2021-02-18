# Laravel Sail Mongodb

This is a simple [Laravel](https://laravel.com/docs/8.x) application created with its built-in
solution [Sail](https://laravel.com/docs/8.x/sail) for running your Laravel project
using [Docker](https://www.docker.com/), using the command below:

`curl -s https://laravel.build/laravel-sail-mongodb | bash`

The application has its necessary configuration in order to run mongodb container as well.

## Requirements for building and running the application

- [Composer](https://getcomposer.org/download/)
- [Docker](https://docs.docker.com/get-docker/)

## Application Build and Run

After cloning the repository get into the laravel-sail-mongodb directory and run:

`composer install`

`cp .env.example .env`

`./vendor/bin/sail up`

## Then finally test the application

Go to [http://localhost](http://localhost) in order to see the application running.
