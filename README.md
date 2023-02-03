# Docker Laravel

## About the project

A dockerized laravel project

## Some of technologies used on the project

-   Docker
-   Docker-compose
-   Laravel
-   PHP
-   MySQL
-   Nginx


## How to run the project

Prerequisites: Docker

```bash
## Clone repository
git clone docker-laravel

## Enter on the project folder
cd docker-laravel

## Start the laravel project
docker-compose run --rm composer create-project laravel/laravel .

## Set the database configurations on .env file
DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

## Run the migrations
docker-compose run --rm  artisan migrate

## Start the project
docker-compose up -d server php mysql

```

# Autor

Matheus de Lino Ferreira

https://www.linkedin.com/in/matheus-de-lino-ferreira-7a3929187/
