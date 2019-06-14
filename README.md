# Client-server model
This is an educational project, aim is to understand how to interact with POSIX (synchronous) socket APIs to implement a client-server architecture.

## Build
```
$ mkdir build
$ cd build
$ cmake ..
$ make
```
Requires C++14 compiler

## Usage
Run server:
```
$ ./os-net-server <port>
```
Run client:
```
$ ./os-net-client <port>
```
  
## Test
Tested manually on macOS Mojave 10.14.3 and Linux 4.12.

## Copyright
Pavel Ponomarev, 2019 (pavponn@gmail.com)

MIT License.
