## Source
This is a fork of richarvey/nginx-php-fpm. Made some small changes:
 
 * Added APCu
 * Removed maxmind geoip stuff
 * Added igbinary

## Docker Image

Image is available at https://cloud.docker.com/repository/docker/naveed125/nginx-php-fpm

## Using the image
```
docker run -e DEPLOYMENT=development -d -p 80:80 naveed125/nginx-php-fpm:latest
```

## Building the image
Remeber to match the PHP version in the tag

```
docker build -t naveed125/nginx-php-fpm:7.3.9 .
```

## Push to public docker repo
Remember to match the PHP version in the tag

```
docker push naveed125/nginx-php-fpm:7.3.9
```
