# Use the official PHP image
FROM php:8.2-apache

# Enable PHP extensions commonly used in projects
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

# Copy all files to the Apache server root
COPY . /var/www/html/

# Expose port 80
EXPOSE 80
