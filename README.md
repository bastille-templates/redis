# redis

Remote Dictionary Server

## Now apply template to container

```sh
bastille create redis 14.4-RELEASE YourIP-Bastille
bastille bootstrap https://github.com/bastille-templates/redis
bastille template redis bastille-templates/redis \
 --arg REDIS_VERSION=84 \
 --arg REDIS_PORT=6379 \
 --arg REDIS_MAXMEM=256mb \
 --arg REDIS_MAXPOL=allkeys-lru
```
