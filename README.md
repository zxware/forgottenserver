forgottenserver 
===============

The Forgotten Server is a free and open-source MMORPG server emulator written in C++. It is a fork of the [OpenTibia Server](https://github.com/opentibia/server) project. To connect to the server, you can use [OTClient](https://github.com/edubart/otclient) or [OpenTibiaUnity](https://github.com/slavidodo/OpenTibia-Unity).

### Compiling
```shell
$ apt-get install git cmake build-essential liblua5.2-dev libgmp3-dev libmariadb-dev-compat libboost-filesystem-dev libboost-system-dev libboost-iostreams-dev libpugixml-dev libcrypto++-dev
$ mkdir build && cd build
$ cmake ..
$ make -j4
```
