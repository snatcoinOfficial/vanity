# SNATCOIN Address Generator and Vanity Address Generator


This library will also work with the majority of other cryptocurrencies.


Grab a new Snatcoin public/private key pair:

  ./snatgen.sh

  This will create an array with your public Snatcoin address first and your private Snatcoin address second


Snatcoin vanity generator usage:

  ./snatvanity.py YuM

  Will create a Snatcoin vanity address starting with YuM




## addrgen - minimal Bitcoin address generator in Python

This script generates a single Bitcoin address using the compressed public key format and prints it with its private key.

This version includes ability to find Snatcoin addresses as well as Snatcoin vanity addresses.

### Usage 

    python addrgen.py

### Mac OS X

For some reason, the script segfaults on OS X unless it's run in in 32-bit mode. Instead, those on OS X should run:

    bash addrgen.sh

### Generating other types of addresses

Supply the version number for your desired address  with the --otherversion switch. (supported by pywallet at least)

    python addrgen.py --otherversion=48    <- Litecoin

    python addrgen.py --otherversion=1    <- Snatcoin

If you wish to generate addresses based on a passphrase, a given private key, or some other option look at the commented lines in the test() function.

Created and Licensed Public Domain by Joric/bitcoin-dev June 2012 with minor modifications by David Sterry.  Additions in 2018 by the Snatcoin Developers.
