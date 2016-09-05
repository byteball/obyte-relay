# Relay for Byteball network

This is a node for Byteball network that stores the entire database and forwards new storage units to peers.  The relay does not hold any private keys and cannot send payments itself.

## Install

Install node.js, clone the repository, then say
```sh
npm install
```
## Run
```sh
node start.js > log &
```
## Customize

If you want to change any defaults, refer to the documentation of [byteballcore](../../../byteballcore), the core Byteball library `require()`'d from here.
