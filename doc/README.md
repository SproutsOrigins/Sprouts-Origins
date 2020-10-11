Sprouts Origins Core
=====================

Setup
---------------------
[Sprouts Origins Core](https://www.sprocrypto.com) is the original Sprouts Origins client and it builds the backbone of the network. However, it downloads and stores the entire history of Sprouts Origins transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run Sprouts Origins on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/sproutsorigins-qt (GUI, 32-bit) or bin/32/sproutsoriginsd (headless, 32-bit)
- bin/64/sproutsorigins-qt (GUI, 64-bit) or bin/64/sproutsoriginsd (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run sproutsorigins-qt.exe.

### OSX

Drag Sprouts Origins-Qt to your applications folder, and then run Sprouts Origins-Qt.

### Need Help?

* Join our Discord server [Discord Server](https://discordapp.com/invite/9nzt37V)

Building
---------------------
The following are developer notes on how to build Sprouts Origins on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Sprouts Origins repo's [root README](https://github.com/sproutsorigins/sproutsorigins/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/) ***TODO***
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
