# redis

Remote Dictionary Server

## Now apply template to container

```sh
bastille create redis 14.1-RELEASE YourIP-Bastille
bastille bootstrap https://github.com/bastille-templates/redis
bastille template redis bastille-templates/redis --arg version=84
```
