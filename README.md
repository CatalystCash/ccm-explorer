# CCM BlockChain Explorer
Block explorer for CCM CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon ccmd. It should be accessible from the Internet. Run ccmd with open port as follows:
```bash
./ccmd --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=9355
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

Based on :

https://github.com/Karbovanets/Karbowanec-Blockchain-Explorer
