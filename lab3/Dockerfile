FROM debian:13-slim 

LABEL version="1.0" \
 preformer="" \
 group=""

USER root

WORKDIR /opt/lab3

RUN apt-get update \
 && apt-get install -y --no-install-recommends nginx \
 && rm -rf /var/lib/apt/lists/*

COPY ./index.html /var/www/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

