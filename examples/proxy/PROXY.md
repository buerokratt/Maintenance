# Proxies

This directory contains nginx and Caddyfile examples for reverse proxies.

### Ruuter examples

In [Ruuter examples](Ruuter) we forward requests for /v1/ to Ruuter v1 and /v2/ to Ruuter v2.

In the example our Ruuter v1 runs on `192.168.1.201:8081` and Ruuter v2 on `192.168.1.201:8082`.

*Note! nginx.conf: trailing `/` in `proxy_pass` is important!*

