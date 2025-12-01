ARG VERSION
FROM almalinux:${VERSION:-9}
RUN dnf install nginx -y
RUN mkdir /app
WORKDIR /app
RUN pwd
RUN useradd rajiv
ARG COURSE="DOCKER" \
    DURATION="10HRS"
ENV COURSE=${COURSE}
USER rajiv
