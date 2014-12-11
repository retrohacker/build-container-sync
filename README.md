build-container-sync
===

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

You need to have docker configured to run without sudo on your system and https://registry.hub.docker.com/u/iojs/build/settings/webhooks/ needs to point to your server.
