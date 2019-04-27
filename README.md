Bellcore Node
============

A Bellcoin full node for building applications and services with Node.js. A node is extensible and can be configured to run additional services.

## Install

```bash
npm install -g git://github.com/bellcoin-electrum/bellcore-node.git
bellcore-node start
```

## Prerequisites

- GNU/Linux x86_64 *(for bellcoind distributed binaries)*
- Node.js v0.10, v0.12 or v4
- ZeroMQ *(libzmq3-dev for Ubuntu/Debian)*
- ~200GB of disk storage
- ~8GB of RAM

## Configuration

Bellcore includes a Command Line Interface (CLI) for managing, configuring and interfacing with your Bellcore Node.

```bash
bellcore-node create -d <bellcoin-data-dir> mynode
cd mynode
bellcore-node install <service>
bellcore-node install https://github.com/yourname/helloworld
```

This will create a directory with configuration files for your node and install the necessary dependencies. For more information about (and developing) services, please see the [Service Documentation](docs/services.md).

## Add-on Services

There are several add-on services available to extend the functionality of Bellcore:

- [Insight API for Bellcoin](https://github.com/bellcoin-electrum/insight-api-bellcoin)
- [Insight UI for Bellcoin](https://github.com/bellcoin-electrum/insight-ui-bellcoin)

## License

Code released under [the MIT license](https://github.com/bellcoin-electrum/bellcore-node/blob/master/LICENSE).

Copyright 2013-2019 BitPay, Inc.

- bitcoin: Copyright (c) 2009-2019 Bitcoin Core Developers (MIT License)
- bellcoin: Copyright (c) 2018-2019 Bellcoin Core Developers (MIT License)
