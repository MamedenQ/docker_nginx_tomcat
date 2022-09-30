FROM nginx:latest

RUN rm -f /etc/nginx/conf.d/*
COPY conf.d/nginx.conf /etc/nginx/conf.d
COPY nginx.conf /etc/nginx
