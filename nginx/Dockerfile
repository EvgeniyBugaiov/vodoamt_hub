FROM nginx:1.19.0-alpine

RUN rm /etc/nginx/conf.d/default.conf
COPY admin.conf /etc/nginx/conf.d
COPY api.conf /etc/nginx/conf.d
