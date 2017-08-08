# ownCloud: Alpine

[![Build Status](https://drone.owncloud.com/api/badges/owncloud-docker/alpine/status.svg)](https://drone.owncloud.com/owncloud-docker/alpine)
[![](https://images.microbadger.com/badges/image/owncloud/alpine:latest.svg)](https://microbadger.com/images/owncloud/alpine:latest "Get your own image badge on microbadger.com")

This is our minimal customized [Alpine](https://alpinelinux.org/) base image based on [official Alpine](https://registry.hub.docker.com/_/alpine/). It's only mostly for our testing and infra images you can find on this organization.


## Versions

To get an overview about the available versions please take a look at the [GitHub branches](https://github.com/owncloud-docker/alpine/branches/all) or our [Docker Hub tags](https://hub.docker.com/r/owncloud/alpine/tags/), these lists are always up to date.


## Volumes

* None


## Ports

* None


## Available environment variables

```

```


## Build locally

The available versions should be already pushed to the Docker Hub, but in case you want to try a change locally you can always execute the following command to get this image built locally:

```
bash update-tools.sh
IMAGE_NAME=owncloud/alpine ./hooks/build
```


## Issues, Feedback and Ideas

Open an [Issue](https://github.com/owncloud-docker/alpine/issues)


## Contributing

Fork -> Patch -> Push -> Pull Request


## Authors

* [Thomas Boerger](https://github.com/tboerger)
* [Felix Boehm](https://github.com/felixboehm)


## License

MIT


## Copyright

```
Copyright (c) 2017 Thomas Boerger <tboerger@owncloud.com>
```
