ARG VERSION
FROM almalinux:${VERSION:-9}
RUN dnf install nginx -y
RUN mkdir /app
WORKDIR /app
RUN pwd
RUN useradd rajiv
ARG COURSE="DOCKER" \
    DURATION="10HRS"
RUN echo "$COURSE :$DURATION"
ENV COURSE=${COURSE}
USER rajiv
CMD["sleep", "1000"]
