FROM wordpress:5.9-php7.4-fpm-alpine

COPY ./wp-content /var/www/html/wp-content

RUN chmod -R 755 /var/www/html/
RUN chown www-data:www-data -R /var/www/html/

VOLUME /var/www/html
