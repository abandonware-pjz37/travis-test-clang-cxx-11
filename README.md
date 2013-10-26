* `default.clang` (**failed**: by default `c++11` is not fully supported)
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-cxx-11.png?branch=default.clang)](https://travis-ci.org/travis-ci-tester/travis-test-clang-cxx-11)
* `clang.libstd-4.8` (**failed**: installing new `stdlib++` version not help)
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-cxx-11.png?branch=clang.libstd-4.8)](https://travis-ci.org/travis-ci-tester/travis-test-clang-cxx-11)
* `clang-3.2` (**failed**: updating to `3.2` without `stdlib++4.8` update)
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-cxx-11.png?branch=clang-3.2)](https://travis-ci.org/travis-ci-tester/travis-test-clang-cxx-11)
* `clang-3.2.libstd-4.8` (**passed**)
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-cxx-11.png?branch=clang-3.2.libstd-4.8)](https://travis-ci.org/travis-ci-tester/travis-test-clang-cxx-11)

**Note**:
* test clang libc++ support: https://github.com/travis-ci-tester/travis-test-clang-with-libcxx
* install clang 3.2 version: https://github.com/travis-ci-tester/travis-test-clang-3.2
* g++ c++11 support: https://github.com/travis-ci-tester/travis-test-gcc-cxx-11
