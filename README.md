# Using OpenSSL with biicode C/C++ Dependency Manager

Example code to explain [dependencies in biicode docs](http://docs.biicode.com/c++/dependencies.html).

[master branch](https://github.com/MariadeAnton/openssl_example/tree/master) uses OpenSSL v1.0.1

[openssl/1.0.2 branch](https://github.com/MariadeAnton/openssl_example/tree/openssl/1.0.2) uses OpenSSL v1.0.2
   

Update to v1.0.2 → change `biicode.conf` file to:

```
[requirements]
    lasote/openssl(v1.0.2): 0

[includes]
    openssl/md5.h: lasote/openssl/include
```