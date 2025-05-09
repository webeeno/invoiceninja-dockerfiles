FROM nginx:alpine

# Remove default content and EXPOSE
RUN rm -rf /usr/share/nginx/html/*

COPY ./invoiceninja.conf /etc/nginx/conf.d/default.conf
COPY ../docker/app /usr/share/nginx/html

EXPOSE 8008
