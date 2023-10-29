FROM nginx

RUN apt-get update && apt-get install -y vim

RUN rm ./etc/nginx/nginx.conf
COPY confs/nginx.conf ./etc/nginx/