FROM alpine:latest
RUN set -e; \
 apk update && \
 apk upgrade && \
 apk add vim;

ENTRYPOINT vim

# docker build -t ex00 .
#docker run -ti --rm ex00
