F7Coin
================================

http://www.f7lans.com

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers
Copyright (c) 2014-2015 F7Coin Developers

What is F7coin?
----------------

F7Coin is a clone of Litecoin

License
-------

F7Coin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

There really isn't one. There's only one person working on this ( me - sp00nz ) and
I plan on updating when I can. Others are free to contribute however please contact me
if you have any changes requested.

Testing
-------

Testing is being done on the fly. If you discover any issues please let me know.


Network
-------
Add "addnode=74.221.212.139" to your f7coin.conf to connect to the master server.


Building
--------

To build F7Coin: 

    cd src; make -f makefile.unix

To build F7Coin-QT Wallet:

    qmake -o Makefile bitcoin-qt.pro
    make -f Makefile
    ./f7coin-qt

