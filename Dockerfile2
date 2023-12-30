FROM ubuntu
RUN apt update
RUN apt install apache2 -y
ADD . /vwr/www/html
ENTRYPOINT apachectl FOREGROUND
