## Images
<b>nginx</b> (nginx:alpine)<br>
<b>php-fpm</b> (php:8.1.0-fpm) - Dockerfile<br>
<b>mysql</b> (mysql:latest)<br>

## Steps
1. <code>git clone https://github.com/laravel/laravel.git www</code>
2. <code>cd www</code>
3. <code>cp .env.example .env</code>

## .env file
<code>DB_HOST=db</code><br>
<code>DB_DATABASE=docker_laravel</code><br>
<code>DB_USERNAME=root</code><br>
<code>DB_PASSWORD=123<br></code><br>

## Docker Start
1. <code>docker-compose up -d</code>

## Laravel settings up
1. <code>docker-compose exec app composer update</code>
2. <code>docker-compose exec app php artisan key:generate</code>
3. <code>docker-compose exec app php artisan config:cache</code>
