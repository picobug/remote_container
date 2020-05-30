FROM node:lts-alpine
RUN sed -i -e 's/http:\/\/dl-cdn.alpinelinux.org\/alpine/https:\/\/alpine.global.ssl.fastly.net\/alpine/g' /etc/apk/repositories && apk add --no-cache git && rm -rf /tmp/* /var/cache/apk/*
