snakebite-docker
===

This Dockerfile will create a snakebite client on [alpine](http://alpinelinux.org/).
Total size of snakebite client image is less then 50MB - which makes it easy play
around.

Usage
---

To run snakebite client and ``ls`` HDFDS root directory:

    # docker run ravwojdyla/snakebite -n <namenode-host> -p <namenode-port> ls /


Build
---
To build your own image:

    # docker build -t $(whoami)/snakebite .

