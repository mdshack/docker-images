FROM alpine:latest

RUN apk add --no-cache dnsmasq=2.89-r6

COPY dnsmasq.conf /etc/dnsmasq.conf

ENTRYPOINT dnsmasq -k
