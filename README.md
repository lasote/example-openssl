# example-openssl
Project to reuse the OpenSSL package created with Conan C and C++ package manager

Instructions (Windows):

```bash
$ git clone https://github.com/lasote/example-openssl.git
$ cd example-openssl
$ mkdir build && cd build
$ conan install ..
$ cmake .. -G "Visual Studio 14 Win64"
$ cmake --build . --config Release
$ cd bin
$ md5
```

Instructions (Linux/OSx):

```bash
$ git clone https://github.com/lasote/example-openssl.git
$ cd example-openssl
$ mkdir build && cd build
$ conan install ..
$ cmake ..
$ cmake --build .
$ cd bin
$ md5
```