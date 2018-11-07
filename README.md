# About apache-httpd-docker
A build of [Apache httpd](http://httpd.apache.org/) based on top off [Debian sid](https://www.debian.org/releases/sid/) and therefore including the latest and greatest versions of the system libraries.

# Usage
The usage is identical to the [official httpd image](https://hub.docker.com/_/httpd/), in fact the build is based for 90% from this image.

# Version
This container is numbered version 2.4.37.1. The official Apache code is version 2.4.37, the .1 is added because of updated build dependencies.

# Software versions included
- Apache http: version 2.4.37
- nghttp2: version 1.34.0-1 (included in Debian sid)
- OpenSSL: version 1.1.1-2 (included in Debian sid)
- Brotli: version 1.0.7-1 (included in Debian sid)

# Maintainer
This container is built and maintained by [Cedric Roijakkers](mailto:cedric@roijakkers.be).