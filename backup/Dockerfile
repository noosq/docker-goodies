FROM alpine:3

RUN apk --no-cache add \
    gnupg \
    haveged \
    tini

ENTRYPOINT ["/sbin/tini", "--"]
