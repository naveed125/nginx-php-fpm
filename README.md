## Source
This is a fork of richarvey/nginx-php-fpm. Made some small changes to it for example added APCu, redis and igbinary support. 
Source is available at: https://github.com/naveed125/nginx-php-fpm

## Using the image
```
docker run -e DEPLOYMENT=development -d -p 80:80 naveed125/nginx-php-fpm:latest
```

## Building the image
Match the PHP version in the tag

```
docker build -t naveed125/nginx-php-fpm:7.3.9 .
```

## Push to public docker repo
Match the PHP version in the tag
```
docker push naveed125/nginx-php-fpm:7.3.9
```
