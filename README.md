# SkipChat

**SkipChat is a secure, distributed peer-to-peer messaging service**

SkipChat is a secure, distributed peer-to-peer messaging service that works
offline. It works by having a community of users transmit messages, hop to hop,
creating a kind of dynamic mesh network that does not need to be fully
connected for messages to be able to be sent. Essentially, transmitted messages
can travel through other devices using SkipChat, and messages can spread
geographically when these devices move and come in proximity with other devices
running SkipChat.

This technology could be applied in a variety of scenarios, especially when
traditional infrastructure is not available. For example, SkipChat could be
incredibly useful tool in areas where disasters have occurred. It could also be
useful in developing countries or areas where traditional cellular networks are
not available, either due to lack of infrastructure or due to frequent power
outages.

SkipChat implements a lightweight peer-to-peer networking protocol to achieve
decentralized messaging, and it uses strong cryptography on top of that to
provide confidentiality, message integrity, and anonymity. In the system,
public keys serve are used for both encryption and addressing. Our
cryptographic protocol uses asymmetric and symmetric key encryption to
efficiently and securely transport data. Details of the protocol can be found
in our presentation, or in the source files.

## License

Copyright (c) 2015 Anish Athalye, Ankush Gupta, and Katie Siegel. All
contributions from the authors are released under the MIT license. See
[LICENSE.md][license] for details.

The licenses for components used in this project are as follows:

* LGSimpleChat is copyrighted by Logan Wright and distributed under the Mozilla
  Public License Version 2.0.
* OpenSSL is copyrighted by the OpenSSL project and dual-licenced under Apache
  License 1.0 and the 4-clause BSD License.

[license]: LICENSE.md
