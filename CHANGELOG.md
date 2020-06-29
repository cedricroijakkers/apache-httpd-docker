# Release 2.4.43.2
Updated dependencies (Debian: OpenSSL and Brotli; Alpine: OpenSSL) and added patch for Apache bug 64537.

Software versions:

Debian-based:

* Apache httpd 2.4.43
* nghttp2 1.41.0-2
* openssl 1.1.1g-1
* brotli 1.0.7-6.1

Alpine-based:

* Apache httpd 2.4.43
* nghttp2 1.41.0-r0
* openssl 1.1.1g-r0
* brotli 1.0.7-r5

Also applied a patch for the following bug: https://bz.apache.org/bugzilla/show_bug.cgi?id=64537

# Release 2.4.43.1
Updated dependencies (Debian: OpenSSL and Brotli; Alpine: OpenSSL).

Software versions:

Debian-based:

* Apache httpd 2.4.43
* nghttp2 1.40.0-1
* openssl 1.1.1g-1
* brotli 1.0.7-6+b1

Alpine-based:

* Apache httpd 2.4.43
* nghttp2 1.40.0-r0
* openssl 1.1.1g-r0
* brotli 1.0.7-r4

# Release 2.4.43
Updated Apache httpd to version 2.4.43 and updated OpenSSL to 1.1.1f.

Software versions:

Debian-based:

* Apache httpd 2.4.43
* nghttp2 1.40.0-1
* openssl 1.1.1f-1
* brotli 1.0.7-6

Alpine-based:

* Apache httpd 2.4.41
* nghttp2 1.40.0-r0
* openssl 1.1.1f-r0
* brotli 1.0.7-r4

# Release 2.4.41.3
Updated dependencies (Debian: OpenSSL; Alpine: OpenSSL).

Software versions:

Debian-based:

* Apache httpd 2.4.41
* nghttp2 1.40.0-1
* openssl 1.1.1e-1
* brotli 1.0.7-6

Alpine-based:

* Apache httpd 2.4.41
* nghttp2 1.40.0-r0
* openssl 1.1.1e-r0
* brotli 1.0.7-r4

# Release 2.4.41.2
Updated dependencies (Debian: OpenSSL and Brotli; Alpine: nghttp2, OpenSSL, and Brotli).

Software versions:

Debian-based:

* Apache httpd 2.4.41
* nghttp2 1.40.0-1
* openssl 1.1.1d-2
* brotli 1.0.7-6

Alpine-based:

* Apache httpd 2.4.41
* nghttp2 1.40.0-r0
* openssl 1.1.1d-r4
* brotli 1.0.7-r4

# Release 2.4.41.1
Updated dependencies (Debian: OpenSSL and Brotli; Alpine: nghttp2, OpenSSL, and Brotli).

Software versions:

Debian-based:

* Apache httpd 2.4.41
* nghttp2 1.39.2-1
* openssl 1.1.1d-2
* brotli 1.0.7-3

Alpine-based:

* Apache httpd 2.4.41
* nghttp2 1.39.2-r2
* openssl 1.1.1d-r2
* brotli 1.0.7-r2

# Release 2.4.41
Updated Apache httpd to version 2.4.41 (including upstream Dockerfile changes to allow compilation of `mod_md`).

Software versions:

Debian-based:

* Apache httpd 2.4.41
* nghttp2 1.39.2-1
* openssl 1.1.1c-1
* brotli 1.0.7-2

Alpine-based:

* Apache httpd 2.4.41
* nghttp2 1.39.2-r0
* openssl 1.1.1c-r0
* brotli 1.0.7-r1

# Release 2.4.39.1
Updated dependencies (OpenSSL in both Debian and Alpine, nghttp2 in Alpine only).

Software versions:

Debian-based:

* Apache httpd 2.4.39
* nghttp2 1.37.0-1
* openssl 1.1.1c-1
* brotli 1.0.7-2

Alpine-based:

* Apache httpd 2.4.39
* nghttp2 1.39.1-r0
* openssl 1.1.1c-r0
* brotli 1.0.7-r1

# Release 2.4.39
Updated Apache httpd to version 2.4.39.

Software versions:

Debian-based:

* Apache httpd 2.4.39
* nghttp2 1.37.0-1
* openssl 1.1.1b-2
* brotli 1.0.7-2

Alpine-based:

* Apache httpd 2.4.39
* nghttp2 1.38.0-r0
* openssl 1.1.1b-r1
* brotli 1.0.7-r1

# Release 2.4.38
Updated Apache httpd to version 2.4.38.

Also introduced Alpine Linux builds. Debian-based builds will be maintained alongside Alpine-based builds from now on.

Software versions:

Debian-based:

* Apache httpd 2.4.38
* nghttp2 1.36.0-1
* openssl 1.1.1a-1
* brotli 1.0.7-2

Alpine-based:

* Apache httpd 2.4.38
* nghttp2 1.35.1-r0
* openssl 1.1.1a-r1
* brotli 1.0.7-r1

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