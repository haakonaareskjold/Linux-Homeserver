# Homeserver
Repo is the same as the ones i use for two domains (in production) that runs the same setup(swapped out personal details):

Traefik for managing the TLS/SSL challenge with acme \
Traefik as reverse proxy for using ports 80 and 443 for more than one service/stack at a time \
Two similar docker-compose stack with nginx, wordpress and mysql, just different domain names, can scale with more domains \
Added portainer 2.0 as a service (can be put either locally or on a sub-domain?)


## testing/installation
If you want to use this, remember to change the domain names on site1 and site2 directories. \
You also need to change the environment values in both respective wordpress and db services. \
Finally change email to a valid one in the reverse-proxy/docker-compose.yml \
Remember to configure your firewall (ufw or similar) to allow port 80 and 443 TCP for ipv6 and also \
port forward port 80 and 443 on your router.

### Has been tested without any problems as of 21/09/2020
