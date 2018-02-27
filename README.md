## SNATCOIN CPU Address Generator and CPU Vanity Address Generator


This library will help you create:
 
  * public and private key pairs for Snatcoin addresses
  * Snatcoin vanity addresses

Uses Python 2.7.6


### Setting up

    git clone https://github.com/snatcoinOfficial/vanity.git
    cd vanity


### Grab a new Snatcoin public/private key pair:

    ./snatgen.sh

  This will create an array with your public Snatcoin address first and your private Snatcoin address second


### Snatcoin CPU Vanity Generator usage:

    ./snatvanity.py SNAT

  Will create a Snatcoin vanity address starting with SNAT
  
    
### Snatcoin CPU Vanity Generator [looping] usage:

    ./snatloop.py SNAT

  Will create a list of Snatcoin vanity address starting with SNAT


### Mac OS X

For some reason, the script segfaults on OS X unless it's run in in 32-bit mode. Instead, those on OS X should run:

    bash snatgen.sh


Created and Licensed Public Domain by Joric/bitcoin-dev June 2012 with minor modifications by David Sterry.  
Modifications on February 26th 2018 by the Snatcoin Developers.
