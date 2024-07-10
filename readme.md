# Sonarqube community edition

Generate ssl certificate

```sh
openssl req -x509 -nodes -newkey rsa:2048 -keyout ssl.key.pem -out ssl.cert.pem -sha256 -days 365 \
    -subj "/C=GB/ST=London/L=London/O=Alros/OU=IT Department/CN=localhost"
```
