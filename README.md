# star_notary
star notary DAPP on Ethereum platform.

## Getting Started

- Using this app, it is possible to store your own star on ethereum contract storage, keep your own star with your own token, and buy, exchange, transfer stars registered in contract. 
  - ERC-721 Token Name : ustar
  - ERC-721 Token Symbol : uw
- This project is a task in Udacity Blockchain Developer Nanodegree Program. 
- This project is constructed based on truffle Webpack box. You can see Webpack [here](https://www.trufflesuite.com/boxes/webpack).

### Prerequisites

- node.js v10.15.3
- truffle v5.0.26

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

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* Truffle v5.0.26
* OpenZeppelin v2.3.0
* VScode v1.36.1
