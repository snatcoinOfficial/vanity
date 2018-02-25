## SNATCOIN Address Generator and Vanity Address Generator


This library will also work with the majority of other cryptocurrencies.


### Setting up

    git clone https://github.com/snatcoinOfficial/vanity.git
    cd vanity 
    chmod +x addrgen.py addrgen.sh snatgen.sh snatvanity.py snatloop.py


### Grab a new Snatcoin public/private key pair:

    ./snatgen.sh

  This will create an array with your public Snatcoin address first and your private Snatcoin address second


### Snatcoin CPU Vanity Generator usage:

    ./snatvanity.py YuM

  Will create a Snatcoin vanity address starting with YuM
  
    
### Snatcoin CPU Vanity Generator [looping] usage:

    ./snatloop.py YuM

  Will create a list of Snatcoin vanity address starting with YuM


### Usage 

    python addrgen.py

### Mac OS X

For some reason, the script segfaults on OS X unless it's run in in 32-bit mode. Instead, those on OS X should run:

    bash addrgen.sh

### Generating other types of addresses

Supply the version number for your desired address  with the --otherversion switch. (supported by pywallet at least)

    python addrgen.py --otherversion=48    <- Litecoin
    python addrgen.py --otherversion=1     <- Snatcoin

If you wish to generate addresses based on a passphrase, a given private key, or some other option look at the commented lines in the test() function.


Created and Licensed Public Domain by Joric/bitcoin-dev June 2012 with minor modifications by David Sterry.  
Modifications on February 26th 2018 by the Snatcoin Developers.
