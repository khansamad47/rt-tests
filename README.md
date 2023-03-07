# Real-time tests for Roc Toolkit

[![Build](https://github.com/roc-streaming/rt-tests/workflows/build/badge.svg?branch=main)](https://github.com/roc-streaming/rt-tests/actions/workflows/build.yml?query=branch%3Amain) [![Matrix chat](https://matrix.to/img/matrix-badge.svg)](https://app.element.io/#/room/#roc-streaming:matrix.org)

About
-----

The scope if this repo is [non-functional](https://en.wikipedia.org/wiki/Non-functional_testing) real-time integration tests for [Roc Toolkit](https://github.com/roc-streaming/roc-toolkit) public API. These tests are supposed to run on real hardware and produce metrics to be checked for regressions. Some examples of non-functional tests are:

* service quality tests
* latency tests
* performance tests (benchmarks)
* stress tests
* tests invloving real network interfaces and audio devices

Dependencies
------------

* C++17 compiler
* CMake >= 3.0.0
* Google Test >= 1.10 (downloaded automatically)
* Roc Toolkit (should be pre-installed system-wide)

Instructions
------------

Build and run:

```
make
```

Clean build results:

```
make clean
```

Format code:

```
make fmt
```

Authors
-------

See [here](https://github.com/roc-streaming/rt-tests/graphs/contributors).

License
-------

[MPL-2.0](LICENSE)
