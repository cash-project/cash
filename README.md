Cash integration/staging tree
HEAD
Cash integration/staging tree
ce04e053426cfb875a78c3e3047ec194ca7e3d63


http://cash-project.eu5.org (coming soon...)

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Cash Developers

What is Cash?
----------------

Cash is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 5 minute block targets
 - subsidy halves in 420k blocks (~4 years)
 - ~52 million total coins

The rest is the same as Bitcoin.
 - 80 coins per block
 - 4032 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Cash client sofware, see http://cash-project.eu5.org.

License
-------

Cash is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Cash
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/cash-project/cash/tags) are created
regularly to indicate new official, stable release versions of Cash.

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
    ./cash-qt_test

# cash
currency
d1e2a360c3e03d34d6a2f9a2bcfa223a7c37aa1b

# cash
currency
 d1e2a360c3e03d34d6a2f9a2bcfa223a7c37aa1b
 ce04e053426cfb875a78c3e3047ec194ca7e3d63
