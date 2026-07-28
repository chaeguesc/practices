# Description
What command will most quickly tell you what is contained in an Alpine Linux /etc/hosts file?

## Run instructions

RESPUESTA:

docker run --rm alpine:latest cat /etc/hosts

docker exec -ti test1 cat /etc/hosts