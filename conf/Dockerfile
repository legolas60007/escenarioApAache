FROM php:7.4.12-apache
RUN apt-get clean && apt-get update; 
RUN a2enmod auth_digest auth_basic status info rewrite headers
RUN service apache2 restart;


