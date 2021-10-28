# FakeStopOverview
**FakeStop is an secure electronic storage system with the full power of blockchain technology
**

###  Setting local blockchain
**We need to install CLI version of Ganache.**

		npm install -g ganache-cli

Ganache provides us our personal local blockchain network which we can use to develop our blockchain application. It also gives temporary test accounts with fake ethereum which we can use to run our apps. We need to start the RPC server before running our application.

##### We need to install truffle
		npm install truffle -g
Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.

#### Install Software Packages
please use the following command to install Javascript Packages before you start $ npm install , npm install web3, npm install ExpressJs.
#### Dependencies
- Truffle v5.4.12 (core: 5.4.12)
- Solidity v0.5.16 (solc-js)
- Node v14.18.1
- Web3.js v1.5.3

**To start the ganache run the command**
ganache-cli

**Deploy the smart contract to the local blockchain.

1. open truffle console by running this command:

			truffle console
1.  deploy the smart contract by using this command:

		migrate
**Now we can start the server by running this command:

		node index.js
#### Authors
Rim Joudi [Github : https://github.com/RimJoudi] Maroua Alaya [Github : https://github.com/maroua199525]

some features from this project are: users can sign in and signup.
Protection of documents to keep it from being destroyed, manipulated or forged into some other document.