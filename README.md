# About apache-httpd-docker
A build of [Apache httpd](http://httpd.apache.org/) based on top off [Debian sid](https://www.debian.org/releases/sid/) or [Alpine Edge](https://wiki.alpinelinux.org/wiki/Edge) and therefore including the latest and greatest versions of the system libraries. Also included a patch for Apache bug 64537, which is not yet included in the upstream 2.4 branch.

# Usage
The usage is identical to the [official httpd images](https://hub.docker.com/_/httpd/), in fact the build is based for 90% from this image.

# Version
This container is numbered version 2.4.46, to match with the latest Apache code.

# Software versions included
## Debian-based build
* Apache httpd: 2.4.46
* nghttp2: 1.41.0-3
* openssl: 1.1.1g-1
* brotli: 1.0.9-2

## Alpine-based build
* Apache httpd: 2.4.46
* nghttp2: 1.41.0-r0
* openssl: 1.1.1g-r0
* brotli: 1.0.9-r0

Patch included for the following Apache bug: https://bz.apache.org/bugzilla/show_bug.cgi?id=64537

# Maintainer
This container is built and maintained by [Cedric Roijakkers](mailto:cedric@roijakkers.be).