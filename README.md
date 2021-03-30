* **WORK IN PROGRESS. BE CAREFUL!**  
* Reference sweep script for Basic (2-of-2) MultiSig wallets. NodeJS.  
* Uses [SoChain's Free API](https://sochain.com/api) by default for blockchain data and for broadcasting transactions. You can implement your own backends yourself.  
* Tested with NodeJS v14 v15. 
* Exercise caution. This reference may contain errors. This reference is provided as-is and without any guarantees or expectation of performance or security whatsoever.  
* You are solely responsible for any consequences of using this code.  
* NEVER SHARE YOUR PRIVATE KEYS. NEVER USE PRIVATE KEYS ON INSECURE SYSTEMS.  

Command-line Usage:
```
$ git clone <repository URL>
$ cd <dir> && npm install
$ N=10 PRIVATE_KEY1_BIP32= PRIVATE_KEY2= DESTINATION_ADDR= NETWORK= DERIVATION_PATH= node example.js
```
* N is the number of maximum addresses you've generated on the given network
* PRIVATE_KEY1_BIP32 is the BIP32 extended private key you backed up
* PRIVATE_KEY2 is the second private key you backed up
* DESTINATION_ADDR is where you want the swept coins to go
* NETWORK is the network for which you're sweeping coins
* DERIVATION_PATH is the derivation path shown when you back up your private keys
