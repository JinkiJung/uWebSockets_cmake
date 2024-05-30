# uWebSockets_cmake
A lovely tutorial for how to make the simplest C++ code working with uWebSockets and CMake!

## Setup
In the root folder, clone and build the uWebSocket by following the commands below:

```
git clone --recurse-submodules git@github.com:uNetworking/uWebSockets.git
cd uWebSockets
WITH_OPENSSL=1 make
```

Coming back to the root folder:

```
cd ..
```

Make a build folder and build the source from there:

```
mkdir build && cd build && cmake .. && make
```

Execute the application in the build folder:

```
./Main
```

Expected output:

```
Listening for connections...
```

Ctrl + C to terminate it.

## Acknowledge

The source codes used in this project were derived from various StackOverflow posts below and the uWebSockets guideline.

- https://stackoverflow.com/questions/75777485/integrating-uwebsockets-into-a-cmake-project
- https://stackoverflow.com/questions/73573954/correct-way-to-install-and-run-uwebsockets-in-c
- https://github.com/uNetworking/uWebSockets/blob/master/misc/READMORE.md#putting-it-all-together


Feel free to make a pull request on this to make it simpler.

### Last updated - 30th May, 2024
