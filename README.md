REOSC Network Intelligence API
============
This is the backend service which runs along with reosc-node and tracks the network status, fetches information through JSON-RPC and connects through WebSockets to [reosc-netstats](http://stats.reosc.io) to feed information. For full install instructions please read the [wiki](https://github.com/REOSC/mn/wiki).


## Prerequisite
* reosc-node
* npm

### Hi! 
## We would love to see your node working on [REOSC-Net-STATS](http://stats.reosc.io/) Page
    http://stats.reosc.io

    $ cd ~/

    $ git clone https://github.com/REOSC/reosc-api

    $ cd reosc-api

    $ npm install

## now run:

    $ cd ~/reosc-api

    $ npm start

## Now you Can modify node.js file LINE25: to update your Masternodes Name when connected to our stats server.

    $ cd lib/node.js

    LINE25 : var INSTANCE_NAME = "REOSC_Masternode";

