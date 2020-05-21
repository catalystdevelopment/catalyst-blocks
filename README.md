# Block explorer for catalyst

### catalyst-blocks
Block explorer for the Catalyst CryptoNote based cryptocurrency.

### Installation
It takes data from daemon turtlecoind. It should be accessible from the Internet. Run turtlecoind with open port as follows:
./Catalystd --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=17291
Just upload to your website and change 'api' variable in config.js to point to your daemon.
Development
Devs: @devopsralf

#### Note
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer & turtlecoin/turtle-explorer-js
