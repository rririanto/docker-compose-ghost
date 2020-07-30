### docker-ghost-platform

Quick start docker compose that run Ghost blog, [Nginx proxy](https://github.com/nginx-proxy/nginx-proxy) with TLS/SSL and MySQL database. 

### Run

Install [docker](https://docs.docker.com/get-docker/)

__Create nginx-proxy network__

$ docker network create nginx-proxy

__First Run Nginx-proxy__
 
$ cd nginx-proxy

$ docker-compose up --build -d

__Run Main Ghost__

$ cd ..

$ docker-compose up --build -d

__Finish__

Open your browser: yourdomain.com or localhost

To log in into ghost admin yourdomain.com/ghost or localhost/ghost
