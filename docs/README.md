# tpm2-pkcs11

[![Build Status](https://travis-ci.org/tpm2-software/tpm2-pkcs11.svg?branch=master)](https://travis-ci.org/tpm2-software/tpm2-pkcs11)
[![Coverage Status](https://codecov.io/gh/tpm2-software/tpm2-pkcs11/branch/master/graph/badge.svg)](https://codecov.io/gh/tpm2-software/tpm2-pkcs11)
[![Language grade: C/C++](https://img.shields.io/lgtm/grade/cpp/g/tpm2-software/tpm2-pkcs11.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/tpm2-software/tpm2-pkcs11/context:cpp)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/tpm2-software/tpm2-pkcs11.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/tpm2-software/tpm2-pkcs11/context:python)

PKCS #11 is a Public-Key Cryptography Standard that defines a standard method to
access cryptographic services from tokens/ devices such as hardware security
modules (HSM), smart cards, etc. In this project we intend to use a TPM2 device
as the cryptographic token.

# Getting Started

* [Building](BUILDING.md) - How to get it to build
* [Initializing](INITIALIZING.md) - How to configure it
* [Installing](INSTALL.md) - How to install it

# Example Usages
* [SSH](SSH.md) - How to configure and use it with SSH.
* [P11](P11.md) - How to configure and use it with various P11 components.
* [PKCS11-TOOL](PKCS11_TOOL.md) - How to configure and use it with OpenSC's pkcs11-tool.

# Advanced Knowledge
* [Architecture](ARCHITECTURE.md) - Internal Overview
* [DB Upgrades](DB_UPGRADE.md) - What happens on a DB Version Upgrade
* [Release Process](RELEASE.md) - How releases are conducted
