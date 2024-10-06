FROM nginx:alpine

COPY docker/nginx/default.conf /etc/nginx/conf.d

COPY .env.example /var/www/.env
COPY . /var/www