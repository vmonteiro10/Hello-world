FROM php:7.2.19-apache
COPY src/ /var/www/html/
ADD ../docker_test.sh /
ENTRYPOINT ["/bin/bash", "../docker_test.sh"]
EXPOSE 80

