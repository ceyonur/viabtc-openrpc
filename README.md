# viabtc-openrpc

ViaBTC API OpenRPC Specification

## Install dev dependencies

Prerequisites:

- Node.JS
- npm

`$ npm install --dev`

## Documentation Server

open-rpc-generator uses Gatsby as the documentation server. There is a npm script that automatically generates a Gatsby server from the `viabtc-openrpc.json` file.

`$ npm run docs:generate`

This will generate required files for Gatsby. Then you can run the server:

```
$ cd docs/gatsby/
$ npm install
```

It can take a while to install modules. Then:

```
$ npm run start
```
