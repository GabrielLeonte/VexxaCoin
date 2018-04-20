Vexxacoin Core
=============

Setup
---------------------
Vexxacoin Core is the original Vexxacoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Vexxacoin transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Vexxacoin Core, visit [vexxacoin.org](https://vexxacoin.org).

Running
---------------------
The following are some helpful notes on how to run Vexxacoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/vexxacoin-qt` (GUI) or
- `bin/vexxacoind` (headless)

### Windows

Unpack the files into a directory, and then run vexxacoin-qt.exe.

### OS X

Drag Vexxacoin-Core to your applications folder, and then run Vexxacoin-Core.

### Need Help?

* See the documentation at the [Vexxacoin Wiki](https://vexxacoin.info/)
for help and more information.
* Ask for help on [#vexxacoin](http://webchat.freenode.net?channels=vexxacoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=vexxacoin).
* Ask for help on the [VexxacoinTalk](https://vexxacointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Vexxacoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Vexxacoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/vexxacoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [VexxacoinTalk](https://vexxacointalk.io/) forums.
* Discuss general Vexxacoin development on #vexxacoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=vexxacoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
