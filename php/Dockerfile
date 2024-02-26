# PHP Dockerfile
FROM php:8.3-fpm

# 安装必要的扩展
RUN docker-php-ext-install pdo_mysql

# 将你的应用代码复制到容器中
COPY app/ /var/www/html