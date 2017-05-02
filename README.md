build-container-sync
===

[![Greenkeeper badge](https://badges.greenkeeper.io/retrohacker/build-container-sync.svg)](https://greenkeeper.io/)

A simple tool to keep your server's docker images in sync with https://github.com/iojs/build-containers

#Usage

Simply:

```
$ npm link
... npm stuff ...
$ build-container-sync
Docker webhook started on 8411
```

And you are good to go.

#Requirements

* Docker (needs to run without sudo)
* Your server must be registered at https://registry.hub.docker.com/u/iojs/build/settings/webhooks/
* You must have `curl` installed
