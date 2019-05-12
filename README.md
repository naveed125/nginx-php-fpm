## Source
This is a fork of richarvey/nginx-php-fpm. Made some small changes to it for example added APCu support. Source is available at: https://github.com/naveed125/nginx-php-fpm

## Using the image
docker run -e DEPLOYMENT=development -d -p 80:80 naveed125/nginx-php-fpm:latest

## Building the image
docker build -t naveed125/nginx-php-fpm:latest .

## Push to public docker repo
docker push naveed125/nginx-php-fpm:latest
