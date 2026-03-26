# Timeseries Database

A timeseries database built in C++23.

## Prerequisites

- CMake 3.26+
- A C++23-capable compiler (clang++ or g++)
- [vcpkg](https://github.com/microsoft/vcpkg) with `VCPKG_ROOT` set in your environment

```sh
export VCPKG_ROOT=/path/to/vcpkg
```

## Build

```sh
make          # configure + build (Release by default)
make test     # run tests
make run      # build and run the executable
make clean    # remove the build directory
make rebuild  # clean + build
```

To build in debug mode:

```sh
make BUILD_TYPE=Debug
```

## Project structure

```
.
├── src/           # source files (add main.cpp + implementation here)
├── include/       # public headers
├── tests/         # GTest test files
├── CMakeLists.txt
├── vcpkg.json     # vcpkg dependencies
└── Makefile
```

