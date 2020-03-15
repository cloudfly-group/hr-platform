<p align="center"><img src="./src/website/public/assets/images/logomark.min.svg" width="400"></p>

# Human Resources Flatform

## About Us

## Setup
1. docker-compose build
2. docker-compose up -d
3. docker-compose exec app cp .env.example .env
4. docker-compose exec app composer install
5. docker-compose exec nodejs npm install
6. docker-compose exec app php artisan key:generate
7. docker-compose exec app php artisan migrate
8. docker-compose exec app php artisan db:seed
9. docker-compose exec app php artisan config:cache

## Config
- Open file hosts and add "127.0.0.1 hr-platform.local" into it.
