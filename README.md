DARKCOIL - Darkcoin Lightweight Client
======================================

DARKCOIL is a minimal wallet for Darkcoin. It includes a graphical Qt-wallet and a headless daemon written in C++ based on the bitcoin core staging tree.


About
------

This is basically the official Darkcoin client with everything stripped off what Darkcoin makes unique (Darksend, Masternodes, InstantTX, etc.)

You **don't** want to use this implementation if you:

* operate a masternode (it wont work).
* operate a pool (just don't!).
* want to anonymize/denominate your coins.

If anything above applies, please refer to the official client at https://github.com/darkcoin/darkcoin

You only **want to use this** if you:

* want to simply send, recieve or store coins without experiments.
* do not want to mix, denominate or anonymize your coins.

Be aware that this is no official darkcoin client by the core developers. Always check the code and the functionality prior using this tool in production. If you find any issues, please use the issue tracker at https://github.com/vertoe/darkcoil/issues


License
-------

DARKCOIL is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

* Copyright (c) 2009-2013 Bitcoin Developers
* Copyright (c) 2013-2014 Darkcoin Developers
* Copyright (c) 2014 DARKCOIL Project (by vertoe)
