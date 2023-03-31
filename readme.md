# yarr

**yarr** (yet another rss reader) is a web-based feed aggregator which can be used both
as a desktop application and a personal self-hosted server.

It is written in Go with the frontend in Vue.js. The storage is backed by SQLite.

![screenshot](etc/promo.png)

## usage

This is an exact fork of the original yarr repo I cloned and built the Docker image to create it myself. Feel free to use the Docker Compose below.

```
version: '3.3'
services:
    yarr:
        ports:
            - '7070:7070'
        volumes:
            - '/docker/yarr:/data'
        image: itsnoted/yarr
```

## credits

[Feather](http://feathericons.com/) for icons.
