# About apache-httpd-docker
A build of [Apache httpd](http://httpd.apache.org/) based on top off [Debian sid](https://www.debian.org/releases/sid/) or [Alpine Edge](https://wiki.alpinelinux.org/wiki/Edge) and therefore including the latest and greatest versions of the system libraries.

# Usage
The usage is identical to the [official httpd images](https://hub.docker.com/_/httpd/), in fact the build is based for 90% from this image.

# Version
This container is numbered version 2.4.41, to match with the latest Apache code.

# Software versions included
## Debian-based build
- Apache http: version 2.4.41
- nghttp2: version 1.40.0-1 (included in Debian sid)
- OpenSSL: version 1.1.1e-1 (included in Debian sid)
- Brotli: version 1.0.7-6 (included in Debian sid)

## Alpine-based build
- Apache http: version 2.4.41
- nghttp2: version 1.40.0-r0 (included in Alpine edge main)
- OpenSSL: version 1.1.1e-r0 (included in Alpine edge main)
- Brotli: version 1.0.7-r4 (included in Alpine edge testing)

# Maintainer
This container is built and maintained by [Cedric Roijakkers](mailto:cedric@roijakkers.be).