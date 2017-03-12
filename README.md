Bitcoin LCC integration/staging tree
=====================================

[![Build Status](https://travis-ci.org/bitcoin/bitcoin.svg?branch=master)](https://travis-ci.org/bitcoin/bitcoin)

https://bitcoincore.org

http://www.doensen.com

What is Bitcoin?
----------------

Bitcoin is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Bitcoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Bitcoin Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Bitcoin Core software, see https://bitcoin.org/en/download, or read the
[original whitepaper](https://bitcoincore.org/bitcoin.pdf).

What is Bitcoin LCC?
--------------------

Bitcoin Lossy Compression Chain (LCC) is a blockchain replacement for the Bitcoin MemPool that is designed to increase scalability of Bitcoin without causing a hard fork of the blockchain. 

*** This project is experimental and is not yet operational. ***

License
-------

Bitcoin Core & Bitcoin LCC are released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. 


Defect Reports
--------------

Defects should be emailed to llc_defects@doensen.com

Current Progress
----------------

<<< 12-Mar-2017
    Move the default linux path for the blockchain from ".bitcoin" to ".lcc_bitcoin". Ditto for other OS.

<<< 11-Mar-2017
    Added minor notes and GUI changes to indicate that this is not a bitcoin core blockchain. Started work on making this code 'alt-coin' like.

<<< 11-Mar-2017
	Removed block reward. When a block is created no block reward is given, the LCC relies on fees in bitcoin only. It does not generate it's own native token.   

<<< 10-Mar-2017 
	First release 
 

