FROM php:7-apache
RUN apt-get update && apt-get install -y \
	vim \
	telnet \
&& docker-php-ext-install mysqli \ 
&& docker-php-ext-install sockets