# Release 2.4.37.2
* Container update because of new dependency versions (OpenSSL and nghttp2). Apache httpd version unchanged at 2.4.37.
* Added libbrotli1 because using mod_brotli would fail at run-time because of missing library.

Software versions:

* Apache httpd 2.4.37
* nghttp2 1.35.1-1
* openssl 1.1.1a-1
* brotli 1.0.7-1

# Release 2.4.37.1
Container update because of new dependency versions (OpenSSL and Brotli). Apache httpd version unchanged at 2.4.37.

Software versions:

* Apache httpd 2.4.37
* nghttp2 1.34.0-1
* openssl 1.1.1-2
* brotli 1.0.7-1

# Release 2.4.37
Updated Apache httpd to version 2.4.37. TLSv1.3 patch no longer needed since it has been included in the main release branch.

Software versions:

* Apache httpd 2.4.37
* nghttp2 1.34.0-1
* openssl 1.1.1-1
* brotli 1.0.6-1

# Release 2.4.35
First release of this container.

Software versions:

* Apache httpd 2.4.35, including a TLSv1.3 patch coming from httpd Trunk
* nghttp2 1.33.0-1
* openssl 1.1.1-1
* brotli 1.0.6-1