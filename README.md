# DevOpsProject

Repo is the same as the ones i use for two domains (in production) that runs the same setup:

Traefik for managing the TLS/SSL challenge with acme \
Traefik for reverse proxy for using ports 80 and 443 for more than one service at a time \
Two similar docker-compose stack with nginx, wordpress and mysql, just different domain names \
Has been tested without any problems as of 05/08/2020