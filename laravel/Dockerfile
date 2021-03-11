FROM php:7.4-alpine

COPY --from=mlocati/php-extension-installer /usr/bin/install-php-extensions /usr/local/bin/

RUN install-php-extensions cli pgsql fpm bcmath bz2 intl gd mbstring mysql zip json pdo http redis curl readline xml cgi raphf propro

