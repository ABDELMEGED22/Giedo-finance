ARG imageVariant="latest"
ARG greeting="Welcome to Giedo-finance!"
FROM mcr.microsoft.com/devcontainers/base:${imageVariant}

WORKDIR /usr/local/etc

RUN echo "${greeting}" > greeting.txt

LABEL greeting="${greeting}"