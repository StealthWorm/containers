FROM php:8-apache

WORKDIR /var/www/html/

COPY . .

EXPOSE 80
# dando permissões para o usuario no grupo a todos os arquivos do projeto
RUN chown -R www-data:www-data /var/www