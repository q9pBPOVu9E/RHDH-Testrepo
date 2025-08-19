FROM nextcloud:31.0.8-apache

RUN sed -i 's/:80/:8080/g' /etc/apache2/ports.conf /etc/apache2/sites-available/*.conf

EXPOSE 8080
