# About apache-httpd-docker
A build of [Apache httpd](http://httpd.apache.org/) based on top off [Debian sid](https://www.debian.org/releases/sid/) and therefore including the latest and greatest versions of the system libraries.

# Usage
The usage is identical to the [official httpd image](https://hub.docker.com/_/httpd/), in fact the build is based for 90% from this image.

# Software versions included
- Apache http: version 2.4.35
- nghttp2: version 1.33.0-1 (included in Debian sid)
- Openssl: version 1.1.1-1 (included in Debian sid)

# Patches applied
- TLSv1.3 patch from Apache 2.5 (Trunk) backported and applied to Apache 2.4.35

# Maintainer
This container is built and maintained by [Cedric Roijakkers](mailto:cedric@roijakkers.be).