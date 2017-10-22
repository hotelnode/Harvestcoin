
Harvest development tree

Harvest is a PoS-based cryptocurrency.

HC is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1

Last POW Block : 7777 Block
POW Reward: 3.5 HC per Block
POS Reward: 3.5 HC (HiPOS)
Block Spacing: 60 Seconds
Stake Minimum Age: 24 Hours

3 MegaByte Maximum Block Size (3X Bitcoin Core)

Port: 12116
RPC Port: 12117

HC includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the HC codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.


