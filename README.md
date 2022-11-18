# nginx_config_reverse_proxy_ssl
![Nginx_Reverse_Proxy_SSL(1)](https://user-images.githubusercontent.com/33643615/202673538-1ae0b437-c8b2-41c4-8dad-b202ac4e68f7.png)

<h1>OverView</h1>

This Repository is a simple implementation of a reverse proxy and https configuration of self signed certificates as well as instructions to handle the preflight problem of react and 'Access-Control-Allow-Origin'.

## Dependencies

- Docker
- Docker-Compose
- Portainer(better to have)

<h2>Usage</h2>

> docker-compose up -d inside the shell

## Watch out for
- If u Have 2 services that requires port 80, remember to change the port number of the docker compose inside the docker daemon and in the outside host 
  port : 81:81
