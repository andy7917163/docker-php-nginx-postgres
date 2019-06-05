Docker-compose php-nginx-postgres
===
![author](https://img.shields.io/badge/author-Andy-blue.svg)

## Description

Docker Compose configuration to run PHP 7.2 with Nginx, PHP-FPM, PostgreSQL.

## Install prerequisites

Install docker for your enviorment

- [docker](https://docs.docker.com/install/)
- [docker-compose](https://docs.docker.com/compose/install/)

## How to use

Steps to work

1. Edit `.env ` , change `APP_CODE_PATH_HOST` to your application root path
    ```
    APP_CODE_PATH_HOST=../
    ```
2. Check and up docker-compose
    ```
    docker -v
    docker-compose -v
    docker-compose up -d
    ```
3. Then open http://php-docker.local:8080 
> Change the domain name to your setting domain