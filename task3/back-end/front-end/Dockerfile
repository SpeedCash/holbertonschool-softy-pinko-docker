# Forward 5252 to 5252
FROM nginx

WORKDIR /app

COPY ./softy-pinko-front-end/ /var/www/html/softy-pinko-front-end

COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

EXPOSE 9000
