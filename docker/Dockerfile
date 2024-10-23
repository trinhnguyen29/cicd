FROM wyveo/nginx-php-fpm:php81
# Get Composer
COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer
# Get NodeJS
COPY --from=node:latest /usr/local/bin /usr/local/bin
# Get npm
COPY --from=node:latest /usr/local/lib/node_modules /usr/local/lib/node_modules