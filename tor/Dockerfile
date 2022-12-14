FROM alpine:3.17.0
RUN apk add tor
COPY torrc /etc/tor/torrc
USER 100:100
CMD ["tor"]
