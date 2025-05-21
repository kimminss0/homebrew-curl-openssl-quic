# Homebrew formula for curl with HTTP3 support

This package provides curl built with nghttp3 and OpenSSL's QUIC support in Homebrew.

```
brew tap kimminss0/curl-openssl-quic
brew install kimminss0/curl-openssl-quic/curl
```

## Test

```
$ curl -I --http3 https://cloudflare-quic.com
HTTP/3 200
date: Wed, 21 May 2025 07:48:31 GMT
content-type: text/html
content-length: 125959
priority: u=3,i=?0
server: cloudflare
cf-ray: 943278ce0efd29e1-FUK
alt-svc: h3=":443"; ma=86400
server-timing: cfExtPri
```
