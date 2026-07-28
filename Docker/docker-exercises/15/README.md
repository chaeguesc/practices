# Description
Run the following containers and note some containers failed and exited with an error status.
Use the `docker inspect` command to show the exit status of only the failed containers.

Did you know that you can include conditionals in format statements?

## Run instructions

    docker run alpine date
    docker run alpine date1
    docker run alpine date2
    docker run alpine date


Respuesta:

docker ps -f status=exited