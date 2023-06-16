FROM nginx

COPY ./nginx/*.conf /etc/nginx/conf.d/

RUN apt-get update -y && apt-get upgrade -y

RUN apt-get install -y php php-fpm

VOLUME [./:/usr/share/nginx/html]

EXPOSE 3000