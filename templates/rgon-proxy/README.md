# rgon-proxy

RGON-Proxy is an Service including Nginx and Letsencrypt to proxy incoming Trafic to the related containers.

Related containers can be defined with following labels:

- `rgon.domain=mydomain.com`
- `rgon.port=80`
- `rgon.ssl='true'`
- `rgon.redirect=https`
