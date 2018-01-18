## Bytecoin

Bytecoin, the next bitcoin, is a anonymous egalitarian digital currency based on CryptoNote technology.

## Building CryptoNote

### On *nix:

#### Dependencies

- [GCC](http://gcc.gnu.org) 4.7.3 or later
- [CMake](http://www.cmake.org) 2.8.6 or later
- [Boost](http://www.boost.org) 1.55

Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make'. The resulting executables can be found in build/release/src.

Advanced options:

Parallel build: run `make -j<number of threads>' instead of `make'.
Debug build: run `make build-debug'.
Test suite: run `make test-release' to run tests in addition to building. Running `make test-debug' will do the same to the debug version.
Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++' before running `make'.

### On Windows

#### Dependencies

- MSVC 2013 or later
- [CMake](http://www.cmake.org) 2.8.6 or later
- [Boost](http://www.boost.org) 1.55

To build, change to a directory where this file is located, and run this commands:

```sh 
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

And then do Build.
Good luck!
