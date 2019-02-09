mFm coin Core
=============

Setup
---------------------
mFm coin Core is the original mFm coin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of mFm coin transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download mFm coin Core, visit [mfmcoin.org](https://mfmcoin.org).

Running
---------------------
The following are some helpful notes on how to run mFm coin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/mfmcoin-qt` (GUI) or
- `bin/mfmcoind` (headless)

### Windows

Unpack the files into a directory, and then run mfmcoin-qt.exe.

### OS X

Drag mFm coin-Core to your applications folder, and then run mFm coin-Core.

### Need Help?

* See the documentation at the [mFm coin Wiki](https://mfmcoin.info/)
for help and more information.
* Ask for help on [#mfmcoin](http://webchat.freenode.net?channels=mfmcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=mfmcoin).
* Ask for help on the [mFmcoinTalk](https://mfmcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build mFm coin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The mFm coin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [mFmcoinTalk](https://mfmcointalk.io/) forums.
* Discuss general mFm coin development on #mfmcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=mfmcoin-dev).

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
