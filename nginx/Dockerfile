FROM nginx:alpine

RUN mkdir /www \
    && chown -R nginx:nginx /www \
    && touch /var/log/nginx/error.log \
    && touch /var/log/nginx/access.log \
    && chown -R nginx:nginx /var/log/nginx

WORKDIR /var/www

EXPOSE 80