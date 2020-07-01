FROM nginx:alpine

# COPY nginx.conf /etc/nginx/nginx.conf
RUN rm /etc/nginx/conf.d/default.conf
COPY apps/*.conf /etc/nginx/conf.d/
