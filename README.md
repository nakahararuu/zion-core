# Zion-Core

a wrapper application for ちゃアニ. REST API, authentication, and static resource hosting.

## Build Setup
``` bash
# run dev server on http://localhost:2015
$ cp .env.default .env
$ docker-compose up

# run prodution server on http://example.xyz:80 and https://example.xyz:443
# (http://example.xyz:80 points to https://example.xyz:443)
$ cp .env.default .env
$ vim .env
$ docker-compose up
```

## Feature
- an alternative REST API for ちゃアニ
- authentication service for ちゃアニ
- an alternative static resource hosting server for ちゃアニ
- automatic HTTPS

