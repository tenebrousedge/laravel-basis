# Laravel App Basis

This is a bootstrap project containing all the steps I do before starting a new project. 
The goal is to speed this process up and ultimately automate it.

The laravel version used is v5.2.35.

### Instructions

- Clone and delete .git directory to have a clean fork: `rm -rf .git`
- Run `composer install`

- Initialize laravel project:
  - Copy `.env.example` to `.env`: `cp .env.example .env`
  - Run `php artisan key:generate`
  - Run `php artisan app:name Some\\Namespace`
- Run ide helper
  - Run `php artisan ide-helper:generate`
  - Run `php artisan ide-helper:meta` (for phpstorm)
- Push project to github
  - Run `git init`
  - Run `git add .`
  - Run `git commit -m "first commit"`
  - Create new project in Github
  - You add the remote git repository and push (follow github instructions)
- Setup bugsnag
  - Enter your bugsnag key in `config/bugsnag.php`
- Add project in circleci.com:
  - Go to [circleci dashboard](https://circleci.com/dashboard) and select "Add projects"
