## Source
This is a fork of richarvey/nginx-php-fpm. One big difference is that I've added APCu support. Source is available at: https://github.com/naveed125/nginx-php-fpm

## Using the image
docker run -e DEPLOYMENT=development -d -p 80:80 naveed125/nginx-php-fpm:latest

