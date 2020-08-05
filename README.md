# DevOpsProject

Repo is the same as the ones i use for two domains (in production) that runs the same setup:

Traefik for managing the TLS/SSL challenge with acme \
Traefik for reverse proxy for using ports 80 and 443 for more than one service at a time \
Two similar docker-compose stack with nginx, wordpress and mysql, just different domain names \


## testing/installation
If you want to use this, remember to change the domain names on site1 and site2 directories. \
You also need to change the environment values in both respective wordpress and db services. \
Finally change email to a valid one in the reverse-proxy/docker-compose.yml

### Has been tested without any problems as of 05/08/2020