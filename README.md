# About apache-httpd-docker
A build of [Apache httpd](http://httpd.apache.org/) based on top off [Debian sid](https://www.debian.org/releases/sid/) or [Alpine Edge](https://wiki.alpinelinux.org/wiki/Edge) and therefore including the latest and greatest versions of the system libraries.

# Usage
The usage is identical to the [official httpd images](https://hub.docker.com/_/httpd/), in fact the build is based for 90% from this image.

# Version
This container is numbered version 2.4.38, to match with the latest Apache code.

# Software versions included
## Debian-based build
- Apache http: version 2.4.38
- nghttp2: version 1.36.0-1 (included in Debian sid)
- OpenSSL: version 1.1.1a-1 (included in Debian sid)
- Brotli: version 1.0.7-2 (included in Debian sid)

## Alpine-based build
- Apache http: version 2.4.38
- nghttp2: version 1.35.1-r0 (included in Alpine edge)
- OpenSSL: version 1.1.1a-r1 (included in Alpine edge)
- Brotli: version 1.0.7-r1 (included in Alpine edge testing)

# Maintainer
This container is built and maintained by [Cedric Roijakkers](mailto:cedric@roijakkers.be).