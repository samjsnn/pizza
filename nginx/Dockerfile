FROM nginx

# Overwrite Default Configuration
COPY ./Proxy/default.conf /etc/nginx/conf.d/default.conf

COPY ./Proxy/includes/ /etc/nginx/includes/

COPY ./Proxy/ssl/ /etc/ssl/certs/nginx/
