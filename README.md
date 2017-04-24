Ultimate Docker Server
======================

**UDS** is a docker compose file that you can fire on your server that will automatically enable you to:
- run git server ([Gogs](https://github.com/gogits/gogs))
- run CI and CD ([drone](https://github.com/drone/drone))
- run web server ([Caddy](https://github.com/mholt/caddy))
- (*to be continued*)

Caddy handles reverse proxy and load balancing too if needed.

## Getting started
Clone the repo and fire up `docker-compose`:
```shell
docker-compose up
```
