FROM php:7.4-apache
COPY . /myapp
WORKDIR /myapp

RUN docker-php-ext-install pdo pdo_mysql
RUN apt install php libapache2-mod-php php-mysql

CMD [ "php", "./todo_list.php" ]

EXPOSE 9090
