[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/bayubimantarar/docker-jenkins-laravel/pulls)

# Docker Laravel Jenkins
Docker Laravel Jenkins adalah sebuah wadah untuk berlatih DevOps.

## Installation
1. Clone repository
2. Install dependencies composer

        composer install --no-dev #for production

        composer install #for development

3. Copy file environment

        cp .env.example .env

4. Generate application key

        php artisan key:generate
5. Migrate table
    
        php artisan migrate

6. Seed data to table
    
        php artisan db:seed

## Test
Test with phpunit

    ./vendor/bin/phpunit
