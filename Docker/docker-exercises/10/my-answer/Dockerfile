FROM debian:trixie

USER root

RUN apt-get update && apt-get -y install curl unzip glibc-source groff less python3

WORKDIR /root

RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" && \
    unzip awscliv2.zip && \
    ./aws/install && \
    rm -rf awscliv2.zip ./aws && \
    apt-get autoremove -y curl unzip

ENTRYPOINT ["/usr/local/bin/aws"]
