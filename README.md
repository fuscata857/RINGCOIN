Ringcoin integration/staging tree
================================


Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Ringcoin Developers

What is Ringcoin?
--------------------------------

If you start worrying, it will be too late! Get ready to win a diamond ring worth 6.5 carats right now!?
---------------------------------------------------------------------------------------------------------

Ringcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2.5 ~20 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 -  ~7,777,7777total coin
The rest is the same as Bitcoin.
 - 77 coins per block 4 weeks only
 -  to retarge2870000 coin t difficulty

Specially designed 6.5 carat diamond ring event!!!!!

Start time: When the first 1000 node users break through Draw date: Currently undecided. Scheduled to be paid when a specific quantity is mined or purchased on the exchange. (Scheduled to be paid to those who achieve 777777 collected coins) Limited to the first time. Coins purchased from exchanges, not necessarily mined, are recognized as holdings)
The power of our coin will provide you with the highest quality luxury house, a nice car and a luxurious and leisurely life. However, you should look at at least 10 years and invest in this coin. This coin is reserved for 2 million coins to control trading for speculative purposes for short-term investments.
From now on, the more beautiful your stories become, the busier and more enjoyable our journey will be. We wanted to create a coin that allows us to rediscover our value in countless stories around the world, so our coin was born!

This coin is pre-mined and issued in 2 million units for developers and investors.

A beautiful story with our coin!

It will be remembered as a coin of promise to marry a loved one or to be with lovers. Our coin will independently collect and record such stories in the future and remember them as beautiful coins for all lovers and love.
After downloading and installing the open source, create a new file in the .ringcoin folder and modify the file name to ringcoin.conf. Enter addnode=119.56.163.13 in the contents, save and restart your wallet to connect to our node! The administrator will stop mining immediately when the first accessor appears, and will not be involved in mining anymore. It will only connect to maintain the node.
Our coin intentionally contains the most included number 7 in the source code. A special prize is given to those who look at the source code of our coin and guess how many 7s there are!

License
-------

Ringcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Ringcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/ringcoin-project/ringcoin/tags) are created
regularly to indicate new official, stable release versions of Ringcoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./ringcoin-qt_test

