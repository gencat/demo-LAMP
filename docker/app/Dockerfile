FROM gencatcloud/php:5.3.29

RUN apt-get update && apt-get install -y php5-mysql 

RUN apt-get update && apt-get install -y mysql-client

RUN apt-get update && apt-get install -y libmysqlclient-dev

RUN docker-php-ext-install pdo pdo_mysql

