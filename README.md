# docker-redis-ephemeral
Basic Redis image (based on Alpine) with persistence disabled.

## Description
All of the `save *` arguments in `redis.conf` have been commented-out to
disable persistence and unnecessary disk i/o when redis is only used as a
cache, message bus, and other similar scenarios.

## Relevant files
| File Name    | File Path                         |
| ------------ | --------------------------------- |
| `redis.conf` | `/usr/local/etc/redis/redis.conf` |
