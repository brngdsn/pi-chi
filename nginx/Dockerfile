FROM nginx
ENV NGINX_HOST
RUN mkdir /etc/nginx/sites-enabled
ADD default.conf /etc/nginx/conf.d/
ADD nginx.conf /etc/nginx/
ADD clock.conf /etc/nginx/sites-enabled/
# ADD eg.conf /etc/nginx/sites-enabled/
CMD ["nginx", "-g", "daemon off;"]
