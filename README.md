# star_notary
star notary DAPP on Ethereum platform.

## Getting Started

- Using this app, it is possible to store your own star on ethereum contract storage, keep your own star with your own token, and buy, exchange, transfer stars registered in contract. 
  - ERC-721 Token Name : ustar
  - ERC-721 Token Symbol : uw
  - Token Address on Rinkeby network : 0x64b3fdc6dacd2a178cadc97d58696ce8ee82e035
- This project is a task in Udacity Blockchain Developer Nanodegree Program. 
- This project is constructed based on truffle Webpack box. You can see Webpack [here](https://www.trufflesuite.com/boxes/webpack).

### Prerequisites

- node.js v10.15.3
- truffle v5.0.26
- metamask v6.7.2

#### At windows OS
You may have to install 'window-build-tools' to build this project on Windows OS.
```
npm install -g node-gyp
```
```
npm install --global --production windows-build-tools
```
If it doesn't work, please refer to [here](https://github.com/nodejs/node-gyp).

### Installing

modules that you have to install are saved on package.json
So, what you need to do is
```
npm install
```

## Running the tests

Turn on your terminal and move to the project folder first.
```
truffle develop
```
```
compile
```
```
migrate --reset
```
Then, turn on another terminal. Move to the project folder.
```
cd app
```
```
npm run dev
```
Finally, you can use the starNotary test service on browser.
```
http://localhost:8080
```

## Deployment

You can deploy starNotary contract on Ethereum testnet environment.
 - before using the service, you have to have your account on rinkeby network. The best way to generate account and use service is via using metamask.
 - In addition, you have to modify truffle-config.js.
```
//in truffle-config.js
const infuraKey = "your Infura Project ID";
const mnemonic = 'your rinkbey private key';
```
```
npm install --save truffle-hdwallet-provider
```
```
truffle migrate --reset --network rinkeby
```

## Built With

* Truffle v5.0.26
* OpenZeppelin v2.3.0
* VScode v1.36.1
