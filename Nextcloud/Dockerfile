FROM nextcloud:31.0.8-apache

RUN sed -i 's/Listen 80/Listen 8080/' /etc/apache2/ports.conf
RUN sed -i 's/<VirtualHost \*:80>/<VirtualHost \*:8080>/' /etc/apache2/sites-available/000-default.conf
RUN chgrp 0 -R /var/www/html
RUN chmod 770 -R /var/www/html
RUN chmod g+s /var/www/html
RUN echo 'DAS HIER IST NEU 3' > /etc/apache2/test.txt

EXPOSE 8080
