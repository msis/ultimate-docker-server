Ultimate Docker Server
======================

**UDS** is a docker compose file that you can fire on your server that will automatically enable you to have:
- git server ([Gogs](https://github.com/gogits/gogs))
- CI and CD ([drone](https://github.com/drone/drone))
- web proxy & load balancer ([traefik](https://github.com/containous/traefik))
- chat server ([Rocket.Chat](https://github.com/RocketChat/Rocket.Chat))
- OpenVPN server ([OpenVPN for Docker](https://github.com/kylemanna/docker-openvpn))
- (*to be continued*)

## Getting started
1. Clone the repo.
2. Change your main username (I used mine **msis** everywhere, so a simple replace all should work).
3. Replace `docker.localhost` with your domain name (again a replace all should do the trick).
4. And finally, fire up `docker-compose`:
```shell
docker-compose up
```
