# Description

In the docker-compose file add a delay before a service starts

## Run instructions


services:
  httpd:
    image: httpd:alpine
    container_name: prueba1
    ports:
      - "80:80"
    command: ["sh", "-c", "sleep 5 && httpd-foreground"]

