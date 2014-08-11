365Coin 0.8.5 BETA
====================

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2014		365Coin Developers

Distributed under the MIT/X11 software license, see the accompanying
file COPYING or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard. This product also includes software developed by [Crypto++](http://www.cryptopp.com/) which is released under the Boost Software License 1.0.


Intro
---------------------
365Coin is a free open source peer-to-peer electronic cash system that is
completely decentralized, without the need for a central server or trusted
parties.  Users hold the crypto keys to their own money and transact directly
with each other, with the help of a P2P network to check for double-spending.


Setup
---------------------
You need the Qt4 run-time libraries to run 365Coin-Qt. On Debian or Ubuntu:
	`sudo apt-get install libqtgui4`

Unpack the files into a directory and run:

- bin/32/365coin-qt (GUI, 32-bit)
- bin/32/365coind (headless, 32-bit)
- bin/64/365coin-qt (GUI, 64-bit)
- bin/64/365coind (headless, 64-bit)

See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.


Other Pages
---------------------
- [Unix Build Notes](build-unix.md)
- [OSX Build Notes](build-osx.md)
- [Windows Build Notes](build-msw.md)
- [Coding Guidelines](coding.md)
- [Release Process](release-process.md)
- [Release Notes](release-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Unit Tests](unit-tests.md)
- [Translation Process](translation_process.md)