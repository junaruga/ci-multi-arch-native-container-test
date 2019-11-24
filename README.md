# ci-multi-arch-native-container-test

[![Build Status](https://travis-ci.org/junaruga/ci-multi-arch-native-container-test.svg?branch=master)](https://travis-ci.org/junaruga/ci-multi-arch-native-container-test)

CI multiple CPU architectures test using container.
This repository is focusing to test non-Ubuntu Linux distribution (Fedora, RHEL) multiple architectures cases using Travis native multiple architectures features. [1]

## Sister projects

* [ci-multi-arch-native-test](https://github.com/junaruga/ci-multi-arch-native-test): This project is focusing Travis Ubuntu native cases. No container and no QEMU.
* [ci-multi-arch-test](https://github.com/junaruga/ci-multi-arch-test): This project has both some CIs native and emulated architecture cases.

## References

* [1] https://blog.travis-ci.com/2019-11-12-multi-cpu-architecture-ibm-power-ibm-z
