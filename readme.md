# Laravel App Basis

This is a bootstrap project containing all the steps I do before starting a new project. 
The goal is to speed this process up and ultimately automate it.

The laravel version used is v5.2.35.

### Instructions

- Clone and delete .git directory to have a clean fork
- Run composer install
- Run `cp .env.example .env` to copy `.env.example` to `.env`
- Run `php artisan key:generate`
- Run `php artisan app:name Some\\Namespace`
- Add project in circleci.com
