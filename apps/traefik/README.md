## Build certificats for a local ssl
mkcert -instal
mkcert -cert-file certs/local-cert.pem -key-file certs/local-key.pem "docker.localhost" "*.docker.localhost"

