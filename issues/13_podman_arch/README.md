# podman arch issue

From [this build](https://travis-ci.org/junaruga/ci-multi-arch-native-container-test/builds/620173481).


| Travis case | arch | dist | uname -r | result |
| ----------- | ---- | ---- | -------- | ------ |
| x86_64-fedora | amd64 | xenial | 4.15.0-1028-gcp | ok |
| aarch64-xenial-fedora | arm64 | xenial | 5.3.0-22-generic | error |
| aarch64-bionic-fedora | arm64 | bionic | 5.3.0-23-generic | error |
| ppc64le-xenial-fedora | ppc64le | xenial | 5.3.0-19-generic | error |
| ppc64le-bionic-fedora | ppc64le | bionic | 5.3.0-19-generic | error |
| s390x-xenial-fedora | s390x | xenial | 5.3.0-23-generic | error |
| s390x-bionic-fedora | s390x | bionic | 5.3.0-23-generic | error |
