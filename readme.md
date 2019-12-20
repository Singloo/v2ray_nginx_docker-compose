bootstrap a v2ray server


### How to use it?

- replace `server_name` in `./nginx/nginx.conf` with your domain
- replace `/same/path/you/will/put/into/v2ray` in `./nginx/nginx.conf` with any path you want
- replace `/same/path/you/defined/in/nginx/conf` in `./v2ray/config.json` with exactly the same path you wrote in last step
- apply https certificates, put them into `nginx/cert`, replace name of `ssl_certificate`, `ssl_certificate_key` in `nginx.conf`
- Congrats, last step, buy a server, install `docker`,`docker-compose`, run `docker-compose up -d`