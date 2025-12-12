FROM ubunut:latest

WORKDIR /app

RUN apt update -y 

RUN apt install apache2 -y   # root location /var/www/html

COPY .  /var/www/html

EXPOSE 80

CMD ["apache2ctl", "-D",  "FOREGROUND"]