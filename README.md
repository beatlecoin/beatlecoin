Beatlecoin integration/staging tree
================================

http://www.beatlecoin.org

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers
Copyright (c) 2014 Beatlecoin Developers

What is Beatlecoin?
----------------

Beatlecoin is a fork version of Litecoin using scrypt as a proof-of-work algorithm with faster block-time. The coin is dedicated to the start of worldwide Beatlemania 50 years ago.
 - 64 second block targets
 - several superblocks (up to 35X)
 - only one million total coins (instead of 84 millions of Litecoin)
 - difficulty retargets every 8 minutes
 - only 3 confirmations needed

Block rewards:

Standart subsidy (after 911 block) - 1 BEA

First 100 blocks - 0.04 BEA
101-200 b - 0.16 BEA
201-300 b - 0.24 BEA
301-400 b - 0.3804 BEA
401-909 b - 0.85 BEA

Superblocks are: 64, 910 (one after 909), 1963-1970 and others.


Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. Tags are created regularly to indicate new official, stable release versions of Beatlecoin.

