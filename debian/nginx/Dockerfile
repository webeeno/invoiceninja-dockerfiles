FROM nginx:alpine

# Remove default content and EXPOSE
RUN rm -rf /usr/share/nginx/html/*

COPY ./invoiceninja.conf /etc/nginx/conf.d/default.conf

EXPOSE 8008
