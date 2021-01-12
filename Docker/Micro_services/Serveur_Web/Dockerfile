FROM ubuntu:latest
RUN apt-get update -y \
&& apt-get install nginx -y \
&& apt-get clean
VOLUME /var/www/html
ENTRYPOINT ["nginx", "-g", "daemon off;"]
