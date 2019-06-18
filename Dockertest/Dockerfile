FROM php:7.2.19-apache
COPY Dockertest/src/ /var/www/html/
EXPOSE 80
RUN docker build -t hello-world .
RUN docker run -p 80:80 hello-world
