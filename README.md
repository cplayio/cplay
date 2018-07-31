
cPlay is a PoS-based cryptocurrency.

cPlay uses libsecp256k1, libgmp, Boost1.55, OR Boost1.57,  Openssl1.01p, Berkeley DB 4.8, QT5 to compile

Block Spacing: 2 minutes
Stake Minimum Age: 8 Hours

4,0 CPL for listenig to Radio (payed to users of Bitrad.io)
0,5 CPL for Masternode owners
0,5 CPL for Staking

P2P Port: 32454
RPC Port: 32455


BUILD LINUX
-----------
1) git clone https://github.com/cplayio/cplay

2) cd cPlay/src

3) make -f makefile.unix            # Headless

(optional)

4) strip cPlayd

5) sudo cp cPlayd /usr/local/bin
