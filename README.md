# Zion-Core

a backend for ちゃアニ. REST API, authentication, and static resource hosting.

Note: Currently, Zion-Core is PoC project. it's using legacy ちゃアニ PHP scripts as REST API. We need to replace legacy it.

## Build Setup
``` bash
# run dev server on http://localhost:2015
$ cp .env.default .env
$ docker-compose up

# run prodution server on http://example.xyz:80 and https://example.xyz:443
# (http://example.xyz:80 points to https://example.xyz:443)
$ cp .env.default .env
$ vim .env
$ head -2 .env
# Web Server config
HOST_NAME=example.xyz
$ docker-compose up
```

## Feature
- an alternative REST API for ちゃアニ
- authentication service for ちゃアニ
- an alternative static resource hosting server for ちゃアニ
- automatic HTTPS

