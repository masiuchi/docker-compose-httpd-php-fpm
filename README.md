# docker-compose-httpd-php-fpm
docker-compose.yml to start httpd and php-fpm

## usage

```bash
# start httpd and php-fpm (PHP 7.3)
$ docker-compose up

# start httpd and php-fpm (PHP 7.2)
$ PHP_VERSION=7.2 docker-compose up

# open phpinfo page via web browser
$ open http://localhost:8080
```
