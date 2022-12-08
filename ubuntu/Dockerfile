FROM ubuntu:22.04
ENV DEBIAN_FRONTEND=noninteractive
RUN apt update
RUN apt install nodejs -y
RUN apt install npm -y
RUN npm install -g gulp-cli
RUN apt install curl -y
RUN apt install php-cli unzip -yq
RUN curl -sS https://getcomposer.org/installer -o /tmp/composer-setup.php
RUN php /tmp/composer-setup.php --install-dir=/usr/local/bin --filename=composer
ENTRYPOINT ["tail", "-f", "/dev/null"]