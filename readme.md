# yarr

**yarr** (yet another rss reader) is a web-based feed aggregator which can be used both
as a desktop application and a personal self-hosted server.

It is written in Go with the frontend in Vue.js. The storage is backed by SQLite.

![screenshot](etc/promo.png)

## usage

The latest prebuilt binaries for Linux/MacOS/Windows are available

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
