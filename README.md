This repository contains the source for the [libsemigroups](https://hub.docker.com/repository/docker/libsemigroups/libsemigroups-docker-arm) Docker container.

If you have [Docker](https://www.docker.com) installed, you can download this container using:
~~~
docker pull libsemigroups/libsemigroups-docker-arm
~~~
and run it by doing
~~~
docker run --rm -it libsemigroups/libsemigroups-docker-arm
~~~

If you want to use a specific version of `libsemigroups`, then use:
~~~
docker pull libsemigroups/libsemigroups-docker-arm:version-2.0.0
docker run --rm -it libsemigroups/libsemigroups-docker-arm:version-2.0.0
~~~
or, for the latest version, use:
~~~
docker pull libsemigroups/libsemigroups-docker-arm:latest
docker run --rm -it libsemigroups/libsemigroups-docker-arm:latest
~~~
