## Images
<b>nginx</b> (nginx:alpine)<br>
<b>php-fpm</b> (php:8.1.0-fpm) - Dockerfile<br>
<b>mysql</b> (mysql:latest)<br>

## Steps
1. <code>cd /www</code>
2. <code>git clone https://github.com/laravel/laravel.git .</code>
3. <code>cp .env.example .env</code>

## .env file
<code>DB_HOST=db</code><br>
<code>DB_DATABASE=docker_laravel</code><br>
<code>DB_USERNAME=root</code><br>
<code>DB_PASSWORD=123<br></code><br>
