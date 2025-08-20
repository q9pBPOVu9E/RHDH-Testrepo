FROM nextcloud:31.0.8-apache

RUN sed -i 's/80/8080/' /etc/apache2/ports.conf \
 && sed -i 's/<VirtualHost \*:80>/<VirtualHost \*:8080>/' /etc/apache2/sites-available/000-default.conf


EXPOSE 8080
